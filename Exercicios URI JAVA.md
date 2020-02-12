exercicios URI 10 Area


import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		double A; double B; double C; double triangulo; double circulo; double trapezio; double quadrado; double retangulo; 
		Scanner sc=new Scanner(System.in);
		A=sc.nextDouble(); B=sc.nextDouble(); C=sc.nextDouble();
		triangulo=((A * C)/2.0);
		circulo=(3.14159) * Math.pow(C, 2);
		trapezio=((A + B) * C/2.0);
		quadrado=Math.pow(B, 2);
		retangulo=(A * B);
		System.out.println("TRIANGULO: " + String.format("%.3f", triangulo));
		System.out.println("CIRCULO: " + String.format("%.3f", circulo));
		System.out.println("TRAPEZIO: " + String.format("%.3f", trapezio));
		System.out.println("QUADRADO: " + String.format("%.3f", quadrado));
		System.out.println("RETANGULO: " + String.format("%.3f", retangulo));
		sc.close();
      
	}	

exercicios URI 9 Esfera

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		double volume; double pi=3.14159; double raio;
		Scanner sc= new Scanner(System.in);
		raio=sc.nextDouble();
		volume= (double) ((4.0/3) * pi * Math.pow(raio, 3));
	    System.out.println("VOLUME = " + String.format("%.3f", volume));	
	    sc.close();
		
		
		
		

	}

}



exercicios URI 8 calculo simples

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		int codigo1; double total; int numero1; double valor1; int codigo2; int numero2; double valor2;
		Scanner sc= new Scanner(System.in);
		codigo1=sc.nextInt(); numero1=sc.nextInt(); valor1=sc.nextDouble();
		codigo2=sc.nextInt(); numero2=sc.nextInt(); valor2=sc.nextDouble();
		total=((valor1 * numero1)+(valor2 * numero2));
	    System.out.println("VALOR A PAGAR: R$ " + String.format("%.2f", total));	
	    sc.close();
		
		
		
		

	}

}

exercicios URI 7 salario com bonus

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		String vendedor; double salario; double vendas; double total;
		Scanner sc= new Scanner(System.in);
		vendedor=sc.next();
		salario=sc.nextDouble();
		vendas=sc.nextDouble();
		total=((vendas * 15/100) + salario);
	    System.out.println("TOTAL = R$ " + String.format("%.2f", total));	
	    sc.close();
		
		
		
		

	}

}

exercicios URI 6 salario 

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		int number; int hours; double value; double salary;
		Scanner sc= new Scanner(System.in);
		number=sc.nextInt();
		hours=sc.nextInt();
		value=sc.nextDouble();
		salary= (double) (hours * value);
		System.out.println("NUMBER = " + number);
		System.out.println("SALARY = U$ " + String.format("%.2f", salary));
		sc.close();
		
		
		
		
		

	}

}

exercicios URI 5 diferença

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		int A; int B; int C; int D; int DIFERENCA;
		Scanner sc= new Scanner(System.in);
		A=sc.nextInt();
		B=sc.nextInt();
		C=sc.nextInt();
		D=sc.nextInt();
		DIFERENCA= ((A * B)) - ((C * D));
		System.out.println("DIFERENCA = " + DIFERENCA);
		sc.close();
		
		
		
		
		

	}

}

exercicios URI 4 media 2

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		double A; double B; double C; double MEDIA; double pesoA=2.0; double pesoB=3.0; double pesoC=5.0;
		Scanner sc= new Scanner(System.in);
		A=sc.nextDouble();
		B=sc.nextDouble();
		C=sc.nextDouble();
		MEDIA= (double) ((A * pesoA) + (B * pesoB) + (C*pesoC))/10.0;
		System.out.println("MEDIA = "+String.format("%.1f", MEDIA));
		sc.close();
		
		
		
		

	}

}

exercicios URI 3 media 1

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		double A; double B; double MEDIA; double peso1=3.5; double peso2=7.5;
		Scanner sc= new Scanner(System.in);
		A=sc.nextDouble();
		B=sc.nextDouble();
		MEDIA= (double) ((A * peso1) + (B * peso2))/11;
		System.out.println("MEDIA = "+String.format("%.5f", MEDIA));
		sc.close();
		
		
		
		
		

	}

}

exercicio URI  2 produto simples

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		int A; int B; int PROD;
		Scanner sc= new Scanner(System.in);
		A=sc.nextInt();
		B=sc.nextInt();
		PROD= A * B;
		System.out.println("PROD = "+ PROD);
		sc.close();
		
		
		
		
		

	}

}

exercicio URI 1 area do circulo

import java.util.Scanner;
public class Main {

	public static void main(String[] args) {
		double area; double π=3.14159;  double raio;
		Scanner sc= new Scanner(System.in);
		raio=sc.nextDouble();
		area= (double) π * (Math.pow(raio, 2));
		System.out.println("A="+String.format("%.4f", area));
		sc.close();
		
		
		
		
		

	}

}

exercicio URI calcular plano de telefonia

import java.util.Scanner;
public class Exercicio12 {

	public static void main(String[] args) {
		int minutos; double valor=50.00;  
		Scanner sc= new Scanner (System.in);
		minutos=sc.nextInt();
		if(minutos > 100) {
			valor= valor + (minutos - 100) * 2.0; 
			System.out.printf("Valor a pagar: R$ %.2f%n", valor);
		}
		if(minutos <= 100) {
			System.out.printf("Valor a pagar: R$ %.2f%n", valor);
		}
		sc.close();

	}

}


import java.util.Scanner;
import java.util.InputMismatchException;
public class Exercicio12 {

	public static void main(String[] args) {

try {		
		int dia;  
		Scanner sc= new Scanner (System.in);
	        dia=sc.nextInt();
	    
	
	    
		
 
	switch(dia) {
	   
	case 1:
	  System.out.println("Dia da semana: Domingo");
	  break;
	
	case 2:
	 System.out.println("Dia da semana: Segunda");
	 break;	
	 
	case 3:
	 System.out.println("Dia da semana: Terça feira");
     break;
     
	case 4:
	 System.out.println("Dia da semana: Quarta feira");
	 break;
	 
	case 5:
	 System.out.println("Dia da semana: Quinta feira");
	 break;
	 
	case 6:
     System.out.println("Dia da semana: Sexta feira");
	 break;
		
	case 7: 
	 System.out.println("Dia da semana: Sabado");
	 break;

	}
	
	sc.close();
	
	}
      catch (InputMismatchException e){
    	  System.out.println("Favor digite um numero dentro do intervalo");
	   	
	}
 

       
}	
	

}


