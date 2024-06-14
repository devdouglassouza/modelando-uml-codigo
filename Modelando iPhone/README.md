## Programação Orientada a Objeto - Desafio

### Modelagem e Diagramação de um Componente iPhone

Desafio para modelar e diagramar a representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

#### Funcionalidades a Modelar

1. **Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`

### Objetivo

- Criar um diagrama UML que represente as funcionalidades descritas acima.

### Diagrama UML (DRAW.io)

```mermaid
classDiagram
    class FuncaoMusical {
        + tocar() void
        + pausar() void
        + selecionarMusica(String musica) void
    }

    class FuncaoTelefonia {
        + ligar(String Numero) void
        + atender() void
        + iniciarCorreioVoz() void
    }

    class FuncaoNavegador {
        + exibirPagina(String url) void
        + adicionarNovaAba() void
        + atualizarPagina() void
    }

    class iPhone {
    }
    iPhone --> FuncaoMusical
    iPhone --> FuncaoTelefonia
    iPhone --> FuncaoNavegador
```
