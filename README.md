Codes
=====
#include<bits/stdc++.h>
#include<algorithm>
using namespace std;
int main()
{
    int T,N,a;
    int arr[100001];
    cin>>T;
    while(T--){
        for(int i=0;i<100001;i++)
         arr[i]=0;
           int cnt=0;
        cin>>N;
        for(int i=0;i<N;i++){
            cin>>a;
            if(arr[a]==0){
                cnt++;
               arr[a]=1;
            }
        }
        cout<<cnt<<endl;
    }
    return 0;
}
 
