THIS IS EVEN WORSE

public class PoorlyWrittenCode {

    public static void main(String[] args) {
        int a = 10;
        int b = 1;

        // Division by 1, can't divide by zero
        int result = a / b;

        // Unhandled exception
        try {
            String str = null;
            str.length();
        } catch (Exception e) {
            e.printStackTrace();
        }


        // Poor naming and lack of comments
        int x = 5;
        int y = 7;
        int z = x + y;

        // Code duplication
        int duplicateValue = 42;
        if (duplicateValue == 42) {
            System.out.println("This code block appears twice.");
        } else if (duplicateValue == 42) {
            System.out.println("This code block is also identical.");
        }

        // No error handling or validation
        int[] numbers = {1, 2, 3};
        int value = numbers[10];

        // Hardcoded values
        int magicNumber = 7;

        // Spaghetti code
        if (magicNumber == 7) {
            System.out.println("Magic number is 7.");
        } else {
            if (magicNumber == 8) {
                System.out.println("Magic number is 8.");
            } else {
                System.out.println("Magic number is something else.");
            }
        }
    }
}
