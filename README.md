Inggris
Indonesia

nama = input("fairuz abdillah zailany :")
print("selamat datang", fairuz abdi, "berpetualang")

jawaban = masukan(
    "Anda berada di jalan tanah, itu telah berakhir dan Anda dapat pergi ke kiri atau ke kanan. Cara mana yang ingin Anda tuju?

 ").lebih rendah()

jika jawaban == "keluar":
    jawaban = masukan(
        "Kamu datang ke sungai, kamu bisa berjalan di sekitarnya atau berenang menyeberang? Ketik berjalan untuk berjalan-jalan dan berenang untuk berenang menyeberang: ")

    jika jawaban == "berenang":
        print("Kamu berenang dan dimakan buaya.")
    jawaban elif == "berjalan":
        print("Kamu berjalan bermil-mil jauhnya, kehabisan air dan kamu kalah dalam permainan.")
    kalau tidak:
        print('Bukan pilihan yang valid. Anda kalah.')

jawaban elif == "benar":
    jawaban = masukan(
        "Kamu datang ke jembatan, kelihatannya goyah, kamu mau menyeberang atau balik (cross/back)? ")

    jika jawaban == "kembali":
        print("Anda kembali dan kalah.")
    jawaban elif == "cross":
        jawaban = masukan(
            "Kamu menyeberangi jembatan dan bertemu orang asing. Apakah kamu berbicara dengan mereka (ya/tidak)?")

        jika jawaban == "ya":
            print("Anda berbicara dengan stanger dan mereka memberi Anda emas. Anda MENANG!")
        jawaban elif == "tidak":
            print("Anda mengabaikan orang asing dan mereka tersinggung dan Anda kalah.")
        kalau tidak:
            print('Bukan pilihan yang valid. Anda kalah.')
    kalau tidak:
        print('Bukan pilihan yang valid. Anda kalah.')

kalau tidak:
    print('Bukan pilihan yang valid. Anda kalah.')

print("Terima kasih sudah mencoba", fairuz abdillah zailany)
