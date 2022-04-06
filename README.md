# Inheritance_Interface
java code of inheritance with Interface.

interface sampleInterface

{

	void meth1();
  
	void meth2();
  
}

interface childInterface extends sampleInterface

{

	void meth3();
  
	void meth4();
  
}

class sample implements childInterface

{

	public void meth3()
  
	{
  
		System.out.println("meth3");
    
	}
  
	public void meth4()
  
	{
  
		System.out.println("meth4");
    
	}
  
	public void meth1()
  
	{
  
		System.out.println("meth1");
    
	}
  
	public void meth2()
  
	{
  
		System.out.println("meth2");
    
	}
  
}

class InheritanceInterface

{

	public static void main(String args[])
  
	{
  
		sample obj=new sample();
    
		obj.meth1();
    
		obj.meth2();
    
		obj.meth3();
    
		obj.meth4();
    
	}
  
}
