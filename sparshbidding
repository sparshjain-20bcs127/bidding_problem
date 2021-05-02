#include <stdio.h>
int main() {
    char bidders[] = {'A','B','C','D','E','F'};
    int bv[6];
    int valuation[6];

    for(int i = 0; i < 6 ; i++){
        printf("Bidder %c , Please enter your bid value ==>  ",bidders[i]);
        scanf("%d",&bv[i]);
        printf("Bidder %c , Please enter your valuation ==>  ",bidders[i]);
        scanf("%d",&valuation[i]);

    }
    int hbv = bv[0];
    
    int num1 = 0 ;
    int num2 = 0 ;
    
    for(int i = 0; i < 6 ; i++){
        if(bv[i]>hbv){
        hbv = bv[i];
        num1 = i;
        }
    }
    
    int shbv = bv[0];
    for(int i = 1 ; i < 6 ; i++){
          if(bv[i]<hbv && bv[i]>shbv) {
            shbv = bv[i];
            num2 = i;
        }
    }  
printf("The winning bid value is %d\n",hbv);  
printf("Winner is %c\n",bidders[num1]);
printf("Payment to be done  %d\n", shbv);
printf("Valuation : %d \n",valuation[num1]);
printf("Utility amount : %d",valuation[num1]-shbv);

return 0;
}

