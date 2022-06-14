# Assignment

## Q. Write atleast 10 methods that are implemented in Java with their example(explanation).

1. `equals()` method: This method is used to compare two strings for their equality. Returns true if the strings are equal else returns false.
   
    **:**
   ```java
    class EqualsTesting{
        public static void main(String[] args){
            String s1 = "hello";
            String s2 = "Hello";

            System.out.println(s1.equals(s2)); // Returns false
        }
    }
   ```

2. `concat()` method: This method is used to concatenate two strings together.

    **Example:**
    ```java
    class ConcatTesting{
        public static void main(String[] args){
            String s1 = "Nishant";
            String s2 = "Sapkota";

            System.out.println(s1.concat(s2)); // NishantSapkota
        }
    }
    ```

3. `toUpperCase()` method: This method is used to convert any string to its uppercase form. If string is `nishant` it will be converted to `NISHANT`.

    **Example:**
    ```java
    class UppercaseTesting{
        public static void main(String[] args){
            String name = "Nishant";
            
            System.out.println(name.toUpperCase()); // NISHANT
        }
    }
    ```

4. `toLowerCase()` method: This method is used to convert any string to its lowercase form. If a string is `NISHANT` it will be converted to `nishant`.

    **Example:**
    ```java
    class LowercaseTesting{
        public static void main(String[] args){
            String name="NISHANT";

            System.out.println(name.toLowerCase()); // nishant
        }
    }
    ```

5. `length()` method: This method is used to get the length of the string.
   
   **Example:**
   ```java
    class LengthTesting{
        public static void main(String[] args){
            String name="Nishant";

            System.out.println(name.length()); // 7
        }
    }
   ```

6.  `round()` method: This method is used to round a floating point value to the nearest integer value. If 11.4, it will round to 11. If 11.6, it will round to 12

   **Example:**
   ```java
    class RoundTesting{
        public static void main(String[] args){
            double number1 = 11.4;
            double number2 = 11.6;

            System.out.println(Math.round(number1)); // 11
            System.out.println(Math.round(number2)); // 12
        }
    }
   ```

7. `random()` method: This method is used to generate a random number.

    **Example:**
    ```java
    class RandomTesting{
         public static void main(String[] args){
            System.out.println(Math.random()); // Generates a random number
        }
    }
    ```

8. `isDigit()` method: This method is used to check whether a given character is a digit or not. It returns true if it is a digit else returns false.

    **Example:**
    ```java
    class DigitTesting{
        public static void main(String[] args){
            char x = 'B';
            char y = '1';

            System.out.println(Character.isDigit(x)); // False
            System.out.println(Character.isDigit(y)); // True
        }
    }
    ```

9. `isLetter()` method: This method is used to check whether a given character is a letter or not. It returns true if it is a letter else returns false.
    
    **Example:**
    ```java
    class LetterTesting{
        public static void main(String[] args){
            char x = 'B';
            char y = '1';

            System.out.println(Character.isLetter(x)); // true
            System.out.println(Character.isLetter(y)); // false
        }
    }
    ```

10. `min()` method: This method is used to get minimum values between two numbers.

    **Example:**
    ```java
    class MinTesting{
        public static void main(String[] args){
            int a = 10;
            int b = 20;

            System.out.println(Math.min(a,b)); // 10
        }
    }
    ```