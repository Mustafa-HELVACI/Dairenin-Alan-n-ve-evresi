# Dairenin-Alani-ve-cevresi
Yarıçapı r, merkez açısının ölçüsü 𝛼 olan daire diliminin alanı bulma.


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int r;
        double pi = 3.14, a, alan;

        Scanner input = new Scanner(System.in);
        System.out.print("Yarıçap Uzunluğunu Girin :");
        r = input.nextInt();
        System.out.print("Merkez Açısının Ölçüsünü Girin :");
        a = input.nextDouble();

        alan = (pi * (r * r) * a)/360 ;
        System.out.print("Daire Diliminin Alanı :" + alan);




       /*int r;
       double pi = 3.14;

       Scanner inp = new Scanner(System.in);

        System.out.print("Dairenin yarı çapını girin :");
        r = inp.nextInt();

        double alan = pi * r * r;
        double cevre = 2* pi * r;

        System.out.println("Dairenin Alanı :" + alan);
        System.out.println("Dairenin Çevresi ." + cevre);

        */

    }
}
