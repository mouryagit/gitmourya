# gitmourya hello!!!!!!!!!!!!!!
package mourya;

public class codeblock {

	public static void main(String[] args) {
		
		boolean gameOver=true;
		int score=10000;
		int levelCompleted=8;
		int bonus=200;
		
		if(gameOver) {
			int finalScore = score + (levelCompleted*bonus);
			System.out.println("your final score was " +  finalScore);
		}
		
		 
		 score=800;
		 levelCompleted=5;
		 bonus=100;
			if(gameOver) {
				int finalScore = score + (levelCompleted*bonus);
				finalScore %= 1000;
				System.out.println("your final score was " +  finalScore);
			}
		 
		 

	}

}

