# latihan 1. membuat program menentukan nilai akhir 

input :

    #!/usr/bin/python3
    nama = input("Masukkan nama:")
    uts = input("Masukkan nilai UTS:")
    uas = input("Masukkan nilai UAS:")
    tugas = input("Masukkan nilai Tugas:")
    akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
    keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
    if akhir > 80:
    huruf = "A"
    elif akhir > 70:
    huruf = "B"
    elif akhir > 50:
    huruf = "C"
    elif akhir > 40:
    huruf = "D"
    else:
    huruf = "E"
    print("\nNama :",nama)
    print("Nilai UTS :",uts)
    print("Nilai UAS :",uas)
    print("Nilai Tugas :",tugas)
    print("Nilai Akhir :",akhir)
    print("\nNilai Huruf :",huruf)
    print("Keterangan :",keterangan)

output: 
![Screenshot 2024-10-29 212946](https://github.com/user-attachments/assets/6eab4602-7a2b-4396-94b9-e2dc011d9c8f)

algoritma: 
1. Input Data:
- Minta pengguna untuk memasukkan nama.
- Minta pengguna untuk memasukkan nilai UTS.
- Minta pengguna untuk memasukkan nilai UAS.
- Minta pengguna untuk memasukkan nilai Tugas.
2. Hitung Nilai Akhir:
- Gunakan rumus untuk menghitung nilai akhir:
  Nilai Akhir = (20% dari Tugas) + (40% dari UTS) + (40% dari UAS)
- Hitung hasilnya dan simpan sebagai nilai akhir
3. tentukan Keterangan:
   Jika nilai akhir lebih dari 60, set keterangan ke "LULUS", jika tidak set ke "TIDAK LULUS".
   Tentukan Nilai Huruf:
- Jika nilai akhir lebih dari 80, huruf = "A"
- Jika nilai akhir lebih dari 70, huruf = "B"
- Jika nilai akhir lebih dari 50, huruf = "C"
- Jika nilai akhir lebih than 40, huruf = "D"
- Jika tidak, huruf = "E"
4. Output Hasil:
   Cetak nama, nilai UTS, nilai UAS, nilai tugas, nilai akhir, nilai huruf, dan keterangan.

flowchart :

![Screenshot 2024-10-30 170201](https://github.com/user-attachments/assets/3711a005-573c-429d-a0dc-5303e17e2492)

# LATIHAN 2 (membuat program menampilkan gaji karyawan)
input :

    #!/usr/bin/python3
      gaji = int(input("Masukkan gaji: "))
      berkeluarga = (False, True)[input("Sudah berkeluarga? (Y/T): ") == "Y"]
      punya_rumah = (False, True)[input("Punya rumah? (Y/T): ") == "Y"]

    if gaji > 3000000:
        print("Gaji sudah di atas UMR")
        
    if berkeluarga:
        print("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print("Tidak perlu ikutan asuransi")
    
    if punya_rumah:
        print("Wajib bayar pajak rumah")
    else:
        print("Tidak wajib bayar pajak rumah")
    else:  
        print("Gaji belum UMR")


output : 
    ![Screenshot 2024-10-30 172036](https://github.com/user-attachments/assets/92af5370-b24e-4f89-a931-a6c42ac3fd9e)

algoritma : 
1. Mulai: Program dimulai.
2. Input Gaji: Minta pengguna untuk memasukkan gaji dan simpan nilainya.
3. Input Status Keluarga: Tanyakan kepada pengguna apakah mereka sudah berkeluarga (Y/T).
Jika jawabannya "Y", simpan sebagai True, jika tidak, simpan sebagai False.
4. Input Status Rumah: Tanyakan kepada pengguna apakah mereka punya rumah (Y/T).
Jika jawabannya "Y", simpan sebagai True, jika tidak, simpan sebagai False.
5. Cek Gaji: Jika gaji lebih dari 3.000.000: tampilkan pesan "Gaji sudah di atas UMR".
6. Cek Status Keluarga: Jika pengguna berkeluarga: Tampilkan pesan "Wajib ikutan asuransi dan menabung untuk pensiun". Jika tidak berkeluarga:Tampilkan pesan "Tidak perlu ikutan asuransi".
7. Cek Status Rumah: Jika pengguna punya rumah: Tampilkan pesan "Wajib bayar pajak rumah". Jika tidak punya rumah: Tampilkan pesan "Tidak wajib bayar pajak rumah".
8. Jika Gaji Tidak Lebih dari 3.000.000: Tampilkan pesan "Gaji belum UMR".
9. Selesai: Program berakhir.

flowchart:
![Screenshot 2024-10-30 175205](https://github.com/user-attachments/assets/8b8ce821-0882-4417-b41a-4db0fbbad7df)

#LATIHAN 3 penggunaan kondisi OR program membandingkan 3 input bilangan, apabila penjumlahan 2 bilangan hasilnya sama dengan bilangan lainnya, maka cetak pernyataan “BENAR”
    input: 
    
            #!/usr/bin/python3
            a = int(input("Masukkan bilangan A: "))
            b = int(input("Masukkan bilangan B: "))
            c = int(input("Masukkan bilangan C: "))
            if a+b == c or b+c == a or c+a == b:
             print("BENAR")
            else:
             print("SALAH")

output : 

 
 algoritma : 
 1. Mulai:
- Program dimulai.
2. Input Bilangan:
-Minta pengguna untuk memasukkan bilangan A dan simpan nilainya.
-Minta pengguna untuk memasukkan bilangan B dan simpan nilainya.
-Minta pengguna untuk memasukkan bilangan C dan simpan nilainya.
3. Cek Penjumlahan:
Periksa apakah salah satu dari kondisi berikut benar:
-Apakah A + B sama dengan C?
-Apakah B + C sama dengan A?
-Apakah C + A sama dengan B?
4. Output Hasil:
-Jika salah satu kondisi di atas benar, tampilkan "BENAR".
-Jika tidak ada yang benar, tampilkan "SALAH".
5. Selesai:
-Program berakhir.

flowchart: 
![Screenshot 2024-10-30 182151](https://github.com/user-attachments/assets/94fa11ac-6d07-4c20-bae0-dd53e7bffa14)
# latihan 3 : buat program python untuk kasus berikut : 
          #kasus 1 : program pemesanan tiket bioskop 
    Buat program yang menghitung harga tiket bioskop. Tiket reguler berharga Rp50.000,
    sedangkan tiket VIP berharga Rp100.000. Jika user memiliki kartu member, mereka
    mendapatkan diskon 20% dari harga tiket. Program ini harus meminta tipe tiket dan status
    member dari user, lalu menghitung total harga yang harus dibayar.
input : 

    # Harga tiket
    harga_reguler = 50000
    harga_vip = 100000
    
    # Meminta input dari pengguna
    tipe_tiket = input("Masukkan tipe tiket (reguler/VIP): ").strip().lower()
    member = input("Apakah Anda memiliki kartu member? (Y/T): ").strip().upper()
  
    # Menentukan harga tiket berdasarkan tipe
    harga_tiket = harga_reguler if tipe_tiket == "reguler" else harga_vip if tipe_tiket == "vip" else 0
    
    # Menghitung total harga
    diskon = 0.2 if member == "Y" else 0
    total_harga = harga_tiket * (1 - diskon)
    
    # Menampilkan hasil
    if harga_tiket > 0:
        print(f"Harga tiket: Rp{harga_tiket}")
        print(f"Total yang harus dibayar: Rp{total_harga:.2f}")
    else:
        print("Tipe tiket yang dimasukkan tidak valid.")
  output : 
![Screenshot 2024-10-30 183722](https://github.com/user-attachments/assets/ef3c8aca-f7c1-400c-b7c9-842abc3927de)

 algoritma : 
 1. Mulai: Program dimulai.
 2. Definisikan Harga Tiket: Tentukan harga tiket reguler (Rp50.000) dan VIP (Rp100.000).
 3. Input Tipe Tiket: Minta pengguna untuk memasukkan tipe tiket (reguler/VIP).
 4. Input Status Member: Minta pengguna untuk memasukkan status member (Y/T).
 5.Tentukan Harga Tiket:
-Jika tipe tiket adalah "reguler", set harga_tiket ke harga_reguler.
-Jika tipe tiket adalah "VIP", set harga_tiket ke harga_vip.
-Jika tipe tiket tidak valid, set harga_tiket ke 0.
 6.Tentukan Diskon:
-Jika pengguna memiliki kartu member (Y), set diskon ke 0.2 (20%).
-Jika tidak, set diskon ke 0.
 7. Hitung Total Harga:
-Hitung total_harga dengan rumus: harga_tiket * (1 - diskon).
 8.Tampilkan Hasil:
-Jika harga_tiket lebih dari 0, tampilkan harga tiket dan total yang harus dibayar.
-Jika tidak, tampilkan pesan bahwa tipe tiket tidak valid.
 9. Selesai: Program berakhir.

flowchart : 
![Screenshot 2024-10-30 191219](https://github.com/user-attachments/assets/1d9dcd74-0edf-4291-bea7-fc0dabe030ec)

    #kasus 2 : program kalkulator sederhana 
    Buat program kalkulator yang menerima dua angka dan satu operator aritmatika dari pengguna (penjumlahan, pengurangan, perkalian, atau pembagian). Program akan
    menghitung hasil sesuai dengan operator yang dipilih.
  input :

      # Meminta input dari pengguna
    angka1 = float(input("Masukkan angka pertama: "))
    angka2 = float(input("Masukkan angka kedua: "))
    operator = input("Masukkan operator (+, -, *, /): ")
    
    # Menghitung hasil berdasarkan operator
    if operator == "+":
        hasil = angka1 + angka2
        print(f"Hasil: {angka1} + {angka2} = {hasil}")
    elif operator == "-":
        hasil = angka1 - angka2
        print(f"Hasil: {angka1} - {angka2} = {hasil}")
    elif operator == "*":
        hasil = angka1 * angka2
        print(f"Hasil: {angka1} * {angka2} = {hasil}")
    elif operator == "/":
        if angka2 != 0:  # Menghindari pembagian dengan nol
            hasil = angka1 / angka2
            print(f"Hasil: {angka1} / {angka2} = {hasil}")
        else:
            print("Error: Pembagian dengan nol tidak diperbolehkan.")
    else:
        print("Error: Operator tidak valid. Gunakan +, -, *, atau /.")

  output : 
  ![Screenshot 2024-10-30 191747](https://github.com/user-attachments/assets/497c9b9f-591c-41a8-812f-854b9776d404)

  algoritma: 
  1. Input Pengguna: Program meminta pengguna untuk memasukkan dua angka dan satu operator aritmatika.
  2. Pemeriksaan Operator: Menggunakan if, elif, dan else untuk menentukan operasi yang akan dilakukan berdasarkan operator yang dimasukkan.
  3. Penghitungan Hasil:
- Jika operator adalah "+", maka program melakukan penjumlahan.
- Jika operator adalah "-", maka program melakukan pengurangan.
- Jika operator adalah "*", maka program melakukan perkalian.
- Jika operator adalah "/", program memeriksa apakah angka kedua bukan nol sebelum melakukan pembagian. Jika nol, program akan menampilkan pesan error.
 4. Output: Program menampilkan hasil perhitungan atau pesan error jika input tidak valid.

  flowchart :
  ![Screenshot 2024-10-30 195706](https://github.com/user-attachments/assets/5df461e9-6589-4329-86ea-5df485c0cdac)



