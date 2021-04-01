import java.util.Scanner;
class TriangleCalc {
  public static void main(String[] args){
     Scanner scan = new Scanner(System.in);
     double a, b, c, V, S;
     System.out.print("Enter a: ");
     a = scan.nextDouble();
     System.out.print("Enter b: ");
     b = scan.nextDouble();
     System.out.print("Enter c: ");
     c = scan.nextDouble();
    if (a <= 0 || b <= 0 || c <= 0 ){
       System.out.println("Invalid triangle!");
       return;
     }
     
     S = a * b * c;
     S = 2*(a*c + b*c);
     System.out.printf("V = %.2f\n", V);
     System.out.printf("S = %.2f\n", S);
  }
}
