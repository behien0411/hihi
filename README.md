public My_FIB {
long fib(int n) {
if(n==0|| n==1) return 1;
else return fib(n-1) + fib(n-2);
}
public static void main(String[] args) {
My_FIB m= new My_FIB(); int n=10;
System.out.print("\n So tho tren dao thang thu " + n+ "= " + m.fib(n));
}
}
