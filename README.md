public class Main {
    public static void main(String[] args) {

        int a = 10;
        int b = 3;

        Arithmetic operations
        System.out.println("Addition: " + (a + b));
        System.out.println("Subtraction: " + (a - b));
        System.out.println("Multiplication: " + (a * b));
        System.out.println("Division: " + (a / b));
        System.out.println("Modulus: " + (a % b));

        Increment & Decrement
        a++;
        b--;

        // Assignment operator
        a += 5;

        Comparison operators
        System.out.println("Is a equal to b? " + (a == b));
        System.out.println("Is a greater than b? " + (a > b));

        Logical operators
        boolean isAdult = true;
        boolean hasLicense = false;

        System.out.println("Adult AND has license: " + (isAdult && hasLicense));
        System.out.println("Adult OR has license: " + (isAdult || hasLicense));
        System.out.println("NOT has license: " + (!hasLicense));
    }
}
