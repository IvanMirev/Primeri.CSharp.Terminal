using System;


class Strings
    {
        static void Main()
        {
            string test = "1";
            test = "2";
            test = "777";
            test = "4";
            test = "5";
            test = "6";

            Console.WriteLine("Събиране с += " + test + "\n");

            test = test.Replace(",",";");
            Console.WriteLine("Работа с Replace" +test+ "\n");

            //Намиране на 3-то число с масив
            Console.WriteLine("3-ти знак" + test.Split (';') [2]);
        }
    }

