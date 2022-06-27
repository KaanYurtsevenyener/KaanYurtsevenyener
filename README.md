- 👋 Hi, I’m @KaanYurtsevenyener
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

  
  
  
  {
  
  static void Main(string[] args)
        {
            int exam1 = 60;
            int exam2 = 60;
            if (exam1*0.4 + exam2*0.6>=60)
	{
                Console.WriteLine("passed");
	}
            else if (exam1*0.4 + exam2*0.6 <40)
            {
                Console.WriteLine("integration");
            }
            else
	{
                Console.WriteLine("stay");

	}
            //if (number <= 87) {
            //    Console.WriteLine("This Number Is Small Than 88 ");
            //}

            //else if (number == 88)  {
            //    Console.WriteLine("This Number Is 88");
            //}

            //else {
            //    Console.WriteLine("This Number Is Bigger Than 88");
            //}
            //switch (number)
            //{
            //    case 85:
            //        Console.WriteLine("This Number Is Small Than 88 ");
            //        break;
            //    case 87:
            //        Console.WriteLine("This Number Is Small Than 88 ");
            //        break;
            //    default:
            //        Console.WriteLine("This Number Is 88");
            //        break;

            //if (number >= 0 && number <= 100)
            //{
            //    Console.WriteLine("Number is between 0-100");

            //}
            //else if (number > 100 && number <= 200)
            //{
            //    Console.WriteLine("Number is between 101-200");

            //}
            //else if (number > 200 || number < 0)
            //{
            //    Console.WriteLine("Number is less than 0 or greater than 200");
            //}

            Console.ReadLine();

            //value type 
            //Console.WriteLine("Hello World");
            decimal number6 = 10.4m;
            double number5 = 10.4;
            char character = 'A';
            bool conditions = true;
            byte number4 = 0;
            short number3 = -32768;
            int number1 = 2147483647;
            var number7 = 10;
            number7 = 'A';
            long number2 = -922337203685477580;
            Console.WriteLine("Number1 is  {0} ", number1);
            Console.WriteLine("Number2 is  {0} ", number2);
            Console.WriteLine("Number3 is  {0} ", number3);
            Console.WriteLine("Number4 is  {0} ", number4);
            Console.WriteLine("Number5 is  {0} ", number5);
            Console.WriteLine("Number6 is  {0} ", number6);
            Console.WriteLine("Number7 is  {0} ", number7);
            Console.WriteLine("character is : {0} ", (int)character);
            Console.ReadLine();
        }
        
	}
