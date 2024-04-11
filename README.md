# 500-to-1000-difficulty-rating-CODECHEF-SOLUTIONS
Here all the CodeChef Solutions are listed under 500 to 1000 difficulty rating.
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Greater Average

  CODE--> 
           import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner in = new Scanner(System.in);
		int T = in.nextInt();
		while(T-->0){
		    int a = in.nextInt();
		    int b = in.nextInt();
		    int c = in.nextInt();
		    System.out.println(0.5*(a+b)>c?"Yes":"No");
		}

	}
}
<------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------>

Problem--> Subscriptions 
  CODE-->
  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		int T = sc.nextInt();
		while(T-->0){
		     int N = sc.nextInt();
		     int X = sc.nextInt();
		     int r1 = 0;   // remaining freinds 
		     int r = N/6;    // no. of freinds divided by 6 
		     if(N % 6 != 0){
		         r1++;
		     }
		       int fin = r1+r;
		       System.out.println(fin*X);
		     
		}

	}
}

<------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
