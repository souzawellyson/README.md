import java.util.Scanner;
public class GerenciadorDePessoas {
    //Criação de dois objetos do tipo Pessoa
    private Pessoa pessoa1;
    private Pessoa pessoa2;

    public GerenciadorDePessoas(Pessoa pessoa1, Pessoa pessoa2){
        this.pessoa1 = pessoa1;
        this.pessoa2 = pessoa2;
    };

    //Objeto "entrada" do tipo Scanner que vai pegar o texto digitado do teclado
    Scanner entrada = new Scanner(System.in);
    
    
    public void cadastrarPessoa1(Pessoa pessoa){
        System.out.println("CADASTRAR PESSOA 1");
        System.out.print("Informe o nome da pessoa 1: ");
        this.pessoa1.setNome(entrada.next());
        System.out.print("Informe o CPF: ");
        this.pessoa1.setCpf(entrada.next());
        System.out.print("Informe a idade: ");
        this.pessoa1.setIdade(entrada.nextInt());
    }
    public void cadastrarPessoa2(Pessoa pessoa){
        System.out.println("CADASTRAR PESSOA 2");
        System.out.print("Informe o nome da pessoa 2: ");
        this.pessoa2.setNome(entrada.next());
        System.out.print("Informe o CPF: ");
        this.pessoa2.setCpf(entrada.next());
        System.out.print("Informe a idade: ");
        this.pessoa2.setIdade(entrada.nextInt());
    }
    public void atualizarPessoa1(Pessoa pessoa){
        System.out.println("ATUALIZAR PESSOA 1");
        System.out.print("Informe o novo nome da pessoa 1: ");
        this.pessoa1.setNome(entrada.next());
        System.out.print("Informe o CPF: ");
        this.pessoa1.setCpf(entrada.next());
        System.out.print("Informe a idade: ");
        this.pessoa1.setIdade(entrada.nextInt());
    }
    public void atualizarPessoa2(Pessoa pessoa){
        System.out.println("ATUALIZAR PESSOA 2");
        System.out.print("Informe o novo nome da pessoa 2: ");
        this.pessoa2.setNome(entrada.next());
        System.out.print("Informe o CPF: ");
        this.pessoa2.setCpf(entrada.next());
        System.out.print("Informe a idade: ");
        this.pessoa2.setIdade(entrada.nextInt());
    }
    public void exibirPessoa1(){
        System.out.println("DADOS DA PESSOA 1");
        System.out.println("Nome: " + this.pessoa1.getNome());
        System.out.println("CPF: " + this.pessoa1.getCpf());
        System.out.println("Idade: " + this.pessoa1.getIdade());
    }
    public void exibirPessoa2(){
        System.out.println("DADOS DA PESSOA 2");
        System.out.println("Nome: " + this.pessoa2.getNome());
        System.out.println("CPF: " + this.pessoa2.getCpf());
        System.out.println("Idade: " + this.pessoa2.getIdade());
    }
}
