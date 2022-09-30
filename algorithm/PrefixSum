Prefix Sum
```sh
#include<bits/stdc++.h>
using namespace std;
int main(){
	freopen("LeDuyHao_prefixsum.inp","r",stdin);
	freopen("LeDuyHao_prefixsum.out","w",stdout);
	int n;
	cin>>n;
	int a[10000];
	for(int i=0;i<n;i++){
		cin>>a[i];
	}
	int prefix[n];
	for(int i=0;i<n;i++){
		if(i==0) prefix[0]=a[0];
		else prefix[i]=prefix[i-1]+a[i];
	}
	int t;
	cin>>t;
	while(t--){
		int l,r;
		cin>>l>>r;--l;--r;
		if(l==0) cout<<prefix[r]<<endl;
		else cout<<prefix[r]-prefix[l-1]<<endl;
	}
	return 0;
}
```
Vấn đề:

Đưa ra tổng của bất kì dãy con nào với O(1)
