# exercicios-do-beecrowd
pasta de resolução 
import java.io.IOException;
import java.util.Scanner;
import java.text.DecimalFormat;
public class Main {
 
    public static void main(String[] args) throws IOException {
 		Scanner input = new Scanner(System.in);
		DecimalFormat Df = new DecimalFormat("0.000");
		
		double distancia, combustivel, consumoM;
		distancia = input.nextDouble();
		combustivel = input.nextDouble();
		consumoM= (distancia/combustivel);
		
		System.out.println(Df.format(consumoM)+" km/l");

	}

}
