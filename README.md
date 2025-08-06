package prog1;
import java.util.Scanner;

public class Prime {
	

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner sc = new Scanner(System.in);
int a =sc.nextInt();
int b = 0;
if(a<=1) {
	b=1;
}
for(int i=2;i<Math.sqrt(a);i++) {
	if(a%i==0) {
		b=1;
	}

}
if(b==0){
	System.out.println("is prime");
}else {
	System.out.println("not prime");
}
	}

}
