import java.util.Scanner;

public class Programa01 {
static public void main (String[] args) {
Scanner input = new Scanner(System.in);

int QDP;
float preco;
String produto;

float totalpreco = 0.0f;

System.out.println("quantos produtos tem?");

QDP = input.nextInt();



for(int i=1;i<=QDP;i+=1){
System.out.printf("Qual é o nome do produto %d%n",i);
produto = input.next();
System.out.printf("Qual é o preço do produto %d%n",i);
preco = input.nextFloat() ;
totalpreco += preco;
System.out.printf("O preço do produto %s é %.2f%n",produto,preco);
}
if (totalpreco > 150) {
        totalpreco -= (totalpreco/10);
        System.out.println("Você ganhou 10% de desconto!");
System.out.printf("O preço total dos produtos é %.2f%n",totalpreco);
}
}
}
