using System;

public class Task2
{
    public static void Main(string[] args)
    {
        // 1. Declare and Initialize the 2D array (Jagged Array)
        // Row 0: Even numbers
        // Row 1: Odd numbers
        int[][] numberMatrix = new int[][]
        {
            new int[] { 2, 4, 6, 8, 10 },
            new int[] { 1, 3, 5, 7, 9 }
        };

        Console.WriteLine("The number matrix has been initialized.");
        Console.WriteLine(); // Add a blank line for readability

        // 3. The puzzle requires you to extract three specific digits
        // based on "The Puzzle Clues."

        // The Puzzle Clues:
        // - Digit 1: The number at Row 1, Index 3.
        // - Digit 2: The number at Row 0, Index 0.
        // - Digit 3: The number at Row 1, Index 4.

        // 4. Extract the Digits:
        // Digit 1 Extraction: Row 1, Index 3 -> Value 7
        int digit1 = numberMatrix[1][3];

        // Digit 2 Extraction: Row 0, Index 0 -> Value 2
        int digit2 = numberMatrix[0][0];

        // Digit 3 Extraction: Row 1, Index 4 -> Value 9
        int digit3 = numberMatrix[1][4];

        // Output the extracted digits (Optional, but good for verification)
        Console.WriteLine($"Extracted Digits: {digit1}, {digit2}, {digit3}");
        
        // 5. Combine the Digits (The Key):
        // Convert the three digits into a single string.
        string passwordKey = digit1.ToString() + digit2.ToString() + digit3.ToString();

        // 6. Final Output:
        Console.WriteLine();
        Console.WriteLine($"The final 3-digit key was printed to the console as the \"password\" or key.");
        Console.WriteLine($"Password: **{passwordKey}**");

    }
}
