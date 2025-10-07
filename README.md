# insertion---selection---sort
lnsertion ve selection sort örnek1
Başlangıç: [22, 27, 16, 2, 18, 6]

Pass 1 (key = 27):
  Sonuç: [22, 27, 16, 2, 18, 6]

Pass 2 (key = 16):
  shifting: [22, 27, 27, 2, 18, 6]
  shifting: [22, 22, 27, 2, 18, 6]
  Sonuç: [16, 22, 27, 2, 18, 6]

Pass 3 (key = 2):
  shifting: [16, 22, 27, 27, 18, 6]
  shifting: [16, 22, 22, 27, 18, 6]
  shifting: [16, 16, 22, 27, 18, 6]
  Sonuç: [2, 16, 22, 27, 18, 6]

Pass 4 (key = 18):
  shifting: [2, 16, 22, 27, 27, 6]
  shifting: [2, 16, 22, 22, 27, 6]
  Sonuç: [2, 16, 18, 22, 27, 6]

Pass 5 (key = 6):
  shifting: [2, 16, 18, 22, 27, 27]
  shifting: [2, 16, 18, 22, 22, 27]
  shifting: [2, 16, 16, 18, 22, 27]
  Sonuç: [2, 6, 16, 18, 22, 27]

Sıralı dizi: [2, 6, 16, 18, 22, 27]

Big-O:
  Best Case: O(n)
  Average Case: O(n^2)
  Worst Case: O(n^2)
  Space Complexity: O(1)

18 dizide index 3 (1-based pos 4).
=> 18 -> Average case
Başlangıç: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Adım 1: swap(0, 4) -> [2, 3, 5, 8, 7, 9, 4, 15, 6]

Adım 2: min zaten index 1 (swap ile değişim yok) -> [2, 3, 5, 8, 7, 9, 4, 15, 6]

Adım 3: swap(2, 6) -> [2, 3, 4, 8, 7, 9, 5, 15, 6]

Adım 4: swap(3, 6) -> [2, 3, 4, 5, 7, 9, 8, 15, 6]

İlk 4 adım sonrası dizi: [2, 3, 4, 5, 7, 9, 8, 15, 6]

Selection Sort Big-O: Best/Average/Worst = O(n^2)
