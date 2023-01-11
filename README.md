# java-loops
import java.util.*;
import java.io.*;
import java.lang.Math;

class Solution{
    public static void main(String []argh){
        Scanner in = new Scanner(System.in);
        int t=in.nextInt();
        for(int i=0;i<t;i++){
            int a = in.nextInt();
            int b = in.nextInt();
            int n = in.nextInt();
            double s = a;
            for(int j=0;j<n;j++)
            {
                s=s+(Math.pow(2,j))*b;
                int k=(int)s;
                System.out.print(k+" ");
            }
            System.out.println();
            
        }
        
        in.close();
    }
}
