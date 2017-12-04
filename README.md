# ProyectoCalculo
Este proyecto sirve  para calcular  el area de un triangulo , además puede ser ampliado con otras formas de calcurar areas o perimetros.

package tema02;

import java.util.Scanner;

public class Ejercicio20 {

	public static void main(String[] args) {
		int base,altura;
		int A,d=2;
		
		
		Scanner teclado=new Scanner(System.in);
		System.out.println("Introeduzca base: ");
		System.out.println("Introduzca altura: ");
	    base=teclado.nextInt();
	    altura=teclado.nextInt();
		A=(base*altura)/d;
		System.out.println("El area del triángulo es: " +A);
	}

}


