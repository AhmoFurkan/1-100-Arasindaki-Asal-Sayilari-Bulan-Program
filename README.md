# 1-100-Arasindaki-Asal-Sayilari-Bulan-Program
Java ile 1 - 100 arasındaki asal sayıları ekrana yazdıran programı yazınız.

        import java.util.Scanner;

        public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);

        for (int i = 1; i <= 100; i++) {
            if (i == 2 || i == 3 || i == 5 || i == 7) {
                System.out.println(i);
            }
            if (i % 2 == 0 || i % 3 == 0 || i % 5 == 0 || i % 7 == 0) {
            } else {
                System.out.println(i);
            }

        }


     }
    }


https://app.patika.dev/ahmetfurkan
![image](https://user-images.githubusercontent.com/107626332/182777799-2c54c709-a637-4643-92c9-325160e7667d.png)
