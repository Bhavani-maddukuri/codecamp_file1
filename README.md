import java.util.*;

class File1

{

public static void main(String args[])

{

int n,evensum=0,oddsum=0;

System.out.println("enter a number");

Scanner s=new Scanner(System.in);

n =s.nextInt();

int a[]=new int[n];

System.out.println("enter"+n+"values");

for(int i=0;i<n;i++)

{

a[i]=s.nextInt();

} 

for(int i=0;i<n;i++)

{

if(a[i]%2==0 && i%2==0)

{evensum=evensum+a[i];}

else if(a[i]%2==1 && i%2==1)

{

oddsum=oddsum+a[i];

}

}

System.out.println(+evensum+ " " +oddsum);

}

}
