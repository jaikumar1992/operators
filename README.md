# operators
basic operators in java

class operators
{
int a=25;
int b=42;
void add()
{
System.out.println("---arithmetic operators---");
System.out.println(a+b);
System.out.println(a-b);
System.out.println(a*b);
System.out.println(a/b);
System.out.println(3+a+a);
System.out.println(a--);
}
void logical()
{
	System.out.println("---logical operators---");
System.out.println(a&a);
System.out.println(a|a);
System.out.println(a/b);
}
void bitwise()
{
	System.out.println("---bitwise operators---");
	System.out.println(a&b);
	System.out.println(a|b);
	System.out.println(a^b);
	System.out.println(a<<b);
	System.out.println(a>>b);
}
void relational()
{
	System.out.println("---relational operators---");
	System.out.println(a==b);
	System.out.println(a<b);
	System.out.println(a>b);
	System.out.println(a>=b);
	System.out.println(a<=b);
}
void assignment()
{
	System.out.println("---assignment operators---");
	System.out.println(a+=b);
	System.out.println(a-=b);
	System.out.println(a*=b);
	System.out.println(a/=b);
	System.out.println(a&=b);
}
public static void main(String []args)
{
operators o1=new operators();
o1.add();
o1.logical();
o1.bitwise();
o1.relational();
o1.assignment();
}
}
