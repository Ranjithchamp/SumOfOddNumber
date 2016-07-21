# SumOfOddNumber
import java.util.Scanner;

public class SumOfOddNumber {

	/**
	 * @param args
	 */
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner qq = new Scanner(System.in);
		System.out.println("Range from:");
		int from=qq.nextInt();
		System.out.println("To:");
		int to=qq.nextInt();
		int sum=0;
		for(int i=from;i<=to;i++){
			if(i%2==1){
				sum=sum+i;
			}
		}
		System.out.println("Sum Of odd Number in Range is");
 System.out.println(sum);
	}

}
