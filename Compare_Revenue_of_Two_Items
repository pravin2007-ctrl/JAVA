package hello;
import java.util.Scanner;
public class High_orders {

			public static void main(String[] args) {
				int [] productid = {5001,5002,5003,5004,5005};
				int [] productprice = {20,30,40,50,60};
				Scanner scan = new Scanner(System.in);
				System.out.println("CHOOSE THE PRODUCT 5001 to 5005:-");
				int product =scan.nextInt();
				System.out.println("SELECT QUANTITY:-");
				int qty=scan.nextInt();
				double price = 0;
				boolean valid = false;
				for(int i=0; i<productid.length; i++) 
				{
					if ( product==productid[i]) 
					{
						price = productprice[i];
						if ( product==5004 || product==5005 )
							price*=0.8;
						valid=true;
						break;
					}
				}
				if(valid) 
				{
					double totalbill = price*qty;
					System.out.println("Total Bill Amount: "+totalbill);
				}
				else
					System.out.println("Invalid Input.");
				scan.close();
			}
}
