# Do-while 
sing System.IO;
using System.Linq;
using System.Collections.Generic;

namespace CSharp_Shell
{

    public class Program 
    {
        public static void Main()
        {  
        	int i=1,a;
        	Console.WriteLine("Enter Number");
			a= Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("The table of given number is:- ");
			do 
			{
				
					Console.WriteLine(a*i);
				 i++;  
				}
				 while(i<=10);
					
				}
        	
			
        }
    }
Output:-
Enter Number
2
The table of given number is:- 
2
4
6
8
10
12
14
16
18
20
