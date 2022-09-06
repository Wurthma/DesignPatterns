# DesignPatterns

Repositório para estudo e aplicação dos design patterns do famoso livro do "Gang of Four" (GoF).

# Descrição dos Padrões de Projetos

### Criacional

- **Abstract Factory:** Fornece uma interface para criação de famílias de objetos relacionados ou dependentes sem especificar suas classes concretas.
- **Builder:** O Builder é um padrão de projeto criacional que permite a você construir objetos complexos passo a passo. O padrão permite que você produza diferentes tipos e representações de um objeto usando o mesmo código de construção.
- **Factory Method:** Define uma interface para criar um objeto, mas deixa as subclasses decidirem qual classe a ser instanciada. O Factory Method permite a uma classe postergar (defer) a instanciação às subclasses.
- **Prototype:** Especifica os tipo de objetos a serem criados usando uma instância prototípica e criar novos objetos copiados este protótipo.
- **Singleton:** Garante que uma classe tenha somente uma instância e fornecer um ponto global de acesso para ela.

### Padrões Estruturais

- **Adapter:** Converte a interface de uma classe em outra interface esperada pelos clientes. O Adapter permite que certas classes trabalhem em conjunto, pois de outra forma seria impossível por causa de suas interfaces incompatíveis.
- **Bridge:** Separa uma abstração da sua implementação, de modo que as duas possam varias independentemente.
- **Composite:** Compõe objetos em estrutura de árvore para representar hierarquias do tipo partes-todo. O Composite permite que os clientes tratem objetos individuais e composições de objetos de maneira uniforme.
- **Decorator:** Atribui responsabilidades adicionais a um objeto dinamicamente. Os decorators fornecem uma alternativa flexível a subclasses para extensão da funcionalidade.
- **Façade:** Fornece uma interface unificada para um conjunto de interfaces em um subsistema. O Façade define uma interface de nível alto que torna o subsistema mais fácil de usar.
- **Flyweight:** Usa compartilhamento para suportar grandes quantidades de objetos, de granularidade fina, de maneira eficiente.
- **Proxy:** Fornece um objeto representante (surrogate), ou um marcador de outro objeto, para controlar o acesso ao mesmo.

### Padrões Comportamentais

- **Chain of Responsibility:** Evita o acoplamento do rementente de uma solicitação ao seu destinatário, dando a mais de um objeto a chance de tratar a solicitação. Encadeia os objetos receptores e passa a solicitação ao longo da cadeia até que um objeto a trate.
- **Command:** Encapsula uma solicitação como um objeto, desta forma permitindo que você parametrize clientes com diferentes solicitações, enfileire ou registre (log) solicitações e suporte operações que podem ser desfeitas.
- **Interpreter:** Dada uma linguagem, define uma representação para sua gramática juntamente com um interpretador que usa a representação para interpretar as sentenças nesta linguagem.
- **Iterator:** Fornece uma maneira de acessar sequencialmente os elementos de um objeto agregado sem expor sua representação subjacente.
- **Mediator:** Define um objeto que encapsula como um conjunto de objetos interage. O Mediator promove o acoplamento fraco ao evitar que os objetos se refiram explicitamente uns aos outros, permitindo que você varie suas interações independentemente.
- **Memento:** Sem violar a encapsulação, captura e externaliza um estado interno de um objeto, de modo que o mesmo possa posteriormente ser restaurado para este estado.
- **Observer:** Define uma dependência um-para-muitos entre objetos, de modo que, quando um objeto muda de estado, todos os seus dependentes são automaticamente notificados e atualizados.
- **State:** Permite que um objeto altere seu comportamento quando seu estado interno muda. O objeto parecerá ter mudado sua classe.
- **Strategy:** Define uma família de algoritmos, encapsular cada um deles e fazê-los intercambiáveis. O Strategy permite que o algoritmo varie independemente dos clientes que o utilizam.
- **Template Method:** Define o esquelto de um algoritmo em uma operação, postergando a definição de alguns passos para subclasses. O Template Method permite que as subclasses redefinam certos passos de um algoritmo sem mudar sua estrutura.
- **Visitor:** Representa uma operação a ser executada sobre os elementos da estrutura de um objeto. O Visitor permite que você defina uma nova operação sem mudar as classes dos elementos sobre os quais opera.

# Fontes

- https://refactoring.guru/pt-br