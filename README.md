HackBulgaria-solutions-
=======================

Solution of the first  task for Hack Bulgaria CoreRuby course

public class Factorial
{
  public static void main()
  {  
    ulong kth_factoriel;       //0 to 18,446,744,073,709,551,615
	int n,k;
	public int Fact(int n)
	{
	  if(n<=1) return 1;
	  else return n*Fact(n-1);
	}
	kth_factoriel=Math.Pow(Fact(n),k);
	Console.Writeln(kth_factoriel);
  }
}
