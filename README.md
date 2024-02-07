# Java
class MaximumNumber
{
    public static void main(String[] args)
    {
        int a=10, b=12, c=5, max;
        max = (a>b)? (a>c?a:c) : (b>c? b:c);
        System.out.println("maximum value:"+max);
    }
}
