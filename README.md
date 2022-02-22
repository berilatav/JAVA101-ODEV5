Daire Alanı Hesaplama

Yarıçapı r, merkez açısının ölçüsü 𝛼 olan daire diliminin alanı bulan programı yazınız.

𝜋 sayısını = 3.14 alınız.
Alan = (𝜋 * (r*r) * 𝛼) / 360

import java.util.Scanner;
public class Odev5 {

    public static void main(String[] args) {

        int r,a ;
        double pi = 3.14;


        Scanner input = new Scanner (System.in);
        System.out.println("Dairenin yarıçapını giriniz: ");
        r = input.nextInt();

        System.out.println("Dairenin merkez açısını giriniz: ");
        a = input.nextInt();

        double alan =( pi * (r*r) * a) / 360;
        System.out.println("Dairenin alanı :" + alan);


    }
}
