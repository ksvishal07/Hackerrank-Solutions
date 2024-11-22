import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    // public static long fib(long n){
    //     if(n < 1){
    //         return n;
    //     }
    //     if(n == 1){
    //         return 2;
    //     }
    //     return ((4*fib(n - 1)) + fib(n - 2));
    // }

    static long find_sum(long N)
    {
        long one = 2;
        long two = 8;
        long temp = 0;
        long sum = 0;
        while(one < N)
        {
            sum += one;
            temp = two;
            two = 4 * two + one;
            one = temp;
         }
         return sum;
    }

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int t = in.nextInt();
        for(int a0 = 0; a0 < t; a0++){
            long n = in.nextLong();
            // long rec = n/3, sum = 0;
            // while(rec-- > 0){
            //     sum += fib(rec);
            // }
            System.out.println(find_sum(n));
        }
    }
}
