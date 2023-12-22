# -Мой проект полезен тем что можно быстро вычеслить Факториал
(пожалуйста поставьте хорошую оценку)

using System;

namespace FactorialCalculator
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Введите число: ");
            int number = Convert.ToInt32(Console.ReadLine());
            int result = CalculateFactorial(number);
            Console.WriteLine($"Факториал числа {number} равен {result}");
        }

        static int CalculateFactorial(int n)
        {
            if (n == 0)
                return 1;
            else
                return n * CalculateFactorial(n - 1);
        }
    }
}
