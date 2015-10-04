import java.util.Scanner;

public class RésolutionEquation2degre {
	public static void main(String [] args) {
	double a, b, c, discriminant, x1, x2, solusi0;
	Scanner scan = new Scanner(System.in);
	System.out.println("Le polynome est de la forme aX^2+bX+c=0."); // donne la forme du polynome.
	System.out.println("Quelle valeur de a?"); 
	a = scan.nextDouble();
	System.out.println("Quelle valeur de b?"); 
	b = scan.nextDouble();
	System.out.println("Quelle valeur de c?"); 
	c = scan.nextDouble();
	discriminant = Math.pow(b,2) - 4*a*c;
	System.out.println("Le déterminant est " + discriminant +"."); // donne le déterminant
	if (discriminant>0) {
		x1= (b+Math.sqrt(discriminant))/2*a;
		x2=(b-Math.sqrt(discriminant))/2*a;
		System.out.println("Les solutions sont : x1=" + x1 +" et x2="+x2+"."); 
	}
	if (discriminant<0) {
		System.out.println("Pas de solution réelle."); 
	}
	if (discriminant==0) {
		solusi0=-b/2*a;
		System.out.println("L'unique solution est" + solusi0 +".");
	}
	}
}
