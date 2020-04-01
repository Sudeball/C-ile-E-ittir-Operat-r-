//VARIABLE DESCRIPTION
string cinsiyet;
sbyte yas;
//ASK THE GENDER AND AGE OF THE USER
Console.Write("Cinsiyetiniz? Kadın / Erkek ");
                                                                 
cinsiyet = Console.ReadLine();
Console.Write("Yaşınız?");
yas=SByte.Parse(Console.ReadLine());
//18 years old and masculine you can marry
if (cinsiyet == "ERKEK" && yas == 18)
{
Console.Write("Artık Evlenebilirsiniz :)");
}
//PAUSE
Console.ReadLine();
