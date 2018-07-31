# Default-constructor
class Test15
{
int total;
 Test15()
{
  int a=10;
  int b=20;
 total=a+b;
 }
void disp()
{
 
 System.out.println("The sum is:"+total);
}
public static void main(String args[])
{
  Test15 obj=new Test15();
  obj.disp();
}
}
