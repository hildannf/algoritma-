import java.util.Scanner;

public class telur {

    public static void main(String[] args) {
         Scanner inputan = new Scanner(System.in);
         System.out.print("Masukan (kg)telur yang dibeli: ");
         Double KiloTelur = inputan.nextDouble();

         System.out.print("Masukan uang bayar: ");
         Double uangBayar = inputan.nextDouble();

         Double HargaTelur = KiloTelur * 28000; 
         Double Kembalian = uangBayar - HargaTelur;

         System.out.printf("uang kembalian : %.2f" ,Kembalian);
         inputan.close();
    }
}


import java.util.Scanner;

public class Perhitungan {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);


        // Konversi Celcius ke Fahrenheit
        System.out.print("Masukkan suhu dalam Celcius: ");
        double celcius = input.nextDouble();
        double fahrenheit = (celcius * 9/5) + 32;
        System.out.println("Suhu dalam Fahrenheit: " + fahrenheit);


        // Menghitung Keliling Lingkaran
        System.out.print("Masukkan jari-jari lingkaran: ");
        double jariJari = input.nextDouble();
        double kelilingLingkaran = 2 * Math.PI * jariJari;
        System.out.println("Keliling lingkaran: " + kelilingLingkaran);

        // Menghitung Luas Persegi Panjang
        System.out.print("Masukkan panjang persegi panjang: ");
        double panjang = input.nextDouble();
        System.out.print("Masukkan lebar persegi panjang: ");
        double lebar = input.nextDouble();

        double luasPersegiPanjang = panjang * lebar;
        System.out.println("Luas persegi panjang: " + luasPersegiPanjang);


        // Menghitung Volume Kubus
        System.out.print("Masukkan sisi kubus: ");
        double sisi = input.nextDouble();
        double volumeKubus = sisi * sisi * sisi;
        System.out.println("Volume kubus: " + volumeKubus);

        input.close();
    }
} 
