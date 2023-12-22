# -Мой проект полезен тем что можно быстро вычеслить Факториал
(пожалуйста поставьте хорошую оценку)

using System;
 
class Program
{
    static void Main(string[] args)
    {
        Console.Write("n: ");
        int n = int.Parse(Console.ReadLine());
        long result = 1;
        for (int i = 1; i <= n; i++)
            result *= i;
        Console.WriteLine("f: " + result);
        Console.ReadKey(true);
    }
}
