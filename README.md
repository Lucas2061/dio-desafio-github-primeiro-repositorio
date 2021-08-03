# dio-desafio-github-primeiro-repositorio
Desafio de projeto sobre Git/Github

//programa utilizado para calcular a margem de ganhos mensais de um funcionario e definir se ele bateu sua media anual
programa 
	funcao inicio()
	{
	    real mes1,mes2,mes3,mes4,mes5,mes6,mes7,mes8,mes9,mes10,mes11,mes12,media	
	    cadeia funcionario
		
		escreva("digite o nome do funcionario:")
		leia(funcionario)
		escreva("digite suas vendas do mes 1:")
		leia(mes1)
		escreva("digite suas vendas do mes 2:") 
		leia(mes2)
		escreva("digite suas vendas do mes 3:")
		leia(mes3) 
		escreva("digite suas vendas do mes 4:")
		leia(mes4)
		escreva("digite suas vendas do mes 5:")
		leia(mes5)
		escreva("digite suas vendas do mes 6:") 
		leia(mes6)
		escreva("digite suas vendas do mes 7:")
		leia(mes7) 
		escreva("digite suas vendas do mes 8:")
		leia(mes8)
		escreva("digite suas vendas do mes 9:")
		leia(mes9)
		escreva("digite suas vendas do mes 10:") 
		leia(mes10)
		escreva("digite suas vendas do mes 11:")
		leia(mes11) 
		escreva("digite suas vendas do mes 12:")
		leia(mes12)
		
	
	    media = (mes1+mes2+mes3+mes4+mes5+mes6+mes7+mes8+mes9+mes10+mes11+mes12)/12 

	     escreva("O funcioirario: " + funcionario + " obteve um faturamento de: " + media)
	

	    se(media<=500) {
	    	   escreva("\n" + "infelizmente você não atingio a media anual")
	    } 
	    
	    senao {
	    	    escreva("\n" + "parabens por atingir a media anual, solicite seu bonus na direçao")
	    }
	}
	    
	   
} 

## Links úteis  
[Sintaxe basica Markdow](https://markdown.net.br/sintaxe-basica/)
