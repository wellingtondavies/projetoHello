# projetoHello

Primeiro programa em Java do curso: imprime duas saudações no console, uma direto no `main` e
outra por meio de um método estático. Serviu para testar o ambiente (JDK, compilação pela linha de
comando) e o fluxo de versionamento com Git e GitHub.

Projeto acadêmico de Engenharia de Software — Centro Universitário FAG.

**Autor:** Wellington Davies dos Santos.

## Estrutura do repositório

```
src/
└── Hello.java    método main e método holaQueTal()
```

## Como executar

Requisito: JDK 8 ou mais recente.

```bash
javac -d out src/Hello.java
java -cp out Hello
```

Saída esperada:

```
Hello World
Hola que tal
```
