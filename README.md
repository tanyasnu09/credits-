# credits-
##This is a code where a candidate can give some test cases that have some constraints where they give the no of credits and according to that the credits  are termed as underload,overload and normal credits

 #include <stdio.h>


int main(void) {
    int n;
    printf("enter test cases' number");
    scanf("%d",&n);
    int ar[n];
    if(n<=100 &&n>=1)
    {
    for(int i=0;i<n;i++){
        scanf("%d",&ar[i]);
    }
    for(int i=0;i<n;i++){
        if (ar[i]<0 &&ar [i]>100){
            printf("please enter values more than or equal to  but less than");
        }
        if(ar[i]>65){
            printf("Overload\n");
        }else if(ar[i]<35&&ar[i]>0){
            printf("Underload\n");
        }else if (ar[i]>35 && ar[i]<65 )
        {
            printf("Normal\n");
        }



    else if(ar[i]<0)



    {

        printf("enter valid credits ");
        scanf("%d",&ar[i]);
        if (ar[i]<0 &&ar [i]>100){
            printf("please enter values more than or equal to  but less than");
        }
        if(ar[i]>65){
            printf("Overload\n");
        }else if(ar[i]<35&&ar[i]>0){
            printf("Underload\n");
        }else if (ar[i]>35 && ar[i]<65 )
        {
            printf("Normal\n");
        }




    }
    continue;
    }

	return 0;
}
}
