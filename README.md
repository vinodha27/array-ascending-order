# array-ascending-order
int[] a={4,3,8,2,0,5,17};
        for(int i=0;i<=a.length-1;i++)
        {
            for(int j=i+1;j<=a.length-1;j++)
            {
                if(a[i]>a[j])
                {
                    int t=a[i];
                    a[i]=a[j];
                    a[j]=t;
                }
            }
              System.out.println(a[i]);
        }
