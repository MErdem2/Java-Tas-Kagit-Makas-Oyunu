package taşkağıtmakasoyunu;
import java.util.Random;
import java.util.Scanner;

public class TAŞKAĞITMAKASOYUNU {
    public static void main(String[] args) {
        Scanner giris = new Scanner(System.in);
        
        int pc = (int) (Math.random() * 3);
               
        System.out.println("***** ***** ***** ***** *****");
        System.out.println("LÜTFEN SEÇİMİNİZİ YAPINIZ");
        System.out.println("  (0)  TAŞ");
        System.out.println("  (1)  KAĞIT");
        System.out.println("  (2)  MAKAS");
        System.out.println("***** ***** ***** ***** *****");
        
        int oyuncu;
        oyuncu = giris.nextInt();
        
        if (oyuncu > 2)
            System.out.println("HATALI SEÇİM YAPTINIZ, LÜTFEN TEKRAR DENEYİNİZ");
        else if (oyuncu == 0 && pc == 0)
            System.out.println("BİLGİSAYARDA TAŞ SEÇTİ, BERABERE!!");
        else if (oyuncu == 0 && pc == 1)
            System.out.println("BİLGİSAYAR KAĞIT SEÇTİ, KAYBETTİNİZ!!");
        else if (oyuncu == 0 && pc == 2)
            System.out.println("BİLGİSAYAR MAKAS SEÇTİ, KAZANDINIZ!!");
        else if (oyuncu == 1 && pc == 0)
            System.out.println("BİLGİSAYAR TAŞ SEÇTİ, KAZANDINIZ!!");
        else if (oyuncu == 1 && pc == 1)
            System.out.println("BİLGİSAYARDA KAĞIT SEÇTİ, BERABERE!!");
        else if (oyuncu == 1 && pc == 2)
            System.out.println("BİLGİSAYAR MAKAS SEÇTİ, KAYBETTİNİZ!!");
        else if (oyuncu == 2 && pc == 0)
            System.out.println("BİLGİSAYAR TAŞ SEÇTİ, KAYBETTİNİZ!!");
        else if (oyuncu == 2 && pc == 1)
            System.out.println("BİLGİSAYAR KAĞIT SEÇTİ, KAZANDINIZ!!");
        else if (oyuncu == 2 && pc == 2)
            System.out.println("BİLGİSAYARDA MAKAS SEÇTİ, BERABERE!!");
        
    }
    
}
