# Fibonacci-series-
int fib(int n)

{

if(n<=1)

return n;

else

return fib(n-1)+fib(n-2);

}

void main()

{

int i,n;

clrscr();

printf("Enter number of terms");

scanf("%d",&n);

for(i=0;i<n;i++)

{

printf("%d\n",fib(i));

}

getch(); 

}
