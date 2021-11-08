# LAB2 LATIHAN 1

## SOAL

![img](gambar/tugas1.PNG)

untuk mengerjakan bisa menggunakan syntax di bawah ini :

    N=int(input("banyaknya data = "))
    if N>0:
        i=1
        x=int(input("data ke -"+str(i)+"="))
        max=x;total=x
        for i in range(2,N+1):
            x=int (input("data ke -"+str(i)+"="))
            total+=x
            if max<x:
                max=x

        print("bilangan terbesar =",max)

dan di bawah ini adalah outputnya :

![img](gambar/outputl2l1.PNG)

# LAB 2 LATIHAN 2

## SOAL

![img](gambar/tugas2.PNG)

untuk mengerjakan bisa menggunakan syntax di bawah ini :

    data = []
    for i in range (5):
        x =int(input("masukan bilangan : "))
        data.append(x)
    print('data sebelum diurutkan: ',data)
    list.sort(data)
    print('data setelah diurutkan: ',data)

dan di bawah ini adalah outputnya :

![img](gambar/outputl2l2.PNG)

# LAB 3 LATIHAN 1

## SOAL

![img](gambar/tugas3.PNG)

untuk mengerjakan bisa menggunakan syntax di bawah ini :

    baris = 10
    kolom = baris

    for bar in range(baris):
        for col in range(kolom):
            tab = bar+col
            print("{0:>5}".format(tab), end='')
        print()

dan di bawah ini adalah outputnya :

![img](gambar/outputl3l1.PNG)

# LAB 3 LATIHAN 2

## SOAL

![img](gambar/tugas4.PNG)

untuk mengerjakan bisa menggunakan syntax di bawah ini :

    import random
    print(40*"=")
    print("Bilangan acak yang lebih kecil dari 0,5")
    print(40*"=")
    jum = int( input("Masukan nilai n : "))
    i = 0
    for i in range(jum):
        i += 1
        angkaDec = random.uniform(0, 0.5)
        print("Data ke", i, " = ", angkaDec)

dan di bawah ini adalah outputnya :

![img](gambar/outputl3l2.PNG)

