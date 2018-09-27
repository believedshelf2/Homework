public class rocket3 {
	public static final int SCALE = 3;
// Create a static integer that won't be hardcoded
	public static void main(String[] args) {
	// Making strings and integers that will assign to the outer and nested for loops.
		drawCone();
		drawDivider();
		drawTopHalf();
		drawBottomHalf();
		drawDivider();
		drawBottomHalf();
		drawTopHalf();
		drawDivider();
		drawCone();
	}
// the first string is assigned as an integer for the outer for loop
// make a nested for loop that will print out the spaces, lines,slashes and stars
	public static void drawCone() {
		for (int line = 1; line <= (SCALE * 2 - 1); line++) {
			System.out.print(" ");
			for (int spaces = 1; spaces <= (SCALE * 2 - 1) - line; spaces++){
				System.out.print(" ");
			}
			for (int slashes = 1; slashes <= line; slashes++) {
				System.out.print("/");
			}
			System.out.print("**");
			for (int slashes = 1; slashes <= line; slashes++) {
				System.out.print("\\");
			}
			System.out.println(" ");
		}
	}
// use the drawDivide string to use for the next regular for loop that prints out "+", and "=*"
	public static void drawDivider() {
		System.out.print("+");
		for (int i = 1; i <= SCALE * 2; i++) {
			System.out.print("=*");
		}
		System.out.println("+");
	}
// use the drawTopHalf string to use it for the outer and nested for loops
	public static void drawTopHalf() {
		for (int line = 1; line <= SCALE; line++) {
			System.out.print("|");
			for (int repeat = 1; repeat <= 2; repeat++) {
				for (int dots = 1; dots <= SCALE - line; dots++) {
					System.out.print(".");
				}
				for (int points = 1; points <= line; points++) {
					System.out.print("/\\");
				}
				for (int dots = 1; dots <= SCALE - line; dots++) {
					System.out.print(".");
				}
			}
			System.out.println("|");
		}
	}
// next string will draw the bottom half of the rocket
	public static void drawBottomHalf() {
		for (int line = SCALE; line >= 1; line--) {
			System.out.print("|");
			for (int repeat = 1; repeat <= 2; repeat++) {
				for (int dots = 1; dots <= SCALE - line; dots++) {
					System.out.print(".");
				}
				for (int points = 1; points <= line; points++) {
					System.out.print("\\/");
				}
				for (int dots = 1; dots <= SCALE - line; dots++) {
					System.out.print(".");
				}
			}
			System.out.println("|");
		}
	}
}
