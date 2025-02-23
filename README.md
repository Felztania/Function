# Function
#include <bits/stdc++.h>
using namespace std;
void f(int t){
  int y,a,b,c,d,e;
  y=t*t+2*t+3;
  a=y+t;
  b=a*a+2*a+3;
  c=y*y+2*y+3;
  d=b+c;
  e=d*d+2*d+3;
  cout<<e;
}
int main(){
  int t;
  cin>>t;
  f(t);
}
