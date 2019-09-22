# min_max


package elclipse;

public class min_max {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a[]= {1,3,5,2,7,8,10,0,-1,-2,-8};
		int max=Integer.MIN_VALUE;
		int min=Integer.MAX_VALUE;
		
		
		for(int i=0;i<a.length;i++) {
			if(max<a[i]) {                            //comparing element
				max=a[i];
			}
			if(min>a[i]) {
				min=a[i];
			}
		}
		System.out.print(max + "  "+ min);  ///print max and min element in the array

	}

}
///time complexity is o(n^2)
