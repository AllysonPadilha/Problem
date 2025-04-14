public class MediaAluno {
    public static void main(String[] args) {
        // Declaração de variáveis com dados fixos
        String nome = "Allyson";
        double nota1 = 9;
        double nota2 = 10;
        double nota3 = 8;
    
        double media;

        // Processamento
        media = (nota1 + nota2 + nota3) / 3;

        // Saída de informação
        System.out.println("Primeira nota: " + nota1);
        System.out.println("Segunda nota: " + nota2);
        System.out.println("Terceira nota: " + nota3);
        System.out.println("Aluno: " + nome);
        System.out.println("Média: " + media);
    }
}
