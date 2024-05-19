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

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Sale Season

  import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		Scanner sc = new Scanner(System.in);
		int t=sc.nextInt();
		while(t-->0)
		{
		    int x=sc.nextInt();
		    if(x<=100)
		    System.out.println(x);
		    else if(x>100 && x<=1000)
		    System.out.println(x-25);
		    else if(x>1000 && x<=5000)
		    System.out.println(x-100);
		    else
		    System.out.println(x-500);
		}
	}
}


<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Minimum Pizzas

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner pizza = new Scanner(System.in);
		int T=pizza.nextInt();
		while(T-->0){
		    int N = pizza.nextInt();  // the number of friends 
		    int X = pizza.nextInt();   // the number of slices
		    int total = N*X;  
		    int req = total/4;
		    if(total%4!=0)
		        System.out.println(req+1);
		        else
		             System.out.println(req);
		        
		    
		}
		

	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chefland Games

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	    	Scanner game = new Scanner(System.in);
		// your code goes here
		int T = game.nextInt();
		
		while(T-->0){
		     int R1 = game.nextInt(); // Refree's deciesion R1
		     int R2 = game.nextInt(); // Refree's deciesion R2
		     int R3 = game.nextInt(); // Refree's deciesion R3
		     int R4 = game.nextInt(); // Refree's deciesion R4
		     
		     if(R1==0 && R2==0 && R3==0 && R4==0){           // LOGIC(if all decision will be equal to 0 then it should print IN )
		         System.out.println("IN");
		     }
		     else{
		          System.out.println("OUT");
		     }
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Expert Setter

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
        	Scanner expert = new Scanner(System.in);
		// your code goes here
		int T = expert.nextInt();
		
		while(T-->0){
		int X = expert.nextInt(); // The number of problem submitted
		int Y = expert.nextInt(); // the number of approved preoblem
		if(2*Y>=X){
		    System.out.println("YES");
		}
		else{
		     System.out.println("no");
		}
}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chef and NextGen

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		
        	Scanner nextgen = new Scanner(System.in);
		// your code goes here
		int T = nextgen.nextInt();
		
		while(T-->0){
		int A = nextgen.nextInt();  // power in unit 
		int B = nextgen.nextInt();  // years 
		int X = nextgen.nextInt();  // helium in grams
		int Y = nextgen.nextInt();  // Y uint power by 1 gram helium
		
		if(A*B <= X*Y){
		  System.out.println("Yes");
		}
		else{
		   System.out.println("no");
		}
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Sugarcane Juice Business

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		
       Scanner profit = new Scanner(System.in);
		// your code goes here
		int T = profit.nextInt();
		
		while(T-->0){
         int N = profit.nextInt();
         int t = N*50;  // total sell 
         int invest = (t*20)/100 + (t*20)/100 + (t*30)/100; // LOGIC 
         int P  = t-invest;  // profit
         System.out.println(P);
         
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Count the Notebooks

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		 Scanner note = new Scanner(System.in);
		int T = note.nextInt();
		
		while(T-->0){
            
        int N = note.nextInt();     // weight of pulp 
        int pages = N*1000;         // total pages from pulp
        int notebook = pages/100;   // total notebooks made from pages
        System.out.println(notebook);   
	}
	}
}


<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chef and Candies

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			 Scanner candy = new Scanner(System.in);
		     int T = candy.nextInt();
		
	     	while(T-->0){
	     	int N = candy.nextInt();  // the number of children
	        int X = candy.nextInt();  // number of already has candies
	     	     
             if(N>=X){
		        if((N-X)%4==0)
		        System.out.println((N-X)/4);
		        else
		        System.out.println((N-X)/4+1);
		    }
		    else
		    System.out.println("0");
		}
	}
}

