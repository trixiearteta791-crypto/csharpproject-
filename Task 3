using System;

class Task3
{
    static void Main()
    {
        // 1. Declare and initialize the array
        int[] numbers = { 3, 7, 12, 19, 21, 25, 30 };

        // 2. Ask the user for input
        Console.Write("Enter a number to search for: ");
        int target = Convert.ToInt32(Console.ReadLine());

        // Boolean flag to track if the number was found
        bool found = false;

        // 3. Use a for loop to go through the array elements
        for (int i = 0; i < numbers.Length; i++)
        {
            // 4. Compare user input to each element
            if (numbers[i] == target)
            {
                Console.WriteLine($"Number found at position {i}!");
                found = true;
                
                // 5. Use the break statement to stop immediately
                break;
            }
        }

        // 6. If the loop completes with no match
        if (!found)
        {
            Console.WriteLine("Number not found in the list.");
        }
    }
}
