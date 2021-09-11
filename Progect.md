using System;

using System.Collections.Generic;

using System.Linq;

using System.Text;

using cod;

namespace cod

{

   /* void  Student{



}*/

    class Program

    {

     



        static void Main(string[] args)

        {

        

       

        /* Student student=new Student(Convert.ToInt16(Console.ReadLine()),Convert.ToInt16(Console.ReadLine()),Convert.ToInt16(Console.ReadLine()),

           Convert.ToInt16(Console.ReadLine()),Convert.ToInt16(Console.ReadLine()),Convert.ToString( Console.ReadLine()),Convert.ToString(Console.ReadLine()),

         Convert.ToString( Console.ReadLine() ));*/

            

       Student student=new Student(1,1,1,1,1,"1","1","1");

		Teacher teacher=new Teacher(1,1,1,1,"1","1","1");

		teacher.Course_students=student;

		teacher.Get_Course_students();

          /* age = Convert.ToInt16(Console.ReadLine());

            Console.WriteLine(age*age);*/

        }





    }

}
