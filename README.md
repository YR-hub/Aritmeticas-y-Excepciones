public class ArrayIndexOutOfBoundsExceptionExample {
    public static void main(String[] args) {
        int[] array = { 1, 2, 3, 4, 5, 6 };

        try {
            int element = array[8];
            System.out.println("Elemento: " + element);
        } catch (ArrayIndexOutOfBoundsException e) {
            System.out.println("Error: Índice fuera de rango del array.");
        }
    }
}
