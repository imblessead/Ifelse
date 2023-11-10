# Ifelse
Ifelse

package exemplos;
//desvio composto
import java.util.Scanner;

public class ExemploIfElse01 {

	public static void main(String[] args) {
		
			Scanner sc = new Scanner(System.in);
			
			System.out.println("Digite a sua idade :");
			int idade=sc.nextInt();
			
			if(idade<16) {
				System.out.println("Voce é ainda nao pode votar !");
			}else {
				System.out.println("Voce é pode votar !");
			}
			sc.close();

		}

	

	}
