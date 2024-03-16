    using System;

    namespace Calculadora
    {
        class Program
        {
        static void Main(string[] args) 
        {
            Menu();
        }
        static void Soma()
        {
            Console.Clear();

            Console.WriteLine("Primeiro valor:");
            float v1 = float.Parse(Console.ReadLine());

            Console.WriteLine("Segundo valor:");
            float v2 = float.Parse(Console.ReadLine());

            float res = v1+v2;
            Console.WriteLine("O resultado da soma é " + res);
            Console.ReadKey();
            Menu();
        }
        static void Subtracao()
        {
            Console.Clear();

            Console.WriteLine("Primeiro valor:");
            float v1 = float.Parse(Console.ReadLine());

            Console.WriteLine("Segundo valor:");
            float v2 = float.Parse(Console.ReadLine());

            float res = v1-v2;
            Console.WriteLine("O resultado da subtração é " + res);
            Console.ReadKey();
            Menu();
        }
        static void Divisao()
        {
            Console.Clear();

            Console.WriteLine("Primeiro valor:");
            float v1 = float.Parse(Console.ReadLine());

            Console.WriteLine("Segundo valor:");
            float v2 = float.Parse(Console.ReadLine());

            float res = v1/v2;
            Console.WriteLine("O resultado da Divisão é " + res);
            Console.ReadKey();
            Menu();
        }
        static void Multiplicacao()
        {
            Console.Clear();

            Console.WriteLine("Primeiro valor:");
            float v1 = float.Parse(Console.ReadLine()); 

            Console.WriteLine("Segundo valor:");
            float v2 = float.Parse(Console.ReadLine());

            float res = v1*v2; 
            Console.WriteLine("O resultado da Multiplicação é " + res); 
            Console.ReadKey(); 
            Menu();
        }
        static void Menu()
            {
            Console.Clear();
            Console.WriteLine("O Que Deseja Fazer?");
            Console.WriteLine("1 - Soma");
            Console.WriteLine("2 - Subtração");
            Console.WriteLine("3 - Divisão");
            Console.WriteLine("4 - Multiplicação");
            Console.WriteLine("5 - Exit");

            Console.WriteLine("-------------");

            Console.WriteLine("Selecione uma opção:");
            short res = short.Parse(Console.ReadLine());
            switch (res)
            {
            case 1:  Soma(); break;
            case 2:  Subtracao(); break;
            case 3:  Divisao(); break;
            case 4:  Multiplicacao(); break;
            default : System.Environment.Exit(0); break;
            }
            }
        }
    }
