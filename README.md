# Jumlah-Data-pengangguran-Gen-z

import pandas as pd

# Membuat data pengangguran Gen Z
data = {
    'Tahun': [2024] * 8,  # Tahun 2024
    'Usia': [18, 19, 20, 21, 22, 23, 24, 25],  # Usia 18-25 tahun
    'Jumlah_Pengangguran': [500000, 450000, 400000, 350000, 300000, 250000, 200000, 150000]  # Contoh jumlah pengangguran
}

# Membuat DataFrame
df = pd.DataFrame(data)

# Menampilkan DataFrame
print(df)

# Menyimpan DataFrame ke file CSV
df.to_csv('pengangguran_gen_z_2024.csv', index=False)
