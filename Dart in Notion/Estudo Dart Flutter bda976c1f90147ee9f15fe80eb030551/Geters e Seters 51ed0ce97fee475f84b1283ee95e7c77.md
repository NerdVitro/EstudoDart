# Geters e Seters

Métodos Get e Set server par encapsular os atributos de uma classe; Servem para que os atributos não sejam diretamente alterado. Assim deixando a classe e seus atributos mais seguros e menos suscetíveis  a erros

Exemplo de um Get:

```dart
Classe Pessoa{
	// para deixar uma variavel como private basta colocar um anderline
	int _idade;

	int get idade{
		return _idade;
	}

	int get idade => _idade;
}
```

Exemplo de um Set;

```dart
Class Pessoa{
	// Deixando a variavel private 
	double _altura;

	set altura(double parAltura){
		_altura = parAltura;
	}
	// aqui tem um exemplo de uma maneira de validação antes de setar uum valor a varivel
	set altura(double parAltura){
		if(parAltura > 0 && parAltura < 3){
			_altura = parAltura;
		}
	}
}
```