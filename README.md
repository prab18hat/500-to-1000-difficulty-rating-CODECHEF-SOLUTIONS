 500-to-1000-difficulty-rating-CODECHEF-SOLUTIONS
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

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Car or Bike

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		 Scanner home = new Scanner(System.in);
		     int T = home.nextInt();
		   	while(T-->0){
	     	 int X = home.nextInt();    // time taken by bike 
	     	 int Y = home.nextInt();    // time etaken by car 
	     if(X>Y){
	         System.out.println("car");
	     }	 
	     else if(Y>X){
	         System.out.println("bike");
	     }
	     else{
	         System.out.println("same");
	     }

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Is the Score Consistent

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here

		 Scanner score = new Scanner(System.in);
		     int T = score.nextInt();
		   	while(T-->0){
		   int A = score.nextInt();	   // initial  GOAL score by TEAM A
		   int B = score.nextInt();  // initial  GOAL score by TEAM B
		   int C = score.nextInt();  // final goals score by team A
		   int D = score.nextInt(); // final goals score by team B
		   
		   if(A<=C && B<=D){
		       System.out.println("POSSIBLE");
		   }
		  else{
		      System.out.println("IMPOSSIBLE");
		  } 	    
		   	    
		   	}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> The Three Topics 

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		 Scanner topic = new Scanner(System.in);
		   	 int A = topic.nextInt();    //  topic prepared by chef
		   	 int B = topic.nextInt();    // topic  prepared by chef
		   	 int C = topic.nextInt();    // topic  prepared by chef
		   	 int X = topic.nextInt();   // topic given to him in the contetst
		   	 
		   	 if(X==A || X==B ||  X==C){
		   	     System.out.println("YES");
		   	 }
		   	 else{
		   	      System.out.println("NO");
		   	 }
    	
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Monopoly

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner profit = new Scanner(System.in);
		int T = profit.nextInt();
		while(T-->0){
		int P = profit.nextInt();  
		int Q= profit.nextInt();
		int R = profit.nextInt();
		int S = profit.nextInt();
	
		
		if(P>Q+R+S || Q>P+R+S || S>P+Q+R || R>P+Q+S ){
		    System.out.println("yes");
		}
		else{
		    System.out.println("NO");
		}
		
		
		
		
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Problems in your to-do list

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner sc = new Scanner(System.in);
		int t = sc.nextInt();
		while(t-- >0) {
		    int n = sc.nextInt();
		    int ans =0;
		    for(int i=0;i<n;i++) {
		        int x = sc.nextInt();
		        if (x>=1000) {
		            ans++;
		        }
		    }
		    System.out.println(ans);
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Air Conditioner Temperature

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner ac = new Scanner(System.in);
		int T = ac.nextInt();
		while(T-- >0) {
		int A = ac.nextInt();   // Temp. want Alice
		int B = ac.nextInt();   // Temp. want Bob
		int C = ac.nextInt();	// Temp. want Charlie
		if(A<=B && C<=B){
		    System.out.println("Yes");
		}
		else{
		     System.out.println("no");
		}
		      
		      
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Nearest Exit

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner exit = new Scanner(System.in);
		int T  = exit.nextInt();
		while(T-->0){
		int X = exit.nextInt(); // seat number 
		if(X<=50){
		    System.out.println("Left");
		    
		}
		else{
		    System.out.println("Right");
		}
		    
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Reverse The Number

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner rev = new Scanner(System.in);
		int T  = rev.nextInt();
		while(T-->0){
		
StringBuilder str = new StringBuilder(rev.next());
            System.out.println(Integer.parseInt(str.reverse().toString()));

		    
		    
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Sasta Shark Tank

import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goe
		Scanner dv = new Scanner(System.in);
		int T = dv.nextInt();
		while(T-->0){
     	int A = dv.nextInt();
     	int B = dv.nextInt();
     	if(10*A>5*B){
     	    System.out.println("first");
     	}
     	if(5*B>10*A){
     	    System.out.println("second");
     	}
     	if(5*B==10*A){
     	    System.out.println("any");
     	}
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Good Program

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner bit = new Scanner(System.in);
		int T = bit.nextInt();
		while(T-->0){
		 int N = bit.nextInt();
		 if(N%4==0){
		     System.out.println("Good");
		     
		 }
		 else{
		     System.out.println("Not good");
		 }
		    
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Qualify the round

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
	     Scanner points= new Scanner(System.in);
	     int T = points.nextInt();
	     while(T-->0){
	    int X = points.nextInt();
	    int A = points.nextInt(); 
        int B = points.nextInt();
        
        if(A+2*B>=X){
            System.out.println("qualify");
        }
        else{
            System.out.println("notqualify");
        }
	         
	     }

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Elections in Chefland

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner vote = new Scanner(System.in);
	     int T = vote.nextInt();
	     while(T-->0){
	    int N= vote.nextInt();
	    int X = vote.nextInt();
	    
	    int count = 0;
            for (int i = 0; i < N; i++) {
                int age = vote.nextInt();
                if (age >= X) {
                    count++;
                }
            }
            System.out.println(count);
	    
	    
	     }	

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Minimum Cars required

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner car = new Scanner(System.in);
	     int T = car.nextInt();
	     while(T-->0){
	     int n = car.nextInt();
	     int ans = 0;
		    if(n < 4 && n > 0){
		     ans = 1;   
		    }else if(n %4 == 0){
		        ans = n/4;
		    }else{
		        ans = n/4 + 1;
		    }
		    System.out.println(ans);
	        
	     }

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Test Score

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner marks= new Scanner(System.in);
		int T = marks.nextInt();
		while(T-->0){
		int N = marks.nextInt();
        int X = marks.nextInt();
        int Y = marks.nextInt();
        
        if(Y%X==0){
            System.out.println("yes");
        }
        else{
            System.out.println("no");
        }
	    
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Jenga Night

  import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc=new Scanner(System.in);
		int t=sc.nextInt();
		for(int i=0;i<t;i++){
		    int n=sc.nextInt();
		    int x=sc.nextInt();
		    if(n<=x && x%n==0){
		        System.out.println("YES");
		    }else
		    System.out.println("NO");
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Bus Seat Numbering

  /* package codechef; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
	    
		Scanner obj=new Scanner (System.in);
		int T=obj.nextInt();
		for (int i=0;i<T;i++){
		    int n=obj.nextInt();
		    if (n>0 && n<=10){
		        System.out.println("Lower Double");
		    }
		     else if (n>10 && n<=15){
		        System.out.println("Lower Single");
		    }
		    else if (n>15 && n<=25){
		        System.out.println("Upper Double");
		    }
		    else if (n>25 && n<=30){
		        System.out.println("Upper Single");
		    }
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Discus Throw

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
		 int a = sc.nextInt();   // score a 
		 int b = sc.nextInt();  // score b 
		 int c = sc.nextInt();  // score c
		  
		   if(a>b && a>=c){
		        System.out.println(a);
		    }else if(b>=a && b>=c){
		        System.out.println(b);
		    }else {
		        System.out.println(c);
		    }
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Maximise the Tastiness

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner sc=new Scanner(System.in);
		int t=sc.nextInt();
		while(t-->0){
		    int a=sc.nextInt();
		    int b=sc.nextInt();
		    int c=sc.nextInt();
		    int d=sc.nextInt();
		    int sum=Math.max(a,b)+Math.max(c,d);
		    System.out.println(sum);
		
		
		
		

	}
}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Watching Movies at 2x

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner movie = new Scanner(System.in);
		int X = movie.nextInt();
		int Y = movie.nextInt();
		int Total = Y/2+(X-Y);
		System.out.println(Total);
		

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Police and Thief

  import java.util.*;
import java.lang.*;
import java.io.*;


class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner chef = new Scanner(System.in);
		int T = chef.nextInt();
		while(T-->0){
		    int X = chef.nextInt(); //LOACTION OF POLICE 
		    int Y = chef.nextInt();  // LOCATION OF THIEF
		    
		    int Time = Math.abs(X-Y);
		    System.out.println(Time);
		}

	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Flip the cards

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner card = new Scanner(System.in);
		int T = card.nextInt();
		while(T-->0){
		 int n = card.nextInt();
	     int x = card.nextInt(); 
	      if(n == x)
		        System.out.println(0);
		    else if(x > n/2)
		        System.out.println(n-x);
		    else
		        System.out.println(x);
	     
		}	

	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Bath in Winters

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner bath = new Scanner(System.in);
		int T = bath.nextInt();
		while(T-->0){
		    int X = bath.nextInt();
		    int Y = bath.nextInt();
		    int maxBath = X/(2*Y);
		    System.out.println(maxBath);
		}
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Finding Shoes

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner shoes = new Scanner(System.in);
		int T = shoes.nextInt();
		while(T-->0){
		    
		int N = shoes.nextInt();     // number of chef's frends
		int M = shoes.nextInt();     // number of left shoes Chef has
		
		
	   if(M==0){
	       System.out.println(N*2);
	   }
	   else if(N<M){
	        System.out.println(N);
	   }
	   else{
	        System.out.println(N+N-M);
	   }
		    
		    
		}
		
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Small factorials

  import java.util.*;
import java.lang.*;
import java.io.*;
import java.math.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner fac = new Scanner(System.in);
		int t = fac.nextInt();
		while(t-->0){
		    int n = fac.nextInt();
		    BigInteger fact = new BigInteger("1");
            for(int i = 2; i <= n; i++)
            fact = fact.multiply(BigInteger.valueOf(i));
            System.out.println(fact);
		}

	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Mario and Transformation

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner eat = new Scanner (System.in);
		int T = eat.nextInt();
		while(T-->0){
		    int X = eat.nextInt();
		   
		     if(X%3==0){
		        System.out.println("NORMAL");
		    }else if(X%3==1){
		        System.out.println("Huge");
		    }else{
		        System.out.println("Small");
		}

	}
}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Mario and Bullet

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner shoot = new Scanner (System.in);
		int T = shoot.nextInt();
		while(T-->0){
		    int X = shoot.nextInt();
            int Y = shoot.nextInt();
            int Z = shoot.nextInt();
            int res = Y/X;
            int time = Z-res;
            System.out.println(Math.max(0,time));
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chess Ratings
  

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc=new Scanner(System.in);
		int t=sc.nextInt();
		while(t-->0)
		{
		    int count=0;
		    int x=sc.nextInt();
		    int y=sc.nextInt();
		    if(x==y)
		   System.out.println(0);
		   else
		   {
		    while(y>x)
		    {
		       x=x+8;
		       count=count+1;
		       if(x>=y)
		       break;
		    }
		    System.out.println(count);
		}
		}
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Complementary Strand in a DNA


import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		int t = sc.nextInt();
		for (int i  =0;i<t;i++){
		    int n = sc.nextInt();
		    String s = sc.next();
		    String p = "";
		    for (int j = 0;j<n;j++){
		        if (s.charAt(j)=='A'){
		            p += 'T';
		        }
		        else if (s.charAt(j)=='T'){
		            p += 'A';
		        }
		        else if (s.charAt(j)=='G'){
		            p += 'C';
		        }
		        else{
		            p += 'G';
		        }
		    }
		    System.out.println(p);
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chef and Water Bottles

  import java.util.*;
public class Main{
public static void main(String args[]){
Scanner sc=new Scanner(System.in);
int t,n,x,k;
t=sc.nextInt();
while(t!=0)
{
    n=sc.nextInt();
    x=sc.nextInt();
    k=sc.nextInt();
    int z=0;
    if(x>k)
    System.out.println("0");
    else{
        z=k/x;
        if(z>n)
        System.out.println(n);
        else
        System.out.println(z);
    }
    t--;
}
}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Candy Distribution 

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
	
		Scanner  candy = new Scanner(System.in);
		int T = candy.nextInt();
		while(T-->0){
		  int N = candy.nextInt();   // number candies 
		  int M = candy.nextInt();   // number of friends
		  if(N%M==0 && (N/M)%2==0){
		      System.out.println("yes");
		  }
		  else{
		      System.out.println("no");
		  }
	
		  }
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Finding Square Roots

    import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
	 Scanner  sq = new Scanner(System.in);
		int T = sq.nextInt();
		while(T-->0){
		 int  N = sq.nextInt();
		 System.out.println((int)Math.sqrt(N));
		    
}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> The Last Levels

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner in = new Scanner(System.in);
		int t = in.nextInt();
		
		while(t-- > 0){
		    int x = in.nextInt();
		    int y = in.nextInt();
		    int z = in.nextInt();
		    
		    if(x % 3 != 0){
		        int Br = x / 3;
		        System.out.println(x*y + (Br*z));
		        
		    }else if(x % 3 == 0){
		        int Br = (x / 3) - 1;
		        System.out.println(x*y + (Br*z));
		        
		    }else{
		        System.out.println(x*y);
		        
		    }
		}
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Blackjack

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			// your code goes here
		Scanner win  = new Scanner(System.in);
		int T = win.nextInt();
		
		while(T-- > 0){
		    int A = win.nextInt();
		    int B = win.nextInt();
		    if(A+B>=11){
		        System.out.println(21-(A+B));
		    }
		    else{
		         System.out.println(-1);
		    }
}
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Fill Candies

  /* package codechef; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc=new Scanner(System.in);
		int t=sc.nextInt();
		for(int i=0;i<t;i++)
	    {
	        int n=sc.nextInt();
	        int k=sc.nextInt();
	        int m=sc.nextInt();
	        k=m*k;
	        if(n%k==0)
	        {
	            int c=(n/k);
	            System.out.println(c);
	        }
	        else{
	        int c=n/k;
	        System.out.println(c+1);
	    }}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> X Jumps

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner jump  = new Scanner(System.in);
		int T = jump.nextInt();
		while(T-- > 0){
		    int X = jump.nextInt();  // number of stairs want to reach
		    int Y = jump.nextInt();  // number of stairs he can climb in one
		    
		    int c = X/Y + X%Y;
		    System.out.println(c);
}
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chessboard Distance

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner chess  = new Scanner(System.in);
		int T = chess.nextInt();
		while(T-- > 0){
		    int X1 = chess.nextInt();
            int Y1 = chess.nextInt();
            int X2 = chess.nextInt();
            int Y2 = chess.nextInt();
           System.out.println(Math.max(Math.abs(X1-X2),Math.abs(Y1-Y2)));
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Valentine is Coming

  /* package codechef; // don't place package name! */

import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		 Scanner sc = new Scanner(System.in);
	   int t = sc.nextInt();
	   while(t-->0){
	   int x = sc.nextInt();
	   int y = sc.nextInt();
	   System.out.println(x/y);
	   }
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> It is My Serve

import java.util.*;
import java.lang.*;
import java.io.*;


class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		Scanner read = new Scanner(System.in);
		int t = read.nextInt();
		for(int i=0; i<t; i++){
		    int x = read.nextInt();
		    int y = read.nextInt();
		    if((x+y+1)<2){
		        System.out.println("Alice");
		    }
		    else{
		        if((((x+y+1)%4)==1)||(((x+y+1)%4)==2)){
		            System.out.println("Alice");
		        }
		        else{
		            System.out.println("Bob");
		        }
		    }
		}
	}
}

<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Water Mixing

  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner bath = new Scanner(System.in);
		int T = bath.nextInt();
		while(T-->0){
		 	int A = bath.nextInt();  // initial temp of bathtub
			int B = bath.nextInt(); // desired temp of bathtub
		 	int X = bath.nextInt();  // hot water 
		 	int Y = bath.nextInt();  // cold water
		 	
		  if(A<=B && (B-A)<=X)
	        {
	            System.out.println("yes");
	            
	        }
	        else if(A>=B && (A-B)<=Y)
	        {
	            System.out.println("yes");
	        }
	        else{
	            System.out.println("no");
	        }
	        
	    }
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Weights
  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner chef = new Scanner(System.in);
		int T = chef.nextInt();
		while(T-->0){
		 	int W = chef.nextInt();  // weight of object
		 	int X = chef.nextInt();  // wieght 1
		 	int Y = chef.nextInt();  // wieght 2
		 	int Z = chef.nextInt(); // wieght 3
		 	
		 if(W==X || W==Y || W==Z || W==(X+Y+Z)|| W==(X+Z) || W==(X+Y) ||  W == (Z+Y)){
		     System.out.println("yes");
		 }	
	
		 else{
		      System.out.println("no");
		 }
		 	
		 	
		}

	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chef and his Apps
  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner app = new Scanner(System.in);
		int T = app.nextInt();
		while(T-->0){
		 	int S = app.nextInt();  // Total Storage of his  phone
		 	int X = app.nextInt();  // first app occupy space
		 	int Y = app.nextInt();  // occupied space by 2nd app
		 	int Z = app.nextInt();  // memory req. for 3rd app
		    int A = S-(X+Y);
		    if(A>=Z){
		      System.out.println("0");
		    }
		    else if(Z<=X+A || Z<=Y+A){
		         System.out.println("1");
		    }
		    else{
		         System.out.println("2");
		    }
}
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Chef Eren
  import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		int T = sc.nextInt();
		while(T>0)
		{
		    int N = sc.nextInt(), A = sc.nextInt(), B = sc.nextInt();
		    int count1 = 0, count2 = 0;
		    for(int i=1;i<=N;i++)
		    {
		        if(i%2==0) count1++;
		        if(i%2!=0) count2++;
		    }
		    System.out.println((count1*A)+(count2*B));
		    
		    T--;
		}
	}
}
<-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->
  Problem---> Minimum number of coins
  import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
			Scanner coin = new Scanner(System.in);
		int T = coin.nextInt();
		while(T-->0)
		{
		    int X = coin.nextInt();
		    if(X%5==0 || X%10==0){
		        System.out.println( X/10+(X%10)/5);
		    }
		    else{
		        System.out.println("-1");
		    }
}
	}
}

<--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------->

import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner air = new Scanner(System.in);
		int T = air.nextInt();
		while(T-->0)
		{
		   int X = air.nextInt();
		   int N = air.nextInt();
		   
		   int planereq = (N+99) / 100;
		   int addplane = planereq-X;
		   System.out.println(Math.max(0, addplane));
		}
		air.close();
		

	}
}

