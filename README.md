# C-Bypass-launcher
Write That code inside of program.cs

//ConsoleApp (Program.cs)
Random random = new Random();
int length = 16;
var rString = "";
for (var i = 0; i < length; i++)
{
rString += ((char)(random.Next(1, 26) + 64)).ToString();
}
Console.Title = rString;

//FormApp (Form1.cs)
Random random = new Random();
int length = 16;
var rString = "";
for (var i = 0; i < length; i++)
{
rString += ((char)(random.Next(1, 26) + 64)).ToString();
}
this.Text = rString;

https://prnt.sc/v9a517

mertgmr & Purpl£#0001
