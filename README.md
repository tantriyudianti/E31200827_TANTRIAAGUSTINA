# E31200827_TANTRIAAGUSTINA
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author MASTER
 */    
// Import component java.io
import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
public class luasSegitiga2 {



/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author CodeVector-PC
 */

    public static void main(String[] args) throws IOException{
        // Inialisasi variable alas, tinggi dan luas
        double alas, tinggi, luas;
        
        // Inialisasi BufferedReader dengan menggunakan alias Input 
        BufferedReader input = new BufferedReader(new InputStreamReader(System.in));
        
        // Memberitahukan user untuk memasukkan inputan Alas
        System.out.println("Masukkan nilai Alas :");
        
        // Mengambil inputan alas dari user dan disimpan divariable alas 
        // lalu di parsing/convert ke tipe data double
        alas = Double.parseDouble(input.readLine());
        
        // Memberitahukan user untuk memasukkan inputan Tinggi
        System.out.println("Masukkan nilai Tinggi :");
        
        // Mengambil inputan alas dari user dan disimpan divariable tinggi 
        // lalu di parsing/convert ke tipe data double
        tinggi = Double.parseDouble(input.readLine());
        
        // Melakukan operasi aritmatika menghitung luas segitiga
        // disimpan di variable luas
        luas = (alas * tinggi) / 2;
        
        // Menampilkan hasil output dari luas segitiga
        System.out.println("Luas Segitiga adalah : " + luas);        
        
        
        System.out.println("________________________________");
        System.out.println("Nama: Tantria Agustina Yudianti");
        System.out.println("NIM: E31200827");
        System.out.println("Prodi: Manajemin Informatika");
        System.out.println("________________________________");
    }
}

TUGAS NOMER 2
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author MASTER
 */ /*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package mengecekbilanganganjilgenap_scanner;

import java.util.Scanner;

/**
 *
 * @author CodeVector-PC
 */
public class BilanganGenapdanGanjil {
   

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // Inisialisasi Scanner menggunakan alias input
        Scanner input = new Scanner(System.in);
        
        // Deklarasi variable bilangan
        int bilangan;

        // Memberitahukan user untuk memasukkan sebuah bilangan
        System.out.println("Masukkan sebuah bilangan : ");
        
        // Mengambil inputan dari user
        bilangan = input.nextInt();
        
        // Melakukan pengecekan bilagan genap apa bilangan ganjil
        // lalu menampilkannya
        if(bilangan % 2 == 0)
        {            
            System.out.println("Bilangan " + bilangan + " adalah genap");
        }else{
            System.out.println("Bilangan " + bilangan + " adalah ganjil");
        }
        
    }
    
}

    

