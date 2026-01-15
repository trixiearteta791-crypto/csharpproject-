using System;

class Program
{
    static void Main(string[] args)
    {
        char continueChoice = 'Y';

        // Requirement 4: While loop to repeat program until user presses "N"
        while (continueChoice == 'Y' || continueChoice == 'y')
        {
            // Requirement 1: Menu-driven interface
            Console.WriteLine("Press any following key to perform an arithmetic operation:");
            Console.WriteLine("1 - Addition");
            Console.WriteLine("2 - Subtraction");
            Console.WriteLine("3 - Multiplication");
            Console.WriteLine("4 - Division");

            // Input Handling for choice
            string inputChoice = Console.ReadLine();

            // Requirement: Accept two numerical values
            Console.Write("Enter Value 1: ");
            double val1 = Convert.ToDouble(Console.ReadLine());
            Console.Write("Enter Value 2: ");
            double val2 = Convert.ToDouble(Console.ReadLine());

            // Requirement 3: Switch-case structure
            switch (inputChoice)
            {
                case "1":
                    // Requirement: Exact Output Format (A op B = C)
                    Console.WriteLine($"{val1} + {val2} = {Add(val1, val2)}");
                    break;
                case "2":
                    Console.WriteLine($"{val1} - {val2} = {Subtract(val1, val2)}");
                    break;
                case "3":
                    Console.WriteLine($"{val1} * {val2} = {Multiply(val1, val2)}");
                    break;
                case "4":
                    if (val2 != 0)
                        Console.WriteLine($"{val1} / {val2} = {Divide(val1, val2)}");
                    else
                        Console.WriteLine("Error: Division by zero is not allowed.");
                    break;
                default:
                    Console.WriteLine("Invalid selection.");
                    break;
            }

            // Requirement: Continue/Exit Loop Control
            Console.Write("Do you want to continue again (Y/N)? ");
            continueChoice = Console.ReadKey().KeyChar;
            Console.WriteLine("\n"); // Move to next line for better spacing
        }
    }

    // Requirement 2: Separate methods for each operation
    static double Add(double a, double b) => a + b;
    static double Subtract(double a, double b) => a - b;
    static double Multiply(double a, double b) => a * b;
    static double Divide(double a, double b) => a / b;
}
