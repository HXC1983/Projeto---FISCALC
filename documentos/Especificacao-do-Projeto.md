# Especificação do Projeto

Nesta seção é apresentada uma visão geral das técnicas e ferramentas utilizadas na elaboração deste projeto, permitindo compreender como os requisitos e as funcionalidades do sistema foram definidos.

## Personas

As personas são representações específicas de usuários dentro do público-alvo. Segue abaixo as principais personas da aplicação:

<img width="1200" height="600" alt="personas_fiscalc" src="https://github.com/user-attachments/assets/eac83a95-0c4b-4022-98cd-81b7b5fb2cd1" />

## História de Usuários

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Lucas Mendes (Estudante)  | me cadastrar e fazer login no sistema        | acessar módulos de Física. |
|Lucas Mendes (Estudante)  | selecionar um módulo de Física desejado        | para que eu possa escolher o tema de estudo. |
|Lucas Mendes (Estudante)  | inserir os dados e visualizar o resultado do cálculo     | resolver meus exercícios com mais facilidade. |
|Lucas Mendes (Estudante)  | visualizar um gráfico do cálculo realizado    | entender o comportamento do fenômeno físico. |
|Lucas Mendes (Estudante)  | salvar, editar e excluir meus cálculos   | que eu possa consultá-los posteriormente. |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O sistema deve permitir a autenticação de usuários por meio de login.| ALTA |
|RF-002| O sistema deve permitir o cadastro e o gerenciamento de usuários.| ALTA |
|RF-003| O sistema deve permitir visualizar, editar e excluir usuários.| ALTA |
|RF-004| O sistema deve permitir a seleção do módulo ou área da Física.| ALTA |
|RF-005| O sistema deve permitir inserir dados para realização dos cálculos.| ALTA |
|RF-006| O sistema deve permitir gerar a representação gráfica dos resultados obtidos a partir das equações físicas.| ALTA |  

### Requisitos não funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RNF-001| O sistema deve ser desenvolvido utilizando ASP.NET Core MVC.| 
|RNF-002| O sistema deve utilizar SQL Server para armazenamento persistente dos dados.
|RNF-003| O sistema deve ser acessível por meio dos principais navegadores modernos.
|RNF-004| O sistema deve exigir autenticação para acesso às funcionalidades administrativas. |  BAIXA |
|RNF-005| O sistema deve responder às operações de consulta em até 3 segundos em ambiente local. | MÉDIA |


## Diagrama de Casos de Uso

Atores:

- Estudantes
- Administrador

Casos de uso:

- Realizar Cadastrado;
- Realizar Login;
- Selecionar módulos;
- Inserir dados dos exercícios;
- Gerenciar usuários;

<img width="646" height="742" alt="Diagrama_Casos de Uso_FISCALC" src="https://github.com/user-attachments/assets/0b5cba17-8b1e-49df-8807-32795ae66aa4" />

