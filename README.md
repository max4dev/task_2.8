# task_2.8

public class Main {

    public static void main(String[] args) {

        int numbers [] = {2, 3, 4, 5};
        int sumProducts = 0;

        for (int i = 0; i < numbers.length-1; i++) {
            sumProducts += numbers [i]*numbers[i+1];
        }
        System.out.println(sumProducts);
    }
}
