//# simplejavaclasses
//simple implementation of java
class demo{
double width;
double height;
double depth;
demo(double w,double h,double d)
{
width=w;
height=h;
depth=d;
}
double volume()
{
return width*height*depth;
}
}
class democlass()
{
public static void main(String args[])
{
double volume;
demo mybox=new demo(4,7,3);
volume=mybox.volume();
System.out.println("volume");
}
}
