import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        List<Long> list = new ArrayList<>();
        list.add(2l);
        for(long i = 3; i <= 1000000; i+=2){
            boolean isprime = true;

            for(long p : list){
                if(p*p > i){
                    break;
                }
                if(i%p == 0){
                    isprime = false;
                    break;
                }
            }
            if(isprime){
                list.add(i);
            }
        }

        Scanner in = new Scanner(System.in);
        int t = in.nextInt();
        for(int a0 = 0; a0 < t; a0++){
            int n = in.nextInt();
            System.out.println(list.get(n-1));
        }
        in.close();
    }
}
