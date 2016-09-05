using System;

class ReadFromCommandLine
    {
        static void Main()
        {
            //Дефиниране на променливи
            int a = 0, b = 0;

            //Въвеждане на входни параметри
            Console.Write( "Моля въведете а: " );
            b = Convert.ToInt32 (Console.ReadLine());

            //Печат на резултат
            Console.WriteLine("Резултатът на a + b е: " + (a + b) .ToString () + "\n\n\n");
        }
    }