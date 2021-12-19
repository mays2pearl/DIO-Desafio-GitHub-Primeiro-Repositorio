# Desafio 1 

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Xenlongao
{
    internal class Program
    {
        static void Main(string[] args)
        {
        
            var testes = int.Parse(Console.ReadLine());

            for (int i = 0; i < testes; i++)
            {
                var esferas = int.Parse(Console.ReadLine());

                Console.WriteLine(esferas - Math.Floor(Math.Sqrt(esferas)));
            }


        }
    }
}
    
