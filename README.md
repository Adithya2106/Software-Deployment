# Software-Deployment
// Author : Adithya
import java.util.Scanner;
public class LetterGrade {
    public static void main(String[] args) {
        String letterGrade;

        System.out.println("Please enter your grade : ");
        Scanner scan = new Scanner(System.in);

        int grade = scan.nextInt();

        // Check for A+, A, B+, B, C+, C, D+, D, and F
        if (grade >= 95) {
            letterGrade = "A+";
        } else if (grade >= 90) {
            letterGrade = "A";
        } else if (grade >= 85) {
            letterGrade = "B+";
        } else if (grade >= 80) {
            letterGrade = "B";
        } else if (grade >= 75) {
            letterGrade = "C+";
        } else if (grade >= 70) {
            letterGrade = "C";
        } else if (grade >= 65) {
            letterGrade = "D+";
        } else if (grade >= 60) {
            letterGrade = "D";
        } else {
            letterGrade = "F";
        }

        System.out.println("The Final Grade is : " + letterGrade);
    }
}
