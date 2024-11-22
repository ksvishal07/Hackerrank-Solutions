import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static long sum(long n){
        //formula = n*(n+1)/2
        return (long) Math.pow((n*(n+1))/2, 2);
    }

    public static long powersum(long n){
        //formula = n(n+1)(2n+1)/6
        return (long) (n*(n+1)*(2*n+1))/6;
    }

    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int t = in.nextInt();
        for(int a0 = 0; a0 < t; a0++){
            int n = in.nextInt();
            System.out.println(Math.abs(sum(n) - powersum(n)));
        }
    }
}
