import java.util.Scanner;

public class Main {
    public static void main(String[] args)
    {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Podaj swóją temperaturę: ");

        float temperatura = scanner.nextFloat();


         if (temperatura <= 35){
             System.out.println("Twoja temperatura to: " + temperatura + "°C");
             System.out.println("HIPOTERMIA");
         }
        else if (temperatura >= 35 && temperatura <= 36) {
             System.out.println("Twoja temperatura to: " + temperatura + "°C");
             System.out.println("Temperatura jest niższa od normy");
         }

        else if ( temperatura >= 36 && temperatura <= 37 ) {
             System.out.println("Twoja temperatura to: " + temperatura + "°C");
             System.out.println("Temperatura w normie");
         }
        else if ( temperatura >= 37 && temperatura <= 38) {
             System.out.println("Twoja temperatura to: " + temperatura + "°C");
             System.out.println("Stan podgorączkowy");
         }
        else if ( temperatura >= 38 && temperatura <= 39){
             System.out.println("Twoja temperatura to: " + temperatura + "°C");
             System.out.println("Gorączka");
         }


        else if ( temperatura >= 39){
             System.out.println("Twoja temperatura to: " + temperatura + "°C");
             System.out.println("Wysoka gorączka");
         }


    }
}
