import java.util.*;
import java.io.*;

public class Solution{
    public static final int MAX = 1000000;
    public static void main(String args[]) throws IOException {
        List<Integer> list = new ArrayList<>();
        list.add(2);

        for(int i = 3; i <= MAX; i+=2){
            boolean isPrime = true;

            for(int p : list){
                if(p*p > i){
                    break;
                }
                if(i%p == 0){
                    isPrime = false;
                    break;
                }
            }
            if(isPrime){
                list.add(i);
            }
        }

        Map<Integer, Long> sums = new HashMap<>();
        long sum = 0;
        for (int p : list){
            sum += p;
            sums.put(p, sum);
        }

        BufferedReader br = new BufferedReader(new
        InputStreamReader(System.in));
        int t = Integer.parseInt(br.readLine());
        
        while(t-- > 0){
            int x = Integer.parseInt(br.readLine());
            // boolean find = map.containsKey(x);

            while(sums.containsKey(x) == false){
                --x;
            }

            if(sums.containsKey(x)){
                long value = sums.get(x);
                System.out.println(value);
            }
        }
         //System.out.println(Arrays.asList(sums));
    }
}
