import java.util.Scanner;

public class MovieDriver
 {
	
	public static void main(String[] args)
	 {
// Create a new object of type Scanner that reads from the keyboard
		Scanner keyboard = new Scanner(System.in);
		
		System.out.println("Please enter the title of the movie: ");
		//Prompt the user to enter the title of a movie. Set the title in the movie object
		String movieTitle = keyboard.nextLine();
		//ask for rating
		System.out.println("Please enter the rating of the movie: ");
		//Prompt the user to enter the movie’s rating. Set the rating in the movie object
		String movieRating = keyboard.nextLine();
			// ask for ticket sold	
		System.out.println("Please enter the number of tickets sold for this movie: ");
		// Prompt the user to enter the number of tickets sold at a (unnamed) theater
		int ticketSold = keyboard.nextInt();
		//read and discard the line feed.;where keyboard is an object of the scanner class.
		keyboard.nextLine();
		// Print out the information using the movie’s toString method
		System.out.println(movieTitle+"("+ movieRating+")"+(": Ticket Sold: ")+ticketSold);
		//Ask the user if they want to continue
	    System.out.println("Do you want to enter another? (y or n): ");
		
		String another = keyboard.nextLine();
		//loop that reads input for multiple movies
		while(another.equals("y"))
				{

					System.out.println("Please enter the title of the movie: ");
					String movieTitle1 = keyboard.nextLine();
					System.out.println("Please enter the rating of the movie: ");
					
					String movieRating1 = keyboard.nextLine();
					System.out.println("Please enter the number of tickets sold for this movie: ");
					
					int ticketSold1  = keyboard.nextInt();
					keyboard.nextLine();
					System.out.println(movieTitle1+"("+ movieRating1+")"+(": Ticket Sold: ")+ticketSold1);
					System.out.println("Do you want to enter another? (y or n): ");
					//continue the loop if the user types the correct response

					another=keyboard.nextLine();

					}
					System.out.println("Goodbye");
	}
}
