# my-subscriptions-code
#include<bits/stdc++.h>
using namespace std;

int main(){

vector<string>s={"TOI","Hindu","ET","BM","HT"};

vector<double>prices={26,20.5,34,10.5,18};

set<pair<string,string>>p;

int n;
cin>>n;

for(int i=0;i<5;i++){
  int value = n-prices[i];
   for(int j=0;j<5;j++){
    if prices[j]<=value){
      p.insert(make_pair(s[i],s[j]);
      }
     }
    }
  for(auto it=p.begin();it!=p.end();it++){
   cout<<it->first<<""<<it->second<<endl;
  }
  
  return 0;
  }
