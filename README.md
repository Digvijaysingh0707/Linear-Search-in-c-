# Linear-Search-in-c-
#include <iostream>

using namespace std;
int main(){
    int a[5];
    int n;
    int i;
    cin>>n;

    for(int i =0;i<n;i++){
        cin>>a[i];
    }

        int key;
        cin>>key;

        for( i=0;i<n;i++){
            if(key==a[i]){
                cout<<"Found at index "<<i<<endl;
                break;
        }

        }
        if(i==n){
            cout<<"The"<<key<<"is not present";
        }

        return 0;
    }

