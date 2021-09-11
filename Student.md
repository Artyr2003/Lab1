using System;

using System.Collections.Generic;

using System.Linq;

using System.Text;

using cod;

namespace cod

{

   public class Student : Human

    {

        private string faculty = "";

         private short course=1;

         private short average_score=0;

         public Student(){}

         public Student(short age, short height_cen,short

         course, short number ,  short average_score,string

         name,string faculty,string street )

        {

        	address.number = number;

            address.street = street;

           this. average_score=average_score;

           this.age = age;

            this.height_cen = height_cen;

            this.course = course;

            this.name = name;

            this.faculty = faculty;

        }

       public  short Age

         {

             set {age = value;}

             get{return age;}

         }

       public  short Height_cen

         {

             set { height_cen = value; }

             get { return height_cen; }

         }

        public short Course

         {

             set { course = value; }

             get { return course; }

         }

       public  string Name

         {

             set { name = value; }

             get { return name; }

         }

        public string Surname

        {

            set { surname = value; }

            get { return surname; }

        }

       public  string Faculty

         {

             set { faculty = value; }

             get { return faculty; }

         }

        public short Average_score

         {

             set { average_score = value; }

             get { return average_score; }

         }

             public short Number

        {

            set { address. number= value; }

            get { return address.number; }

        }

       public string Street

        {

            set { address.street = value; }

            get { return address.street; }

        }



    }

}
