# Ativ-1
public class Carro {
	String cor, modelo;
	int velocidadeAtual, velocidadeMaxima = 100;
	boolean ligar = false;
	
	public Carro(){
		
}
	
	public String getCor() {
		return cor;
	}

	public void setCor(String cor) {
		this.cor = cor;
	}

	public String getModelo() {
		return modelo;
	}

	public void setModelo(String modelo) {
		this.modelo = modelo;
	}

	public int getVelocidadeAtual() {
		return velocidadeAtual;
	}

	public void setVelocidadeAtual(int velocidadeAtual) {
		this.velocidadeAtual = velocidadeAtual;
	}

	public int getVelocidadeMaxima() {
		return velocidadeMaxima;
	}

	public void setVelocidadeMaxima(int velocidadeMaxima) {
		this.velocidadeMaxima = velocidadeMaxima;
	}



public void acelerar(){
	int x;
	for(x = 0;x <= 110; x++){
		velocidadeAtual = x;
		System.out.println("A velocidade atual do veiculo é: " + velocidadeAtual);
		if(velocidadeAtual > velocidadeMaxima){
			System.out.println("O veiculo ultrapassou a velocidade limite");
		}
		}
	
	
	
}

public void ligar( ){
 ligar = true;
	
}

public void desligar( ){
	 ligar = false;
		
}
	
	
}
