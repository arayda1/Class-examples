using System;

namespace MyApplication
{
  class Car
  {
    string color = "red";
    string colorr = "blue";
    string colors = "yellow";

    static void Main(string[] args)
    {
      Car myObj1 = new Car();
      Car myObj2 = new Car();
      Car myObj3 = new Car();
      Console.WriteLine(myObj1.color);
      Console.WriteLine(myObj2.colorr);
      Console.WriteLine(myObj3.colors);
    }
  }
}
