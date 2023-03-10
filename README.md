# tugas-algoritma
import javax.security.auth.x500.X500Principal;

public class latihan {
    public static void main(String[] args) {
        System.out.println();
        System.out.println("Nomer 1");
        for (int i = 1; i <=11;i+=2) {

            System.out.print(i+" ");
        } 

        System.out.println();
        System.out.println("Nomer 2");
        for (int i=20; i>=0; i-=5) {
            System.out.print(i+" ");
        }

        System.out.println();
        System.out.println("Nomer 3");
        int a = 0;
        int b = 1;
        int c = 0;
        System.out.print(a+" "+b+" ");
        for (int i=2; i<8; i++) {
            c = a + b;
            a = b;
            b = c;
            System.out.print(c+" ");
        }
    }
}
