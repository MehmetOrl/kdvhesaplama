


```java import java.util.Scanner;

public class kdvhesapla {
    public static void main(String[] args) {
        Scanner Input =new Scanner(System.in);


        Scanner input = new Scanner(System.in);
        double ucret,kdv=0.18,kdv2=0.08,kdvTutar,kdvFiyat;
        System.out.print("Ücret tutarını giriniz: ");
        ucret = input.nextDouble();
        kdvTutar=ucret<1000? ucret*kdv:ucret*kdv2;
        kdvFiyat=kdvTutar+ucret;
        System.out.println("Kdv Tutari.:"+kdvTutar);
        System.out.println("Kdv Fiyati.:"+kdvFiyat);
        