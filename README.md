public class armstrong{
public static void main(String[]args)
{
    for(int i=100;i<1000;i++)
    {
        int s=0;
        int a=i;
       for(int j=0;j<3;j++)
       {
        int r=a%10;
        s=s+r*r*r;
        a=a/10;
        }
        if(s==i)
        {
            for(int k=2;k<i/2+1;k++)
            {
                int p=i%k;
                if(p!=0)
                {
                    System.out.println(+i);
                    break;
   
                }
        }
    }
}
}
}
