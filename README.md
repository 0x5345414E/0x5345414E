# 0x5345414E

💻 c#, asp.net, and python with web application and automation focus.

🤳 humanitarian. provide optimization for others to perform at their highest capacity.

✨ meaningful work and make a positive impact on others around me, learn and teach something new everyday.

most of my activity is on Azure Devops :(

```c#
using System.Text;
class Program
{
    static void Main(string[] _)
    {
        string name = "SEAN";
        string hexValue = StringToHex(name);
        Console.WriteLine($"The hex value for {name} is {hexValue}, thanks for visiting!");
    }
    static string StringToHex(string input)
    {
        return string.Join("", Encoding.ASCII.GetBytes(input).Select(b => b.ToString("X2")));
    }
}
```
