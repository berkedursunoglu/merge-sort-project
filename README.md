# Merge Sort Project

##www.patika.dev merge sort projesi

---

[16,21,11,8,12,22] Merge Sort

## 1.Problem
        [16,21,11,8,12,22]
* 1.aşama [16,21,11] [8,12,22]
* 2. aşama [16,21] [11] [8] [12,22]
* 3. aşama [16] [21] [11] [8] [12] [22]
* **Parçalama işleminden sonra birleştirerek sıralama işlemi
* 4.aşama [16,21] [11] [8,12] [22]
* 5. aşama [11,16,21] [8,12,22]
* 6. aşama [8,11,12,16,21,22]

---

## 2. Problem

Her satırda n-1 den O(n) kere işlem yapılıyor.
1. aşamadan 6. aşamaya kadar işlem her işlemde yarıya düşer ve 2^x = n den logn elde edilir.

Bu sebeple big o gösterimi O(nlogn)'dir


