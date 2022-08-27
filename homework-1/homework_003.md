//Написать программу которая на вход принимает число и выдаёт является ли числочётным ( делится оно на 2 без остатка) 4,3,7 

for (int i = 0; i < 4; i++)
{
if (i %2 == 0 && i != 0){   
Console.Write(i);
Console.WriteLine("  четное");
}
else
{
Console.Write(i);
Console.WriteLine("  не четное");  
}
}