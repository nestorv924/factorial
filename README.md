# factorial
class fac
{

public void factorial()
{
Random ran = new Random();
int x = 6;
int[] Ve = new int[x];

for (int i = 0; i < x; i++)
{
Console.WriteLine("Numeros:");
Ve[i] = ran.Next(10, 20);
Console.WriteLine(Vektor[r]);
}
for (int  i= 0; i < x; i++)
{
Ve[i] = Ve[i] * i;
Console.WriteLine("El factorial es: " + Ve[i]);
}
}

public int recur(int n)
{

if (n == 0)
{
return 1;
}
else
{
return n + recur(n - 1);
}
}
static void Main(string[] args)
{
fac ob = new fac();
Random run = new Random();
int op = 0;
while (op != 100)
{
Console.WriteLine(" 1. factorial  ");
Console.WriteLine(" 2.- recursividad  ");
op = int.Parse(Console.ReadLine());
Console.WriteLine();
Console.Clear();
switch (op)
{
case 1:
TimeSpan stop;
TimeSpan start = new TimeSpan(DateTime.Now.Ticks);
ob.factorial();
stop = new TimeSpan(DateTime.Now.Ticks);
Console.Write(stop.Subtract(start).TotalSeconds); Console.WriteLine(" los  segundos son  ");
break;
case 2:


TimeSpan starte = new TimeSpan(DateTime.Now.Ticks);
int a = ren.Factorial(8);
Console.WriteLine(" el resultado es " + f);
stop = new TimeSpan(DateTime.Now.Ticks);
Console.Write(stop.Subtract(start).TotalSeconds); Console.WriteLine(" los segundos son  ");
break;
}
}
Console.ReadKey();
