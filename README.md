// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;
int main() {
    // Write C++ code here
    int a;
    int k=0;
    cout<<"Enter a number ";
    cin>>a;
    int i =2;
    while(i>0){
         int c=0;
        for(int j=2;j<i;j++){
            if(i%j==0)
            c++;
        }
        if(c==0){
        cout<<i;
        cout<<"\n";
        k++;
        }
          if(k==a){
            break;
        }
        
      
        i++;
    }

    return 0;
}












