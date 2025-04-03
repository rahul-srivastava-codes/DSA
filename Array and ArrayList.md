storing a roll number 
int a = 4;
string a second roll number 
int b = 5;
now asking you to store 100 roll number
will not it be cumbersome, is it hard , cumbersome 
or prefer something which can store so many elements
Solution is array
syntax of array is 
datatype[] variable_name = new datatype[size];

Example 
int[] roll_no = new int[5];
int[] roll_no = {1,2,3,4,5};
in java or strong language then array will contain only same type of element
which possess same type of data element.

int[] roll_no ; //declaration of array in stack as roll_no executed during compile time
roll_no                  =  new int[]; //initialization now memory is allocated to object in heap executed during run time refers to dynamic memory allocation
(left)reference varibale = object(right)

1) array objects are in heap
2) heap object are not continuous
3) Array objects are not continuous
may not be continuous as it depends on JVM


Index of an array which help us in getting the position of the array
example - arr[0] -> gives me the value present in array at index 0.

What is new?
New is used to create an object. 
{} also allocates memory in heap


2D array
int[][] arr = new int[rows][col]
it is mandatory to give rows

using for loop in 2D array
for(int i=0; i<arr.length;i++){
  for(int j = 0; j<arr[i].length; j++){
  nums[i][j] = sc.nextInt();
  }
}

For dynamic array we prefer arraylist, defined as
ArrayList<Integer> list = new ArrayList<Integer>();
