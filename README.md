public class ControleEstoque {

    int estoqueatual;
    int adicionar;
    private int getEstoqueatual() {
    	return estoqueatual;
    }
    private void setEstoqueatual(int estoqueatual) {
    	this.estoqueatual = estoqueatual;
    }
    private int getAdicionar() {
    	return adicionar;
    }
    private void setAdicionar(int adicionar) {
    	this.adicionar = adicionar;
    }

}

import java.util.Scanner;

public class Estoque {

    public static void main(String[] args) {
    	int estoqueatual = 0;
    	int adicionar = 0;
    	int total = 0;
    	int retirar= 0;
    	int quantidadeatual = 0;

    	ControleEstoque ce=new ControleEstoque();

    	Scanner sc = new Scanner(System.in);

    	System.out.println("Informe a quantidade a ser inserida no estoque: ");
    	adicionar = sc.nextInt();

       System.out.println("Estoque atual: "+adicionar);

    	System.out.println("Informe quantidade retirada no estoque: ");
    	retirar = sc.nextInt();
    	total = (retirar-adicionar);

       System.out.println("Estoque atualizado:" +total);

    }


      public static void quantidadeatual(int i) {
    	// TODO Auto-generated method stub

    }

    public static void total(int i) {
    	// TODO Auto-generated method stub

    }

    public static void retirar(int i) {
    	// TODO Auto-generated method stub

    }

}
