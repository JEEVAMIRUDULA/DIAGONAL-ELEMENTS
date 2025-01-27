# DIAGONAL-ELEMENTS
package digonalelements;
public class DigonalElements {
    public static void main(String[] args) {
        // TODO code application logic here
        int[][] squareMatrix = {
            {1, 2, 3},
            {4, 5, 6},
            {7, 8, 9}
        };

        System.out.println("Diagonal elements:");
        for (int i = 0; i < squareMatrix.length; i++) {
            System.out.print(squareMatrix[i][i] + " ");
        }
        System.out.println();
    }
}


O/P
Diagonal elements:
1 5 9 

