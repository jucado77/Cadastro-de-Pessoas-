# Cadastro-de-Pessoas-  Algoritmo 
    //algortmo para cadasdtro de pessoas para empresas
  var
	//declaraçao de dados
	nome, RG , CPf caracter
	idade inteiro
  inicio
	//criaçao do cadastro do funcionario
	
	repitirCadastro caracter
	
	escreva(informe o nome do funcionario:")
	leia(nome)
	escreva("infrome o  RG do funcionario:")
	leia(RG)
	escreva("informe o CPF do funcionario")
	leia(CPF)
	
	escreva("infrme a idade do funcionario ")
	leia(idade)
	se (idade < 16) faca
		escreva("fora da idade de trabalhar")
	se ((idade<=16)e(iade>=18))faca
		escreva("Como jovem aprendiz")
	fimse
	se (idade>18)faca
		escreva("Funcionario pode ser contratado como CLT ou PJ")
	
	//consulta de funcionarios
	escreva("nome : ", nome , "RG: ",R,"CPF:",CPF,"iade: ",idade)
	
	escreva("Deseja cadastrar u, novo usuario: s/N")
	leia(repitirCadastro)
	fimenqunto

   FIMDOALGORITMO	
