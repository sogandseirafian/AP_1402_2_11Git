# AP_1402_2_11Git
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace AP_1402_2_13.CS
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("please enter 2 digit number:");
            int num = Convert.ToInt32(Console.ReadLine());
            int sum= 0;
            while(num>0)
            {
                int sdigit;
                sdigit = num % 10;
                sum = sum * 10 + sdigit;
                num /= 10;
            }
            Console.WriteLine("num is:" + sum);

        }
    }
}
