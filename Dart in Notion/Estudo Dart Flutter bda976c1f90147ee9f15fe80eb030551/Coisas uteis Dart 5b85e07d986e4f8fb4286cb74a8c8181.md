# Coisas uteis Dart

## Datas:

```dart
void main() {
  MetodosMes tese = MetodosMes(data: DateTime.now());

  print("Dia atual:     ${tese.diaAtual}");
  print("Primeiro dia:  ${tese.primeiroDia}");
  print("Ultimo dia:    ${tese.lastDay}");
}

class MetodosMes {
  DateTime data;
  int year = 0;
  int month = 0;

  MetodosMes({required this.data}) {
    year = data.year;
    month = data.month;
  }

  int get diaAtual {
    return data.day;
  }

  int get primeiroDia {
    return 1;
  }

  int get lastDay {
    return DateTime(year, month + 1, 0).day;
  }
}
```