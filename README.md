# Java
repo for commands demostraition.
-----------Addition-------------
public class Add {
	public static void add(int n1,int n2)
	{
		int n3=n1+n2;
		System.out.println("Addition of:"+n1+"+"+n2+"="+n3);		
	}

	public static void main(String[] args) {
		Scanner s=new Scanner(System.in);
		System.out.println("Enter 1 number:");
		int a=s.nextInt();
		System.out.println("Enter 2 number:");
		int b=s.nextInt();
		
		add(a, b);
		}
}

