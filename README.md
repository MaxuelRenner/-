# -
using System; using System.Collections.Generic; using System.Linq; using System.Text; using System.Threading.Tasks;  namespace STACK_I_OPASHKA {     class Program     {         static void Main(string[] args)         {                          Queue&lt;double> q1 = new Queue&lt;double>();             q1.Enqueue(2);             q1.Enqueue(4);             double o = q1.Dequeue();             Console.WriteLine(o);             q1.Enqueue(6);             q1.Enqueue(8);             q1.Enqueue(10);             Console.WriteLine(q1.Dequeue());             q1.Enqueue(12);             Console.Read();               while (q1.Count > 0)             {                 Console.WriteLine(q1.Dequeue());             }             Console.Read();              Console.WriteLine("Stack");             Stack&lt;double> s1 = new Stack&lt;double>();             s1.Push(2);             s1.Push(4);             double a = s1.Pop();             Console.WriteLine(a);             Console.WriteLine(s1.Pop());              s1.Push(6);             s1.Push(8);             s1.Push(10);             Console.WriteLine(s1.Pop());             s1.Push(12);                          while (s1.Count > 0)             {                 Console.WriteLine(s1.Pop());             }               Console.Read();         }              }  }
