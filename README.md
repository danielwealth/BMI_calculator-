# BMI_calculator-
import java.util.Scanner;
public class Main {
    
    public static void main(String[] args) {
        Scanner scanner= new Scanner(System.in);
        System.out.println("Enter your weight in kg");
        double weight=scanner.nextDouble();
        System.out.println("Enter your height in meters");
        double height=scanner.nextDouble();
        double heights= height*height;
        double bmi=weight/heights;
        if(bmi< 18.5){
            System.out.println("you are underweight");}
        if(bmi==18.5 && bmi<=24.9){
            System.out.println("you have nomal weight");}
        if(bmi==25 && bmi<=29.9){
            System.out.println("your are over weight");}
        if(bmi>29.9){
            System.out.println("you are obese!");
    }}}
