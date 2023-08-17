# Construtores

Oque são construtores ?

Dentro das classes que tiverem atributo, tem como  criar um construtor da classe pra quando a classe ser instanciada os atributos já são preenchidos.

Exemplo:

```dart
Class Pessoa{
	Pessoa(); // criação de um construtror simples

	Pessoa({required this.nome}) // passagem dos parametros nomeados já atribundo valor

	Pessoa({required String parNome}){ // passagem dos parametros nomeados por variavel
		nome = parNome;
	}

	Pessoa(String parNome){ // passagem do parametro simples 
		nome = parNome
	}
	
	String nome;
}

// para passar a variavel nomeada
Pessoa pessoa1 = Pessoa(nome: 'Vitor');

// para passar a variavel simples 
Pessoa pessoa2 = Pessoa('Kamille');
```

Dentro dos construtores podemos chamar métodos caso queira quando se instanciar já realizar uma ação

Exemplo:

```dart
Class Pessoa(){
	bool vivo = false;

	Pessoa(){
		nascer();	
	}

	void nascer(){
		if(!vivo){
			vivo = true;
		}
	}
}
```

# Construtores nomeados

Servem para casos específicos aonde necessita que o Objeto seja criado de maneira prédefinida.

Exemplo:

```dart
Class Pessoa{
	bool casado = false;

	Pessoa.casada(){
		casado = true;
	}
}
```