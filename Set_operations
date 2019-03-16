
#include <stdio.h>

int main()
{
    int ch;
    printf("ENTER [1] FOR SET UNION\n");
    printf("ENTER [2] FOR SET INTERSECTION\n");
    printf("ENTER [3] FOR SET DIFFERENCE\n");
    printf("ENTER [4] FOR SYMMETRIC DIFFERNCE\n");
    do{
    int n,i,j,A[10],B[10],val,C[10],k=0,p,q,hash[10000]={0},hash1[10000]={0},D[10],h=0;
    printf("\nNOW, WHAT YOU WANT TO FIND:");


    scanf("%d",&n);
    printf("\n><-------------------------------><");

    ch=n;
    if(ch>4)
    printf("\n\n---NO OPERATION ON THIS CHOICE---");
    switch(ch)
    {
        case 1://for union
        printf("\n\nENTER THE SIZE OF SET A:");
        scanf("%d",&p);
        printf("\nENTER THE VALUES IN SET A:\n");
        for(i=0; i<p; i++)
            {
             scanf("%d",&A[i]);
             hash[A[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash[i]!=0)
           {
           C[k]=i;
           k++;
           }
         }

        printf("\nENTER THE SIZE OF SET B:");
        scanf("%d",&q);
        printf("\nENTER THE VALUES IN SET B:\n");
        for(i=0; i<q; i++)
            {
             scanf("%d",&B[i]);
             hash1[B[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash1[i]!=0)
           {
           D[h]=i;
           h++;
           }
         }

        printf("\nSET A: ");
        for(i=0;i<k;i++)
            printf("%d ",C[i]);
        printf("\n\nSET B: ");
        for(i=0;i<h;i++)
            printf("%d ",D[i]);
        for(i=0;i<k;i++)
        {
            for(j=0;j<k;j++)
            {
                if(C[i]==D[j])
                D[j]=-1;
            }
        }
        printf("\n\nUNION OF SET A AND B: ");
        for(i=0;i<k;i++)
            printf("%d ",C[i]);
        for(j=0;j<h;j++)
        {
            if(D[j]!=-1)
            printf("%d ",D[j]);
        }
        break;

        case 2://for intersection
        printf("\n\nENTER THE SIZE OF SET A:");
        scanf("%d",&p);
        printf("\nENTER THE VALUES IN SET A:\n");
        for(i=0; i<p; i++)
            {
             scanf("%d",&A[i]);
             hash[A[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash[i]!=0)
           {
           C[k]=i;
           k++;
           }
         }

        printf("\nENTER THE SIZE OF SET B:");
        scanf("%d",&q);
        printf("\nENTER THE VALUES IN SET B:\n");
        for(i=0; i<q; i++)
            {
             scanf("%d",&B[i]);
             hash1[B[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash1[i]!=0)
           {
           D[h]=i;
           h++;
           }
         }

        printf("\nSET A: ");
        for(i=0;i<k;i++)
            printf("%d ",C[i]);
        printf("\n\nSET B: ");
        for(i=0;i<h;i++)
            printf("%d ",D[i]);
        printf("\n\nINTERSECTION OF SET A AND B: ");
        for(i=0;i<k;i++)
        {
            for(j=0;j<h;j++)
            {
                if(C[i]==D[j])
                printf("%d ",C[i]);
            }
        }
        break;

        case 3://difference
        printf("\n\nENTER THE SIZE OF SET A:");
        scanf("%d",&p);
        printf("\nENTER THE VALUES IN SET A:\n");
        for(i=0; i<p; i++)
            {
             scanf("%d",&A[i]);
             hash[A[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash[i]!=0)
           {
           C[k]=i;
           k++;
           }
         }

        printf("\nENTER THE SIZE OF SET B:");
        scanf("%d",&q);
        printf("\nENTER THE VALUES IN SET B:\n");
        for(i=0; i<q; i++)
            {
             scanf("%d",&B[i]);
             hash1[B[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash1[i]!=0)
           {
           D[h]=i;
           h++;
           }
         }

        printf("\nSET A: ");
        for(i=0;i<k;i++)
            printf("%d ",C[i]);
        printf("\n\nSET B: ");
        for(i=0;i<h;i++)
            printf("%d ",D[i]);
        printf("\n\nDIFFERENCE A-B: ");
        for(i=0;i<k;i++)
        {
            int flag=0;
            for(j=0;j<h;j++)
            {
                if(C[i]!=D[j])
                flag++;
            }
            if(flag==h)
                printf("%d ",C[i]);
        }
        printf("\n\nDIFFERENCE B-A: ");
        for(i=0;i<h;i++)
        {
            int flag=0;
            for(j=0;j<k;j++)
            {
                if(D[i]!=C[j])
                flag++;
            }
            if(flag==k)
                printf("%d ",D[i]);
        }

        break;
        case 4://symmetric differene
            printf("\n\nENTER THE SIZE OF SET A:");
        scanf("%d",&p);
        printf("\nENTER THE VALUES IN SET A:\n");
        for(i=0; i<p; i++)
            {
             scanf("%d",&A[i]);
             hash[A[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash[i]!=0)
           {
           C[k]=i;
           k++;
           }
         }

        printf("\nENTER THE SIZE OF SET B:");
        scanf("%d",&q);
        printf("\nENTER THE VALUES IN SET B:\n");
        for(i=0; i<q; i++)
            {
             scanf("%d",&B[i]);
             hash1[B[i]]++;
            }
        for(i=0;i<10000;i++)
        {
          if(hash1[i]!=0)
           {
           D[h]=i;
           h++;
           }
         }

        printf("\nSET A: ");
        for(i=0;i<k;i++)
            printf("%d ",C[i]);
        printf("\n\nSET B: ");
        for(i=0;i<h;i++)
            printf("%d ",D[i]);
        printf("\n\nSYMMETRIC DIFFERENCE BETWEEN A AND B: ");
        for(i=0;i<k;i++)
        {
            int flag=0;
            for(j=0;j<h;j++)
            {
                if(C[i]!=D[j])
                flag++;
            }
            if(flag==h)
                printf("%d ",C[i]);
        }

        for(i=0;i<h;i++)
        {
            int flag=0;
            for(j=0;j<k;j++)
            {
                if(D[i]!=C[j])
                flag++;
            }
            if(flag==k)
                printf("%d ",D[i]);
        }



    }


    }while(ch!=0);

    return(0);

}
