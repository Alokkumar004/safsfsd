#include <stdio.h>

int main()
{
    int i,j,m,n;
    printf("\n Enter the size of array:");
    scanf("%d",&m);
    int a[m];
    printf("\n Enter the element of array:{");
    for(i=0;i<m;i++){
        scanf("%d",&a[i]);
    }
    printf("}");
    printf("\n Enter the size of array:");
    scanf("%d",&n);
    int b[n];
    printf("\n Enter the element of array:{");
    for(i=0;i<n;i++){
        scanf("%d",&b[i]);
    }
    printf("}");
    printf("\n Cartesian Product is :{");
    for(i=0;i<m;i++){
        for(j=0;j<n;j++){
            printf("(%d,%d),",a[i],b[j]);
        }
    }
    printf("}");
    
    
    return 0;
}
