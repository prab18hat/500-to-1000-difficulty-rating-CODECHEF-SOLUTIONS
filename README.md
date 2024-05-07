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

Problem-->  Janmansh and Assignments

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
	       int X = sc.nextInt();                           // X is time started for assignment
	        if(X<=7){                        
	           System.out.println("Yes");
	       }
	       else{
	            System.out.println("NO");
	       }
	   }

	}
}

<------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->

Problem---> Exams

import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner Exm = new Scanner(System.in);
  
		int T = Exm.nextInt();                  // Number of test case
		 while(T-->0){
	
		int X = Exm.nextInt();              // number of schools X 
		int Y = Exm.nextInt();              // NUMBER OF STUDENTS Y
		int Z = Exm.nextInt();              // number of passed students Z
		
		int appear  = X * Y;                // total appered students 
		
          if(Z > appear/2){
              System.out.println("Yes");
          }
          else {
              System.out.println("No");
          }

		 }
	}
}

<------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->

 Problem--> Chef in his Office

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
		     int X = sc.nextInt(); // work hours from monday to thursday
		     int Y = sc.nextInt(); // work hours of only friday
		     int Total = 4*X + Y;
		     System.out.println(Total);
		}

	}
}

<------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->

Problem--> MAHASENA

import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner battle = new Scanner(System.in);
		int N = battle.nextInt();   // N is the number of Soldiers
		int  count = 0;
		for(int i = 1; i <= N; i++){
		    int A = battle.nextInt();     // A is the number of weapons
		    if(A % 2 == 0){   // checking even condition 
		        count++;
		    }
		}
		 System.out.println(count>N-count ? "Ready for Battle" : "NOT READY");

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> CRED COINS 

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner Cred = new Scanner(System.in);
		int T = Cred.nextInt();
		while(T-->0){
		    int X = Cred.nextInt();   // number of cred coins
		    int Y = Cred.nextInt();    // number of bills
		    int Total = (X*Y) / 100;
		    System.out.println(Total);
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Water Filling

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner water = new Scanner(System.in);
		int T = water.nextInt();
		while(T-->0){   // no of test cases
		    int B1 = water.nextInt(); // bottle 1 status 
		    int B2 = water.nextInt();  // bottle 2 status 
		    int B3 = water.nextInt();  // bottle 3 status 
		    if(B1+B2+B3 <= 1){        // logic for given condition
		        System.out.println("Water filling Time");
		    }
		    else{
		        System.out.println("Not now");
		    }
		}

	}
}


