using System;
using System.Collections.Generic;
					
public class Program
{
	public static void print(ref List<int>lst){
		for(int j=0;j < lst.Count ;j++){
		   Console.WriteLine(lst[j]);
		}
		return;
	}
	
	public static void Main()
	{
		List<int>lst = new List<int>{1,9,9};
		
		for(int i= lst.Count -1;i>=0;i--){
			if(lst[i] == 9){
				lst[i] = 0;
			}
			else{
				lst[i] = lst[i] + 1;
				print(ref lst);		
				return;
			}
		}
		
		lst.Add(0);
		
		lst.Insert(0,1);
		
		print(ref lst);
		
		return;
	}
}
