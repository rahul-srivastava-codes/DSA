Binary search -> Only Valid when array are sorted in ascending or descending order
Linear search max comparison = N
Binary search max comparison = N/2^k
1) find middle element
2) then compare and move start/end depending on condition

Code for Binary search algorithm

```public class Binary_search {
	public static int binarysearch(int[] arr, int target) {
		int start = 0, end = arr.length-1;
		while(start<=end) {
			int mid = start + (end - start)/2;
			if(arr[mid]<target) {
				start = mid + 1;
			}else if (arr[mid]>target) {
				end = mid-1;
			}else {
				return mid;
			}
		}
		return -1;
	}

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int[] num = {1,2,3,4,5,6,7,8,9,10,11,12,13,45};
		System.out.println("Index is " + binarysearch(num,4));

	}

}
```
