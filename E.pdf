
public class E {
	private String nome;
	private int idade;
	private int periodo;
	private String curso;
	private boolean mensalidade;
	//
	public String getNome() {
		return nome;
	}
	//
	public void setNome(String nome) {
		this.nome = nome;
	}
	//
	public int getIdade() {
		return idade;
	}
	//
	public void setIdade(int idade) {
		this.idade = idade;
	}
	//
	public int getPeriodo() {
		return periodo;
	}
	//
	public void setPeriodo(int periodo) {
		this.periodo = periodo;
	}
	//
	public String getCurso() {
		return curso;
	}
	//
	public void setCurso(String curso) {
		this.curso = curso;
	}
	//
	public boolean isMensalidade() {
		return mensalidade;
	}
	//
	public void setMensalidade(boolean mensalidade) {
		this.mensalidade = mensalidade;
	}
	//
	
	public void estadoDoAluno() {
		System.out.println("O aluno " + getNome() + " está cursando o " + getPeriodo() + " periodo.");
	}
	//
	
	public void checarMensalidadeDesseMes() {
		if(mensalidade != false ) {
			System.out.println("Esse aluno já pagou a mensalidade desse mes");
		} else {
			System.out.println("Esse aluno ainda nao pagou a mensalidade desse mes");
		}
	}
	//
	public void faltaParaTerminar() {
		System.out.println("Ainda falta(m) " + (8 - periodo) + " periodo(s) para esse aluno terminar sua graduação");
	}
	//assumese que todos os alunos que forem criados sao de sistemas
	

	public static void main(String[] args) {
	
		E elvis = new E();
		elvis.setNome("Elvis");
		elvis.setCurso("Sistemas");
		elvis.setIdade(23);
		elvis.setPeriodo(4);
		elvis.estadoDoAluno();
		elvis.setMensalidade(true);
		elvis.checarMensalidadeDesseMes();
		elvis.faltaParaTerminar();
		
	}
}
