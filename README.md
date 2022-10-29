# katlar

import java.util.Scanner;

public class Ciftve4Kati {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        do {
            System.out.print("sayı giriniz: ");
            f = sc.nextInt();
            if (f % 2 == 1){
                break;
            }else if(f % 4 == 0){
                sum += f;
            }
        } while (f > 0);

        System.out.print("4'ün katları olan sayıların toplamı = " + sum);
    }
}
