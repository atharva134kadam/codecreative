#include <iostream>
using namespace std;
int main() {
    int s1,s2,s3;
    
    cout<<"enter 3 sides of traingle"endl;
    cin>>s1>>s2>>s3;
    
    s1=s2+s3;
    s2=s1+s3;
    s3=s1+s2;
    
    if(s1=s2+s3 || s2=s1+s3 || s3=s1+s2)
    {
        cout<<"valid traingle"endl;
    }
    else
    {
        cout<<"not valid"<<endl;
    }
    return 0;
}
