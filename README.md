# vucut-kitle-indeksi
import java.util.Scanner;

public class Main {
    public static void main (String []args){

    Scanner inp= new Scanner(System.in);
    double height, weight, bmi;
        System.out.print("Kilonunuzu giriniz: ");
        weight= inp.nextDouble();
        System.out.println("Boyunuzu giriniz: ");
        weight= inp.nextDouble();
        bmi= weight/ (height*height);
        System.out.println("Vücut kitle indeksi: "+bmi);
        
    }

}
