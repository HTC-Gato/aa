import java.util.Scanner;

public class Programa01 {
    static public void main (String[] args) {
	Scanner input = new Scanner(System.in);
        int QDA = 0 ;
        int TotalAprovados = 0 ;
        float percentual = 0F ;
        float totalNotas = 0f ;
        float mediaTurma = 0F ;
       System.out.println("quantos alunos tem na turma");
   QDA = input.nextInt() ;
            for(int i=1;i<=QDA;i+=1){
                System.out.printf("Qual a nota do aluno %d%n",i);
float notaAluno = input.nextFloat() ;
totalNotas += notaAluno;
if(notaAluno>=7.0F){
TotalAprovados += 1;

}
}


mediaTurma = totalNotas/QDA;
System.out.printf("Resultados");
System.out.printf("Total de Alunos: %d%n",QDA);
System.out.printf("Média da Turma: %4.2f%n",mediaTurma);
percentual = (100*TotalAprovados/QDA);
System.out.printf("quantodade de alunos aprovados %d(%4.2f%%)%n",TotalAprovados, percentual);
input.close();
}
}
