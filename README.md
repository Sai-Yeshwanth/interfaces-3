interface A
{
	void display();
	void show();
}
class B implements A
{
	public void display()
	{
		System.out.println("Hello im implemented");
	}
}
class Jala 
{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 A b = new B();
			 b.display();
		
	}
}

