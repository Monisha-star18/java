import java.util.Scanner;

public class ContiguousMemoryAllocation {

public static void main(String[] args) { Scanner scanner = new Scanner(System.in);

// Input the size of the array System.out.print("Enter the size of the array: "); int size = scanner.nextInt();

// Declare an array of integers int[] arr = new int[size];

// Input elements into the array System.out.println("Enter elements of the array:"); for (int i = 0; i < size; ++i) { System.out.print("Enter element " + (i + 1) + ": "); arr[i] = scanner.nextInt(); }

// Display elements of the array System.out.println("Elements of the array are:"); for (int i = 0; i < size; ++i) { System.out.print(arr[i] + " ");
}
System.out.println();
// Close the scanner scanner.close();
}
}
