import java.util.Scanner;
public class Main {
    public static void main (String[]args){
        System.out.println("Введите n");
        Scanner scan = new Scanner(System.in);
        double n = scan.nextDouble();
        System.out.println("Введите x");
        double x = scan.nextDouble();
        if (x>1)
        {
            double res = 0;
            for(double i=0;i<=n;i++){
                res+=Math.pow(-1,i+1)/((2*i+1)*Math.pow(x,2*i+1));
            }
            System.out.println((Math.PI/2)+res);
        }
        else {
            System.out.println("Ошибка!");
        }
    }
}
