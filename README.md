# write-a-java-program-using-Queue-interface-and-add-6integers-and-remove-2integers-print-using-Stack
import java.io.*;
import java.util.*;

public class QueueInterface
{
	static void stack_push(Stack<Integer> stack)
	{
		System.out.println("Adding Elements:");
		
		for(int i = 0; i < 6; i++)
		{
			stack.push(i);
			System.out.println(i);
		}
	}
	
	static void stack_pop(Stack<Integer> stack)
	{
		System.out.println("Removing Operation:");

		for(int i = 0; i < 2; i++)
		{
			Integer y = (Integer) stack.pop();
			System.out.println(y);
		}
	}

	public static void main (String[] args)
	{
		Stack<Integer> stack = new Stack<Integer>();

		stack_push(stack);
		stack_pop(stack);
	}
}
