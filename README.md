# patterns-loops-practice
Some patterns to practice loops in programming fundamentals 


## Pattern 1 

![Image description](https://i.imgur.com/1znEStB.png)

###### while loop

```
#include <iostream>
using namespace std;
int main()
{
	int i=1,slash=0,exclamation=22;
	while (i<=6)
	{
		int j=1;
		while (j<=slash)
		{
			cout<<"/";
			j++;
		}
		int k=1;
		while (k<=exclamation)
		{
			cout<<"!";
			k++;
		}
		int l=1;
		while (l<=slash)
		{
			cout<<"\\";
			l++;
		}
	cout<<"\n";
	i++;	
	slash+=2;
	exclamation-=4;
		
	}
	return 0;
}
```


###### for loop
```
#include <iostream>
using namespace std;
int main()
{
	int slash=0,exclamation=22;
	for (int i=1;i<=6;i++)
	{
		for (int j=1;j<=slash;j++)
		{
			cout<<"\\";
		}
		for (int k=1;k<=exclamation;k++)
		{
			cout<<"!";
		}
		for (int l=1;l<=slash;l++)
		{
			cout<<"/";
		}
		cout<<"\n";
	slash+=2;
	exclamation-=4;	
	}

	
	return 0;
}
```


## Pattern 2

![Image description](https://i.imgur.com/TBCn7YV.png)

###### for loop
```
#include <iostream>
using namespace std;
int main()
{
	int star=6,space=1,slash=12,bslash=0;
	for (int i=1;i<=7;i++)
	{
		for (int j=1;j<=star;j++)
		{
			cout<<"*";
		}
		for (int k=1;k<=space;k++)
		{
			cout<<" ";
		}
		for (int l=1;l<=slash;l++)
		{
			cout<<"/";
		}
		for (int m=1;m<=bslash;m++)
		{
			cout<<"\\";
		}
		for (int n=1;n<=space;n++)
		{
			cout<<" ";
		}
		for (int o=1;o<=star;o++)
		{
			cout<<"*";
		}
	cout<<"\n";
	star-=1;
	space+=1;
	slash-=2;
	bslash+=2;		
	}
return 0;	
}

```


## Pattern 3

![Image description](https://i.imgur.com/VDBHJnl.png)

```
#include <iostream>
using namespace std;
int main()
{
 int space=8,n=9;
 for(int i=1;i<=n;i++)
 {
 	for (int j=1;j<=space;j++)
 	{
 		cout<<" ";
	 }
	 space-=1;
	int c=1;
	for (int k=1;k<=i;k++)
	{
		cout<<c;
		c+=1;
	 } 
	 
	c=i-1;
	for(int l=2;l<=i;l++)
	{
		cout<<c;
		c-=1;
	}
	
	cout<<"\n";
 }
 int sp=1,a=8;
 for(int j=1;j<=8;j++)
 {
 	for(int k=1;k<=sp;k++)
 	{
 		cout<<" ";
	 }
	 sp+=1;
	 for (int l=1;l<=a;l++)
	 {
	 	cout<<l;
	 }
	 cout<<"\n";
	 a-=1;
 }

}

```


## Pattern 4

![Image description](https://i.imgur.com/PCCSKDw.png)

```
#include <iostream>
using namespace std;
int main()
{
	for (int i=1;i<=11;i++)
	{
		if (i==1 || i==11)
		{
			cout<<"+";
		}
		else 
		{
			cout<<"-";
		}
	}
	cout<<"\n";
	int space=4,slash=0;
	for (int j=1;j<=4;j++)
	{
		cout<<"|";
		for (int k=1;k<=space;k++)
		{
			cout<<" ";
		}
		for (int l=1;l<=slash;l++)
		{
			cout<<"/";
		}
		cout<<"*";
		for (int m=1;m<=slash;m++)
		{
			cout<<"\\";
		}
		for (int n=1;n<=space;n++)
		{
			cout<<" ";
		}
		cout<<"|";
		cout<<"\n";
		space-=1;
		slash+=1;
	}
	int sp=1,slash1=3;
	for (int j=1;j<=4;j++)
	{
		cout<<"|";
		for (int k=1;k<=sp;k++)
		{
			cout<<" ";
		}
		for (int l=1;l<=slash1;l++)
		{
			cout<<"\\";
		}
		cout<<"*";
		for (int m=1;m<=slash1;m++)
		{
			cout<<"/";
		}
		for (int n=1;n<=sp;n++)
		{
			cout<<" ";
		}
		cout<<"|";
		cout<<"\n";
		sp+=1;
		slash1-=1;
	}
		for (int i=1;i<=11;i++)
	{
		if (i==1 || i==11)
		{
			cout<<"+";
		}
		else 
		{
			cout<<"-";
		}
	}
	cout<<"\n";
	int sp1=1,slash2=3;
	for (int j=1;j<=4;j++)
	{
		cout<<"|";
		for (int k=1;k<=sp1;k++)
		{
			cout<<" ";
		}
		for (int l=1;l<=slash2;l++)
		{
			cout<<"\\";
		}
		cout<<"*";
		for (int m=1;m<=slash2;m++)
		{
			cout<<"/";
		}
		for (int n=1;n<=sp1;n++)
		{
			cout<<" ";
		}
		cout<<"|";
		cout<<"\n";
		sp1+=1;
		slash2-=1;
	}
	int sp2=4,slash3=0;
	for (int j=1;j<=4;j++)
	{
		cout<<"|";
		for (int k=1;k<=sp2;k++)
		{
			cout<<" ";
		}
		for (int l=1;l<=slash3;l++)
		{
			cout<<"/";
		}
		cout<<"*";
		for (int m=1;m<=slash3;m++)
		{
			cout<<"\\";
		}
		for (int n=1;n<=sp2;n++)
		{
			cout<<" ";
		}
		cout<<"|";
		cout<<"\n";
		sp2-=1;
		slash3+=1;
	}
		for (int i=1;i<=11;i++)
	{
		if (i==1 || i==11)
		{
			cout<<"+";
		}
		else 
		{
			cout<<"-";
		}
	}
	return 0;
}


```

## Pattern 5 (pascal triangle)

![Image description](https://i.imgur.com/UJ2N7zx.png)


```
#include <iostream>
using namespace std;
int main()
{
 int space=8,n=9;
 for(int i=1;i<=n;i++)
 {
 	for (int j=1;j<=space;j++)
 	{
 		cout<<" ";
	 }
	 space-=1;
	int c=1;
	for (int k=1;k<=i;k++)
	{
		cout<<c;
		c+=1;
	 } 
	 
	c=i-1;
	for(int l=2;l<=i;l++)
	{
		cout<<c;
		c-=1;
	}
	
	cout<<"\n";
 }
 int sp=1,a=8;
 for(int j=1;j<=8;j++)
 {
 	for(int k=1;k<=sp;k++)
 	{
 		cout<<" ";
	 }
	 sp+=1;
	 for (int l=1;l<=a;l++)
	 {
	 	cout<<l;
	 }
	 cout<<"\n";
	 a-=1;
 }

}

```
