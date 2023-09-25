# Code_C
Những chương trình ngôn ngữ C do chính Mai Quốc Đại coding
____________________________________________________________
#include <stdio.h>
#include <math.h>
main (){
	while(1){
	float a,b,c,d,e,f,g,denta;
	printf("Ta co phuong trinh: ax^2+bx+c\n");
	printf("Nhap a: ");
	scanf("%f", &a);
	printf("Nhap b: ");
	scanf("%f", &b);
	printf("Nhap c: ");
	scanf("%f", &c);
	denta = b*b - 4*a*c ;
	d =-b/2*a;
	e = (-b+ sqrt(denta))/2*a;
	f = (-b- sqrt(denta))/2*a;
	g = -c/b;
	if(a==0)
		printf("Nghiem cua phuong trinh la: %.2f",g);
	else if(denta<0){
		printf("Phuong trinh vo nghiem!!");
	}
	else if(denta==0){
		printf("Phuong trinh co nghiem kep X1=X2=%.2f",d);
	}
	else {
		printf("Phuong trinh co hai nghiem X1=%.2f X2=%.2f",e,f);
	}
	printf("\n\n");
}
}
