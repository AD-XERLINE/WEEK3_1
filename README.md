# WEEK3_1
โปรแกรมรายสัปดาห์ที่ 3 อันที่ 1

    #include<stdio.h>


    int main() {

    int a;
    int b;
    int c;


    printf("ENTER 3 NUMBER SUCH AS(6 3 8) : ");
    scanf("%d %d %d",&a,&b,&c);

    if (a>b && a>c){
       printf("The most valuable number: %d", a);
    }
    else if(b>a && b>c){
	    printf("The most valuable number: %d", b);
    }
    else if(c>a && c>b){
	    printf("The most valuable number: %d", c);
    }
       return 0;
    }
