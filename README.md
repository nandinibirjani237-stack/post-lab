# post-lab
# task 1
#include <stdio.h>

int main() {
int rows=8;
    for(int i=0;i<rows;i++){
        for(int j=0;j<i;j++){
            if(j%4==0 ){
                printf("0");
            }else{
                printf("1");
            }
        }
        printf("\n");
    }
   
    return 0;
}
# task 2
#include <stdio.h>

int main() {
int rows=5;
    for(int i=1;i<=rows;i++){
        for(int j=1;j<=i;j++){
            if(j%2==0 ){
                printf("0");
            }else{
                printf("1");
            }
        }
        printf("\n");
    }
    # task 3
    #include <stdio.h>

int main() {
int rows=5;
    for(int i=1;i<=rows;i++){
        for(int j=1;j<=i;j++){
            if(j%2==0 ){
                printf("0");
            }else{
                printf("1");
            }
        }
        printf("\n");
    }
   
    return 0;
}

# task 3
#include <stdio.h>
int main() {
int A[3][3] , B[3][3],Result[3][3];
    printf("enter the values for first matrix");
for(int i=0;i<3;i++){
    for(int j=0;j<3;j++){
        scanf("%d",&A[i][j]);
    }}  
     printf("enter the values for second matrix");
    for(int i=0;i<3;i++){
    for(int j=0;j<3;j++){
        scanf("%d",&B[i][j]);
    }}  
    
    for(int i=0;i<3;i++){
    for(int j=0;j<3;j++){
        Result[i][j]=A[i][j]+B[i][j];
    }}  
    printf("\n first matrix \n");
for(int i=0;i<3;i++){
    for(int j=0;j<3;j++){
        printf("%d ",A[i][j]);
    }
    printf("\n");
}    
    printf("\n second matrix \n");
    for(int i=0;i<3;i++){
    for(int j=0;j<3;j++){
        printf("%d ",B[i][j]);
    }
    printf("\n");
}    
    printf("\n resulting sum matrix \n");
    for(int i=0;i<3;i++){
    for(int j=0;j<3;j++){
        printf("%d ",Result[i][j]);
    }
    printf("\n");
}    
    return 0;
}

# task 4
#include <stdio.h>
int main() {
int arr[4][2];
    printf("enter the mid and final marks");
    for(int i=0;i<4;i++){
for(int j =0;j<2;j++){
    scanf("%d\t",&arr[i][j]);
}     
    }
    printf("\n mid and final marks :\n ");
    for(int i=0;i<4;i++){
for(int j =0;j<2;j++){
    printf("%d\t",arr[i][j]);
}   
        printf("\n");
    }
    printf("total marks\t");
    for(int i=0;i<4;i++){
        int sum=0;
for(int j =0;j<2;j++){
    sum+=arr[i][j];
   
}   
         printf("%d\t",sum);
        printf("\n");
    }
     
    int highest=arr[0][0];
for(int i=0;i<4;i++){
       
if(highest<arr[i][0]){
    highest=arr[i][0];
}
}
    printf("\n highest marks %d ",highest);
    
    int highestf=arr[0][1];
for(int i=0;i<4;i++){
if(highestf<arr[i][1]){
    highestf=arr[i][1];
}
}
    printf("\n highest marks %d",highestf);
int lowest =arr[0][0];
    for(int i=0;i<4;i++){
        if(lowest>arr[i][0]){
            lowest=arr[i][0];
        }
    }
    printf("\nlowest marks from mid %d ",lowest);
 int lowestf =arr[0][1];
    for(int i=0;i<4;i++){
        int lowestf =arr[0][1];
        if(lowestf>arr[i][1]){
            lowestf=arr[i][1];
        }
    }
    printf("\nlowest marks from final %d ",lowestf);
    
    int lowesta=arr[0][0];
    for(int i=0;i<4;i++){
        for(int j=0;j<2;j++){
            if(lowesta>arr[i][j]){
                lowesta=arr[i][j];
            }
        }
    }
    printf("\nlowest marks overall across both %d",lowesta);
    
    int highesta=arr[0][0];
    for(int i=0;i<4;i++){
        for(int j=0;j<2;j++){
            if(highesta<arr[i][j]){
                highesta=arr[i][j];
                
            }
        }
    }
    printf("\nhighest marks overall across both %d",highesta);

    float mid_avg=0.0;
    int mid_sum=0;
    for(int i=0;i<4;i++){
        mid_sum+=arr[i][0];
    }
    mid_avg=mid_sum/4.0;
    printf("\n average of mid %f\n",mid_avg);
    float final_avg=0.0;
    int final_sum=0;
    for(int i=0;i<4;i++){
        final_sum+=arr[i][1];
    }
    final_avg=final_sum/4.0;
    printf("final average %f ",final_avg);
    
    return 0;
}

   
    return 0;
}
