# MVC
Sebuah App pemesanan makanan yang simple tetapi memenuhi standar Single Responsibility.

# Tujuan
Kita bisa menambahkan sebuah item makanan yang diinginkan oleh si pembeli
Untuk mempermudah ketika ada yang ingin membeli makanan dan tidak perlu menghitung

## Tentang program
ketika kita ingin mengubah sebuah menu yang ingin kita jual kita tinggal mengganti nama di bagian penawaran.xaml.cs

```

private void generateContentPenawaran()
        {
            Item drink1 = new Item("Ice tea", 8000);
            Item drink2 = new Item("Ice lemon tea", 5000);
            Item drink3 = new Item("Ice lemon", 7000);
            Item food4 = new Item("Kebab", 5000);
            Item food5 = new Item("Gado-gado", 14000);
            Item food6 = new Item("Sate", 15000);

            controller.addItem(drink1);
            controller.addItem(drink2);
            controller.addItem(drink3);
            controller.addItem(food4);
            controller.addItem(food5);
            controller.addItem(food6);

            listPenawaran.Items.Refresh();
        }


```
*MUHAMMAD RIZKO MUNZAL
*19.11.2847
*19-IF-04
