public class StringToNumber {
    public static void main(String[] args) {
        // Example string representations of numbers
        String intString = "123";
        String doubleString = "3.14";

        // Converting string to integer
        int intValue = Integer.parseInt(intString);
        System.out.println("String \"" + intString + "\" as integer: " + intValue);

        // Converting string to double
        double doubleValue = Double.parseDouble(doubleString);
        System.out.println("String \"" + doubleString + "\" as double: " + doubleValue);
    }
}
