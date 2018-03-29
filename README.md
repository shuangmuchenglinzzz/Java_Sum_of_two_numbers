# Java_Sum_of_two_numbers
import java.util.*;

public class Liangshuzhihe {
		public static void main(String[] args){
	    System.out.println("请输入数组中元素个数：");
		Scanner scanner=new Scanner(System.in);
		int n=scanner.nextInt();	
	    int num[]=new int[n];
	    System.out.println("请输入数组中"+n+"个元素：");
	    int target=0;
	        for(int i=0;i<n;i++)
	        {
	        num[i]=scanner.nextInt();
	        }
	        System.out.println("请输入两数之和：");  
	        target=scanner.nextInt();
	        for(int i=0;i<n-1;i++){
	        	for(int j=i+1;j<n;j++){
	        		if(num[i]+num[j]==target)
	        			System.out.println("两数下标为："+i+" "+j);
	        	}
	        }  		
	    }
	}
