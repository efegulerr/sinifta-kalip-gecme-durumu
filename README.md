# sinifta-kalip-gecme-durumu
patika.dev sınıfta kalıp geçme durumu / geçer not 55 ve üzeri

import java.util.Scanner;
public class main {
    public static void main(String[] args){
        int matematik, fizik, turkce, kimya, muzik;
    Scanner inp = new Scanner(System.in);
    System.out.println("Matematik notunuzu giriniz:");
    matematik = inp.nextInt();
    System.out.println("fizik notunuzu giriniz:");
    fizik = inp.nextInt();
    System.out.println("Türkçe notunuzu giriniz:");
    turkce = inp.nextInt();
    System.out.println("Kimya notunuzu giriniz:");
    kimya = inp.nextInt();
    System.out.println("Müzik notunuzu giriniz:");
    muzik = inp.nextInt();
    double avarage = (matematik + fizik + turkce + kimya + muzik) / 5 ;
    if (avarage >= 55){
        System.out.println("Tebrikler sınıfı geçtiniz!");
    } else {
        System.out.println("Sınıfı geçemediniz..");
    }
    System.out.println("Ortalamanız:" + avarage);

    }
    
}
