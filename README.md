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
![描述](https://github.com/foolish1016/MoreView/blob/master/MoreBtn/Preview/7A33E4FC-D15F-4FA2-99D4-371FA7C8DEAA.png)
![描述](http://image.baidu.com/search/detailct=503316480&z=0&ipn=d&word=%E5%9B%BE%E7%89%87&hs=0&pn=0&spn=0&di=154981640220&pi=0&rn=1&tn=baiduimagedetail&is=0%2C0&ie=utf8&oe=utf8&cl=2&lm=-1&cs=415293130%2C2419074865&os=1556766946%2C250663840&simid=4145280632%2C499508967&adpicid=0&lpn=0&ln=30&fr=ala&fm=&sme=&cg=&bdtype=0&oriquery=&objurl=http%3A%2F%2Fimg.zcool.cn%2Fcommunity%2F0117e2571b8b246ac72538120dd8a4.jpg%401280w_1l_2o_100sh.jpg&fromurl=ippr_z2C%24qAzdH3FAzdH3Fooo_z%26e3Bzv55s_z%26e3Bv54_z%26e3BvgAzdH3Fo56hAzdH3FZMTYoNTMzMDQ%3D_z%26e3Bip4s&gsm=0&islist=&querylist=)
