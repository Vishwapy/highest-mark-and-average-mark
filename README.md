# highest-mark-and-average-mark
import java.util.Scanner;
public class Exercise1_5{
    public static void main(String[] args) {
	 Scanner input = new Scanner(System.in);
         double mark_avg;
         int result;
         int i;
         int s;
      
       s = input.nextInt();
    
      int[] arr = new int[s];   
      for(i=0;i<arr.length;i++)
	  {
	arr[i]=input.nextInt();
        }
  int max=arr[0];
float sum=0;
for(int j=0;j<arr.length;j++){
  sum=sum+arr[j];
  if(max < arr[j]){
    max=arr[j];
  }
}
 System.out.print(max+"\n"+(sum/arr.length));
 }
} 
