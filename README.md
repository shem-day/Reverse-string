# Reverse-string
How to revise a string
using System;

namespace How_to_reverse_a_string
{
    class Program
    {
  internal static void ReverseString (string str)
        {
            char[] charArray = str.ToCharArray();
            for (int i = 0, j = str.Length - 1; i < j; i++, j--) ;
            { charArray[i] = str[j];
                charArray[j] = str[i];
            }
            string reversedstring = new string(charArray);
            Console.WriteLine(reversedstring);
        }
    }
}
