import java.util.*;
import java.lang.*;
import java.io.*;

class Ideone
{
	public static void main (String[] args) throws java.lang.Exception{
		Scanner in=new Scanner(System.in);
		int n=in.nextInt();
		int[] arr=new int[n];
		for(int i=0;i<n;i++){
			arr[i]=in.nextInt();
		}
		Hashtable<Integer,Integer> map=new Hashtable<Integer,Integer>();
		for(int i=0;i<n;i++){
			if(map.containsKey(arr[i])==true){
				if(map.get(arr[i])==1){
					System.out.println(arr[i]);
					map.remove(arr[i]);
					map.put(arr[i],2);
				}
			}
			else{
				map.put(arr[i],1);
			}
		}
	}
}
