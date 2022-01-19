# first assignment about swapping numbers
first assignment #swapping numbers

//swap 3 numbers with temporary variable

package javaTutorial;


public class swap {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		        int a=10;
				int b=20;	
				int c=30;
				int d ;
		d=a+b+c;
		
		a=d-(a+b);//now a value is 30. Substituting the value of a in equation 2.
		b=d-(a+b);//now b value is 10. Substituting the value of b in equation 3.
		c=d-(a+b);//now c value is 20.
		
		
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);		
	}

}



//swap 3 numbers without temporary variable

package javaTutorial;

public class swap2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		    int a=10;
			int b=20;	
			int c=30;
			
			//lets put sum of all a,b and c on a
			a=a+b+c;
			
			//now lets substitute the value of a on equation b=a-(b+c)
		b=a-(b+c);
		
		    //now lets substitute the value of b on equation c=a-(b+c)
		c=a-(b+c);
		
		    //now lets substitute the value of c on equation a=a-(b+c)
		a=a-(b+c);
		
		
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);		
	}

}




////swap 4 numbers with temporary variable


package javaTutorial;

public class swap3{

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		
		    int a=10;
			int b=20;	
			int c=30;
			int d=40;
			int e;
		e=a+b+c+d;
		
		a=e-(a+b+c);//now a value is 40. Substituting the value of a in equation 2.
		b=e-(a+b+c);//now b value is 10. Substituting the value of a in equation 3.
		c=e-(a+b+c);//now c value is 20. Substituting the value of a in equation 4.
		d=e-(a+b+c);//now d value is 30.
	
		
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);
		System.out.println(d);	
	}
}



////swap 4 numbers without temporary variable


package javaTutorial;

public class swap4 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

	
		            int a=10;
					int b=20;	
					int c=30;
					int d=40;
					
					//lets put sum of all a,b,c and d on a
					a=a+b+c+d;	
					//now lets substitute the value of a on equation b=a-(b+c+d)
					b=a-(b+c+d);
					
					    //now lets substitute the value of b on equation c=a-(b+c+d)
					c=a-(b+c+d);
					
					
					
					    //now lets substitute the value of c on equation d=a-(b+c+d)
					d=a-(b+c+d);
					
				    //now lets substitute the value of d on equation a=a-(b+c+d)
					a=a-(b+c+d);
					
					
					System.out.println(a);
					System.out.println(b);
					System.out.println(c);
					System.out.println(d);	
	}

}
