using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Generics1
{
    class Program
    {
        static void Main(string[] args)
        {
            List<string> myList = new List<string>();
            myList.Add("1.siva");
            myList.Add("2.Kiran");
            myList.Add("3.Ashok");
            myList.Add("4.narendra");
            foreach (string s in myList)
                Console.Write(s.ToString() + " ");
            myList.Sort();
            Console.WriteLine("\n After sorting");
            foreach (string s in myList)
                Console.Write(s.ToString() + " ");
            myList.Remove("narendra");
            Console.WriteLine("\n Removing of narendra");
            foreach (string s in myList)
                Console.WriteLine(s.ToString() + " ");
            myList.Insert(2, "Thulasi");
            Console.WriteLine("\n Inserting of Thulasi at index position 2");
            foreach (string s in myList)
                Console.Write(s.ToString() + " ");
        }
    }
}
