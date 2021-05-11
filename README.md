
//converting user given number of minutes to years and no. of days
import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        System.out.println("enter no. of minutes :)");
        Scanner sc = new Scanner(System.in);
        int min = sc.nextInt();
        int hr = min/60;
        int day = hr/24;
        int yr = day/365;
        int days = day%365;
        System.out.print(min+" minutes is approximately "+yr);
        System.out.print(" years ");
        System.out.print(days+"days..");
    }
}
