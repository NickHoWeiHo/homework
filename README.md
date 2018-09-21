import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        //01
        Scanner scn =new Scanner(System.in);
        int v1=scn.nextInt();
        System.out.println(v1*9/5+32);
        //02
        Scanner scn =new Scanner(System.in);
        int v1=scn.nextInt();
        int v2=scn.nextInt();
        System.out.println(v1+v2);
        System.out.println(v1-v2);
        System.out.println(v1*v2);
        //03
        Scanner scn =new Scanner(System.in);
        int v1=scn.nextInt();
        int v2=scn.nextInt();
        int v3=scn.nextInt();
        System.out.println(v1+v2+v3);
        System.out.println((v1+v2+v3)/3);
        //04
        Scanner scn =new Scanner(System.in);
        int v1=scn.nextInt();
        int v2=scn.nextInt();
        System.out.println(v1/2.54);
        System.out.println(v2/0.454);
        //05
        Scanner scn =new Scanner(System.in);
        int v1=scn.nextInt();
        int v2=scn.nextInt();
        int v3=scn.nextInt();
        if(v1<v2&&v2<v3){
            System.out.println("True");
        }
        else {
            System.out.println("False");
        }
        //06
        Scanner scn =new Scanner(System.in);
        int v1=scn.nextInt();
        int v2=scn.nextInt();
        int v3=scn.nextInt();
        if(v1%4==0){
            System.out.println("True");
        }
        else{
            System.out.println("False");
        }
        if(v2%4==0){
            System.out.println("True");
        }
        else{
            System.out.println("False");
        }
        if(v3%4==0){
            System.out.println("True");
        }
        else{
            System.out.println("False");
        }
    }
}
