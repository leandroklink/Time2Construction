# Time2 – Classe de Horário em Java

Projeto simples em Java que implementa uma classe de horário usando conceitos básicos de Programação Orientada a Objetos.

## Conceitos utilizados

- Encapsulamento
- Sobrecarga de construtores
- Uso de `this()` para reaproveitamento de construtores
- Getters e setters com validação
- Formatação de horário (24h e 12h AM/PM)

## Classes do projeto

### Time2
Classe que representa um horário com:
- hora (0 a 23)
- minuto (0 a 59)
- segundo (0 a 59)

Possui vários construtores:
- construtor padrão
- construtor com hora
- construtor com hora e minuto
- construtor completo
- construtor de cópia

### Time2Test
Classe de teste que cria objetos `Time2` usando diferentes construtores e imprime os horários no console.

## Como executar

Compile os arquivos:
```bash
javac time2/*.java
