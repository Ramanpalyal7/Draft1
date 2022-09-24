#include<iostream>
#include<cmath>
using namespace std;
int main()
{   int n;
    cout<<"Select what do you want to do"<<endl;
    cout<<"1 for Area of Triangle"<<endl;
    cout<<"2 for Perimeter of Rectangle"<<endl;
    cout<<"3 for Sum of n number "<<endl;
    cout<<"4 for nth term of A.P"<<endl;
    cout<<"5 for Speed "<<endl;
    cout<<"6 for Simple Interest"<<endl;
    cout<<"7 Volume of Cylinder"<<endl;
    cout<<"8 for Distance between two points"<<endl;
    cout<<"9 for Net Salary"<<endl;
    cout<<"10 root of quadratic equation"<<endl;
    cin>>n;
    if(n=1)
    {  int b,h;
    float a;
      a=(b*h)/2;
      cout<<"What is the value of Base and Height";
      cin>>b>>h;
      cout<<"The Area of Triangle is "<<a<<endl;
      
    }
    else if(n=2)
    { 
        int l,b;
    float p;
        p=2*(l+b);
        cout<<"What is the length and breadth of Rectangle";
        cin>>l>>b;
        cout<<"The Perimeter of Rectangle is"<<p<<endl;
        
    }

    else if(n=3)
    {
            int n;
    float s;
      s=n*(n+1)/2;
      cout<<"Write the number of terms";
      cin>>n;
      cout<<"The Sum of n terms is"<<s<<endl;
     
    }
   
    else if(n=4)
    {
         int a,t,n,d;
        t=a+(n-1)*d;
        cout<<"Write the First term of A.P"<<endl;
        cin>>a;
        cout<<"Write the total number of terms with common difference";
        cin>>n>>d;
        cout<<"Therefore the nth term of A.P is "<<t<<endl;
    }
    
    else if(n=5)
    { 
        int v,u,a;
    float s;
        s=(v*v)-(u*u)/(2*a);
        cout<<"What is the intial velocity and final velocity of vehicle with difference it cover"<<endl;
        cin>>u>>v>>a;
        cout<<"The Speed of Vehicle is "<<s<<endl;
        
    }
   
    else if(n=6)
    {
         int p;
    float t,r,s;
        s=(p*t*r)/100;
        cout<<"What is the Principle Amount you get and how much rate of interest over it with time period";
        cin>>s>>r>>t;
        cout<<"The Simple Interest is "<<s<<endl;
    }
    
    else if(n=7)
    {
        int r,h;
    float v;
        v=3.14*r*r*h;
        cout<<"Enter the radius and height of Cylinder";
        cin>>r>>h;
        cout<<"The Volume of Cylinder"<<v<<endl;

    }
    
    else if(n=8)
    {
        int x1,x2,y1,y2;
    float d;
     d=sqrt((x2-x1)*(x2-x1)+(y2-y1)*(y2-y1));
     cout<<"Write the value of x1,x2 and y1,y2"<<endl;
     cin>>x1>>x2>>y1>>y2;
     cout<<"The Distance between two points is "<<d<<endl;

    }
    
    else if(n=9)
    {
        float net ,b,a,d;
        net=b+(b*a/100)-(b*d/100);
        cout<<"What is your basic pay and write the allowance you get and also deduction on your salary"<<endl;
        cin>>b>>a>>d;
        cout<<"You have Net SAlARY of "<<net<<endl;

    }
   
    else 
    {
         int b,a,c;
    float r1,r2;
        r1=(-b+sqrt(b*b-(4*a*c))/(2*a));
        r2=(-b-sqrt(b*b-(4*a*c))/(2*a));
        cout<<"Write the value of a,b,c"<<endl;
        cin>>a>>b>>c;
        cout<<"The Roots are "<<r1<<"  "<<r2;
      return 0;
    }
    

    

}
