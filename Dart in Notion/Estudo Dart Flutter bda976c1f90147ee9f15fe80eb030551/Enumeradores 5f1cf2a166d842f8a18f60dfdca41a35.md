# Enumeradores

[https://acervolima.com/enumeracao-de-dados-no-dart/](https://acervolima.com/enumeracao-de-dados-no-dart/)

[https://www.youtube.com/watch?v=sRNjQfIfCJ8](https://www.youtube.com/watch?v=sRNjQfIfCJ8)

## Estrutura de um Enumerador em Dart

![Untitled](Enumeradores%205f1cf2a166d842f8a18f60dfdca41a35/Untitled.png)

essa estrutura é bem parecida com a estrutura do C#, mas a grande diferença é que não podemos colocar um valor para cada item do enum como no C# pode-se fazer

## Converter um enumerado em um numero e um numero em enumerador

```dart
enum StatusPagamento {
  pendente,
  pago,
  reembolsado
}

void main() {
	int indexStatus = status.index;
	StatusPagamento aux = StatusPagamento.values[status.index];
	
	print(indexStatus);
	print(aux);
}
```