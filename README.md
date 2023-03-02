# Resumo JUnit
Resumo para ajudar o desenvolvimento da prova de JUNit
-

--------------------------------

## Primeiros passos
--------------------------------
### Validações
--------------------------------
 - #### Dependência.
 --------------------------------
No pom.xml antes da tag build, precisamos importar a dependência do JUNit. Segue abaixo linhas de código referentes ao import. 

    <dependencies>
        <dependency>
            <groupId>org.junit.jupiter</groupId>
            <artifactId>junit-jupiter</artifactId>
            <version>5.7.0</version>
            <scope>test</scope>
        </dependency>
    </dependencies>

---------------------------------
 - #### Classes.
 --------------------------------
 Definir suas classes com setters, getters, métodos construtores e validações.

---------------------------------
- #### Main.
---------------------------------
Ao criar sua Main, desenvolva os métodos necessários para criar um sistema funcional e então aplique as validações criadas na sua classe Objeto.

---------------------------------

Agora que temos nossas validações estabelecidas, podemos progredir com os testes em si.
-
---------------------------------

## Passos finais
--------------------------------
### Testes
--------------------------------
- Exemplo estrutura de pastas.

--------------------------------
No mesmo nível que a main/java, se encontra a pasta test, dentro dela se encontra ou não por padrão as pastas java e resources. Dentro da pasta java do nível interior da pasta test, iremos criar uma classe com o mesmo nome da nossa classe main, porem com Test no final de sua nomenclatura. Exemplo, imagina que temos uma classe main de nomenclatura ContactManager, o nome da classe de testes seria ContactManagerTest, onde iremos desenvolver os testes unitários para os métodos de nossa classe main. Já a pasta de resources é onde iremos guardar todos os recursos a serem analisados, como imagens, listas em json ou csvs.

----------------------------------
- Classe de testes.

----------------------------------
Importante sempre estar atento e lembrar de setar o ínicio dos testes, instanciar a classe referente ao teste, ao menos um test relacionado à criação da classe, mensagens periódicas após cada teste e uma mensagem de encerramento da esteira de testes.

----------------------------------
- Rodar o teste ou os testes.

----------------------------------
Para rodar um teste por vez podemos ir na lateral esquerda do método e clicar no sinal de start ao lado do método para rodarmos somente ele, agora para podermos rodar todos, só precisamos clicar shift + F10, ou então clicar na seta de start no topo da IDE.

-----------------------------------

Aproveitem o resumo meus amigos.
-
