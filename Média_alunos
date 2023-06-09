public class Mediadealunos {

    public static void main(String[] args) {
   
 Scanner input = new Scanner(System.in); 
 int quantidadeAlunos = 10; 
 double[] medias = new double[quantidadeAlunos]; 
 int contador = 0; 
 for (int i = 0; i < quantidadeAlunos; i++) { 
 System.out.println("Aluno " + (i + 1)); 
 double somaNotas = 0; 
 for (int j = 0; j < 4; j++) { 
 System.out.print("Digite a nota " + (j + 1) + ": "); 
 double nota = input.nextDouble(); 
 somaNotas += nota; 
 } 
 double media = somaNotas / 4; 
 medias[i] = media; 
 if (media >= 7.0) { 
 contador++; 
 } 
 System.out.println(); // Pula uma linha para separar os alunos 
 } 
 System.out.println("Número de alunos com média maior ou igual a 7.0: " + contador); 
 } 
} 
