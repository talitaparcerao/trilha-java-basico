# [DIO](www.dio.me) - Trilha Java Básico

## Autora
- [Talita Parcerão](https://github.com/talitaparcerao)

## POO - Desafio

### Modelagem e Diagramação de um Componente iPhone

Neste desafio eu modelei e diagramei a representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

#### Funcionalidades a Modelar
1. **Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`

### Objetivo
1. Criar um diagrama UML que represente as funcionalidades descritas acima.
2. Implementar as classes e interfaces correspondentes em Java (Opcional).

### Exemplo de Diagrama UML (Mermaid)
```mermaid
classDiagram
    iPhone <|-- ReprodutorMusical
    iPhone <|-- AparelhoTelefonico
    iPhone <|-- NavegadorInternet
    iPhone : +int fabricacao
    iPhone : +String modelo
    iPhone: +ligar()
    iPhone: +achar()
    class ReprodutorMusical{
      +String nome
      +selecionarMusica(Strind Musica)
      +pausar()
      +tocar()
    }
    class AparelhoTelefonico{
      -int codigo
      +ligar(String numero)
      +atender()
      +iniciarCorreioVoz()
    }
    class NavegadorInternet{
      -int ip 
      +verificarConexao()
      +exibirPagina(Sring url)
      +adicionarNovaAba()
      +atualizarPagina()
    }
```

