// Java-program-to-print-tree-pattern
public class tree {

    public static void main(String args[]) {
        int a, b, c;
        for (a = 0; a <= 10; a++) {
            for (b = 10; b >= a; b--) {
                System.out.print(" ");
            }
            for (b = 1; b <= a; b++) {
                System.out.print("* ");
            }
            System.out.println();
        }

        //stem
        for (a = 1; a <= 7; a++) {
            for (c = 1; c <= 6; c++) {
                System.out.print(" ");
            }
            for (b = 1; b <= 8; b++) {
                System.out.print("|");
            }
            System.out.println();

        }
        //base
        for (a = 1; a <= 3; a++) {

            for (b = 1; b <= 20; b++) {
                System.out.print("|");
            }
            System.out.print("\n");

        }
    }
}
