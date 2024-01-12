public class Fibonaccinumbers 
{
    public static void main(String[] args)
    {
        int i=1,count=10, Num1=0,Num2=1;
        System.out.print(Num1+""+Num2);
        for(i=2;i<count;++i)
           {
               int sumofPrev2=Num1+Num2;
               Num1=Num2;
               System.out.print(""+sumofPrev2);
               Num2=sumofPrev2;
               i++;
           }
    }
}
