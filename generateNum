public class generateNumbers {

    public static void main(String[] args){

            int min = 0;
            int max = 20;
            int a = min + (int) (Math.random()*max);
            int b = min + (int) (Math.random()*max);
            int end = close10(a, b);
            System.out.printf("close10(%d, %d) ---> %d ",a, b, end);


    }
    public static int close10(int a, int b){
        int result = 0;
        int diff1 = 10 - a;
        int diff2 = 10 - b;
        if(Math.abs(diff1) < Math.abs(diff2)){
            result = a;
        }
        else if(Math.abs(diff1) > Math.abs(diff2)){
            result = b;
        }
        else{
            result = 0;
        }
        return result;
    }
}
