# NKU-5
大于m的k个素数

#include<stdio.h>
void fun(int m,int k,int xx[]){
	int i,h=0,l;
		while(h<k){
			int j=0;
			m=m+1;
			for(l=2;l<=m;l++){
				if(m%l==0)
				j++;
			}
			if(j==1){
				xx[h]=m;
				h++;
			}
		}	
	}
	
int main(){
	int a[100]={0};
	int b=20;
	int c=1;
	int i=0;
	fun(c,b,a);
	for(i=0;i<b;i++)
	printf("%d\n",a[i]);
}
![描述](https://github.com/foolish1016/MoreView/blob/master/MoreBtn/Preview/7A33E4FC-D15F-4FA2-99D4-371FA7C8DEAA.png) //在.md文件中添加图片
## 123
### 123
#### 123
![描述](http://25.io/mou/Mou_128.png)
