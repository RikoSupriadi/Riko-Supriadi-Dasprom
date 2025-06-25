# Soal 1: Throw Custom Exception
def cetak_jumlah_orang():
    try:
        jumlah = int(input("Masukkan jumlah orang: "))
        print(f"Input jumlah: {jumlah}")
        if jumlah <= 0:
            raise ValueError("Jumlah orang tidak valid (harus > 0)")
        for i in range(1, jumlah + 1):
            print(f"Mencetak angka: {i}")
    except ValueError as e:
        print(f"Error: {e}")

# Soal 2: Menangani Banyak Exception
def hitung_rata_rata(nilai_list):
    try:
        print(f"Input list: {nilai_list}")
        total = sum(nilai_list)
        print(f"Total: {total}")
        rata2 = total / len(nilai_list)
        print(f"Rata-rata: {rata2}")
        return rata2
    except ZeroDivisionError:
        print("Error: List kosong, tidak bisa menghitung rata-rata.")
    except TypeError:
        print("Error: Semua elemen dalam list harus berupa angka.")

# Contoh penggunaan fungsi
if __name__ == "__main__":
    # Soal 1
    cetak_jumlah_orang()

    # Soal 2
    data1 = [10, 20, 30]         # valid
    data2 = []                   # list kosong
    data3 = [10, "dua", 30]      # ada elemen bukan angka

    print("\nRata-rata data1:", hitung_rata_rata(data1))
    print("Rata-rata data2:", hitung_rata_rata(data2))
    print("Rata-rata data3:", hitung_rata_rata(data3))
