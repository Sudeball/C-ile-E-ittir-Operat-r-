//VARIABLE DESCRIPTION
string cinsiyet;
sbyte yas;

//ASK THE GENDER AND AGE OF THE USER
Console.Write("Your gender? Woman man");
                                                                 
cinsiyet = Console.ReadLine();
Console.Write("Your age?");
yas=SByte.Parse(Console.ReadLine());

//18 years old and masculine you can marry
if (cinsiyet == "MALE" && yas == 18)
{
Console.Write("Now You Can Get Married");
}

//PAUSE
Console.ReadLine();
