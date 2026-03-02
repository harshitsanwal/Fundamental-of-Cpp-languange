# Different Patterns in Cpp
# 1 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int i=0,n,j,k=1;
    cout << "Enter the number: ";
    cin >> n;
    while(i<n)
    {
        j=0;
        while(j<n)
        {
            cout<< n-j+1;
            j++;
            
        }
        cout<<endl;
        i++;
    }
    return 0;
}
```
Input/Output
```
Enter the number: 4
5432
5432
5432
5432
```

# 2 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n,i=1,j,k=1;
    cout << "Enter the number: ";
    cin>> n;
    while(i<=n)
    {
        j=1;
        while(j<=n)
        {
            cout <<" " <<  k;
            j++;
            k++;
        }
        cout << endl;
        i++;
    }
    return 0;
}
```
Input/Output
```
Enter the number: 5
 1 2 3 4 5
 6 7 8 9 10
 11 12 13 14 15
 16 17 18 19 20
 21 22 23 24 25
```
# 3 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n,i=1,j,k=1;
    cout << "Enter the number: ";
    cin>> n;
    while(i<=n)
    {
        j=1;
        while(j<=n)
        {
            cout <<" " <<  k;
            j++;
            k++;
        }
        cout << endl;
        i++;
    }
    return 0;
}
```
Input/Output
```
Enter the number: 4
 1 2 3 4
 5 6 7 8
 9 10 11 12
 13 14 15 16
```

# 4 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int n,i=0,j;
    cout << "Enter the number: ";
    cin>> n;
    while(i<n)
    {
        j=0;
        while(j<n)
        {
            if(j<=i)
            {
                cout << "*";
                j++;
            }
            else{
                cout << " ";
                j++;
            }
        }
        cout << endl;
           i++; 
    }
    return 0;
}
```
Input/Output
```
Enter the number: 5
*    
**   
***  
**** 
*****
```
# 5 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
    int i=0,n,j,k=1;
    cout << "Enter the number: ";
    cin>> n;
    while(i<n)
    {
        j=0;
        while(j<n)
        {
            if(j<=i)
            {
               cout << k;
            } 
            else{
                cout << " ";
            }
            j++;
        }
        cout << endl;
        k++;
        i++;
    }
    return 0;
}
```
Input/Output
```
Enter the number: 4
1   
22  
333 
4444
```
# 6 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
	int i=0,j,n,k=1;
	cout << "Enter the number: ";
	cin >> n;
	while(i<n)
	{
		j=0;
		while(j<n)
		{
			if(j<=i)
			{
				cout << " " << k;
				k++;
			}
			else
			{
				cout << " ";
			}
			j++;
		}
		cout << endl;
		i++;
	}
	return 0;
}
```
Input/Output
```
Enter the number: 4
 1   
 2 3  
 4 5 6 
 7 8 9 10
```

# 7 Pattern
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=1,j,k=1,m=1;
	cout << "Enter the number:";
	cin >> n;
	while(i<n)
	{
		j=1;
		while(j<n)
		{
		 if(j<=i)
			{
			cout << k;
			k++;
			j++;
		    }
			else
			{
				cout <<" " ;
				j++;
			}
		
		}
		cout << endl;
		i++;
		k=i;
	}	
		return 0;
}
```
Input/Output
```
Enter the number:5
1   
23  
345 
4567
```
# Pattern 8
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=1,j,m=0;
	cout << "Enter the number:" ;
	cin>> n;
	while(i<n)
	{
		j=1;
		while(j<n)
		{
			if(j<=i)
			{
				m=i-j+1;
				cout << m;
				j++;
			}
			else
			{
				cout << " ";
			    j++;
			}
		}
		cout << endl;
		i++;
	}
	return 0;
}
```
Input/Output
```
Enter the number:4
1  
21 
321
```
# Pattern 9
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=1,j;
	cout << "Enter the number:" ;
	cin>> n;
	while(i<n)
	{
		j=1;
		while(j<=i)
        {
            cout << (i-j+1);
            j++;
        }
        cout << endl;
        i++;
    }   
    return 0;
}
```
Input/Output
```
Enter the number:5
1
21
321
4321
```
# Pattern 10
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,i=0,k=1;
	cout<<"Enter the number of rows:" ;
	cin>> n;
    for(i=0;i<n;i++)
    {
    	for(int j=0;j<n;j++)
    	{
    		if(j<=i)
    		{
    			cout<< " "<< k;
    			k++;
			}
		else
		cout<< " ";	
		}
	   k=i;
		cout << endl;
	}
	return 0;
}
```
Input/Output
```
Enter the number of rows:3
 1  
 0 1 
 1 2 3
```
# Pattern 11
```cpp
#include<iostream>
using namespace std;
int main()
{
	int n,k=1;
	cout<< "enter the number of rows:";
	cin>> n;
	for(int i=1;i<=n;i++)
	{
		for(int j=1;j<=n;j++)
		{
			if(j<=i)
			{
				cout<<" "<<k;
				k--;
			}
			else
			cout<< " ";
		}
		k=i;
		cout<<endl;
	}
	return 0;
}
```
Input/Output
```
enter the number of rows:5
 1    
 1 0   
 2 1 0  
 3 2 1 0 
 4 3 2 1 0
```

