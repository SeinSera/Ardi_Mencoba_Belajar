# Coba dulu gak sih
Hehehe

# Kumpulan Soal
## Soal 1
### Soal
Buatlah sebuah program yang dapat menghitung luas dan keliling lingkaran dengan memasukkan jari-jari lingkaran.

### Jawaban
```python
import math

def hitung_luas_keliling_lingkaran(jari_jari):
    luas = math.pi * jari_jari ** 2
    keliling = 2 * math.pi * jari_jari
    return luas, keliling