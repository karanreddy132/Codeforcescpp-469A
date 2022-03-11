# Codeforcescpp-469A
#include <bits/stdc++.h>

using namespace std;

int main(){
  int n,p,q,ele;
  set<int> a;
  cin >> n;

  cin >> p;
  for(int i=0;i<p;i++){
    cin >> ele;
    a.insert(ele);
  }

  cin >> q;
  for(int j=0;j<q;j++){
    cin >> ele;
    a.insert(ele);
  }

  if(a.size()==n){
    cout <<  "I become the guy.";
  }else{
    cout << "Oh, my keyboard!";
  }
  
  return 0;
}
