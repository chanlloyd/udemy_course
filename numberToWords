public class LloydLearnsJava{

     public static void main(String []args){
        //System.out.println(getDigitCount(11));
        //System.out.println(reverse(11));
        numberToWords(0);
     }
    
    public static void numberToWords (int number) {
        if (number == 0) {
            System.out.println("Zero");
            }
        else if (number >0) {
            int digit = 0;
            int newNum = reverse(number);
            int digitCount = getDigitCount(number);
            //System.out.println("newNum is "+newNum);
            while (digitCount >0){
                digit = newNum % 10;
                //System.out.println("digit is "+digit);
                switch (digit){
                    case 0: System.out.println ("Zero");
                    break;
                    case 1: System.out.println ("One");
                    break;
                    case 2: System.out.println ("Two");
                    break;
                    case 3: System.out.println ("Three");
                    break;
                    case 4: System.out.println ("Four");
                    break;
                    case 5: System.out.println ("Five");
                    break;
                    case 6: System.out.println ("Six");
                    break;
                    case 7: System.out.println ("Seven");
                    break;
                    case 8: System.out.println ("Eight");
                    break;
                    case 9: System.out.println ("Nine");
                    break;
                }
                newNum = newNum / 10;
                digitCount--;
            }
        }else {
            System.out.println("Invalid Value");
        }
    }
     
    public static int reverse (int number){
        if (number == 0) {
            return 0;
        }
        int newNum = number;
        int sum = 0;
        int digit = 0;
        int digitCount = getDigitCount(Math.abs(number));
        while (digitCount >0){
            digit = newNum % 10;
            //System.out.println("digit is "+digit);
            sum+= digit * (Math.pow (10, digitCount-1));
            newNum = newNum / 10;
            digitCount--;
        }
        return sum;
    }
     
    public static int getDigitCount (int number){
        if (number == 0){
            return 1;
        }
        if (number >0) {
            int digitCount = 0;
            int digit = 0;
            int newNum = number;
            while (newNum >0){
                digit = newNum % 10;
                newNum = newNum / 10;   
                digitCount ++;
            }
            return digitCount;
        }
        return -1;
    } 
}
