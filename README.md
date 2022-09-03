# Calcular-formula-general este programa es para calcular los ejercicios que se necesite la formula general.Para que este programa funcione lo tiene que copiar en Visual Estudio






    class Program
    {
    
        static void Main(string[] args)
        {
        

            Console.WriteLine("Formula General ");
            double a, b, c, x1, x2;
            Console.WriteLine("Ingrese el valor de a: ");
            a = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Ingrese el valor de b: ");
            b = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("Ingrese el valor de c: ");
            c = Convert.ToDouble(Console.ReadLine());
            if (((Math.Pow(b, 2) - 4 * a * c) < 0))
            {
                Console.WriteLine("Los resultados no existen");

                
            }
           else
            {
                x1 = -(b + Math.Sqrt(Math.Pow(b, 2) - 4 * a * c)) / 2 * a;
                x2 = -(b - Math.Sqrt(Math.Pow(b, 2) - 4 * a * c)) / 2 * a;
                Console.WriteLine($"Lo resultados son: \nx1 = {x1}\nx2 ={x2}");
            }
        }
     
            
        
    }
}





