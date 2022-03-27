# Yildizlar-Ile-Elmas
Patika.dev > Java101 > Döngüler > Pratik8 - Yıldızlar İle Elmas

### Ödev
Java'da döngüler kullanarak yıldızlar ile elmas yapınız.


      import java.util.*;

      public class yildizlar_ile_elmas {

        public static void main(String[] args) {

              Scanner sc = new Scanner(System.in);

              System.out.print("Enter a number: ");
              int n = sc.nextInt();

              for (int i=0; i<=n; i++) {
                for (int j=0; j<(n-i); j++) 
                  System.out.print(" ");

                  for (int k=1; k<=(2 * i + 1); k++) 
                    System.out.print("*");

                  System.out.println(" ");
              }

              for (int i=0; i<=n; i++) {
                  for(int j=0; j<(i+1); j++)
                    System.out.print(" ");

                  for (int k=1; k<2*(n-i); k++) 
                    System.out.print("*");
                  System.out.println(" ");
              }
          }
      }
