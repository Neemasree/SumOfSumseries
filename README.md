#include<bits/stdc++.h>
using namespace std;
static long SumofSumseries(int n){
    long sum=0L;
    for(int i=0;i<=n;i++){
        sum=sum+(i*(i+1)/2);
    }
    return sum;
}
int main(){
    int n=5;
    cout<<SumofSumseries(n);
}
