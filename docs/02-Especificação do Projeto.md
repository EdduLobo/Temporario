# Especificações do Projeto

## Personas

Joana Alves Pereira - 15 anos

- Estudante do ensino médio
- Aluna de escola pública, sem muitos recursos para adquirir livros impressos requeridos pela insituição de ensino para as atividades da matéria de Língua Portuguesa e Literatura.

Dra. Beatriz Lima - 58 anos

- Professora do ensino superior, autora de livros de literatura.
- Procura por uma plataforma para divulgar parte de suas obras para leitores que, se interessando pelo material, irão adquirir suas obras (em formato impresso ou digital). 

João Lucas Melo - 48 anos

- Advogado de um grande escritório de advocacia focado em direito empresarial com uma vasta cartela de clientes. 
- João viaja bastante à trabalho e tem a leitura como um hobby, aprecia os clássicos da literatura luso-brasileira, mas como viaja partindo muitas vezes de última hora para se reunir com clientes, necessita de uma plataforma digital para armazenamento das obras que lê, uma vez que transportar livros impressos se mostra um incômodo e uma tarefa nada prática. 


## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

| `PERSONA`         | `FUNCIONALIDADE`                                                                    | `MOTIVO/VALOR`                                                                                                     |
| ----------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| Joana Alves Pereira       | Ter uma plataforma móvel para leitura das obras requisitadas por sua escola. | Poder ter a praticidade para ler as obras a qualquer momento, principalmente no seu deslocamento casa-escola e escola-casa, que realiza utilizando meios de transporte coletivo urbano. |
| Dra. Beatriz Lima    | Ter um modo de disponibilizar amostras de suas obras para possíveis compradores.                         | Aumentar a divulgação de seu trabalho.                     |
| João Lucas Melo    | Conseguir ler obras literárias enquanto está no carro ou enquante espera no saguão do terminal do aeroporto pela saída de seu vôo, sem ter que carregar diversos volumes de livros impressos.                                | Ter praticidade para exercer seu hobby de leitura.                                                                 |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID       | Descrição do Requisito                                                                                            | Prioridade |
| -------- | ----------------------------------------------------------------------------------------------------------------- | ---------- |
|  RF-001  | A aplicação deve permitir ao usuário buscar uma obra específica.                                                  | ALTA       |
|  RF-002  | A aplicação deve permitir ao usuário buscar uma lista de obras baseado em um formato (livro, HQ, etc.)            | ALTA       |
|  RF-003  | A aplicação deve permitir ao usuário buscar uma lista de obras baseado em um gênero.                              | ALTA       |
|  RF-004  | A aplicação deve permitir a um usuário cadastrar e remover uma obra feita pelo mesmo.                             | ALTA       |
|  RF-005  | A aplicação deve permitir o usuário acessa um feed de recomendações de livros.                                    | ALTA       |
|  RF-006  | A aplicação deve permitir o usuário criar sua conta, acessar seu histórico de leituras.                           | ALTA       |
|  RF-007  | A aplicação deve permitir o usuário criar uma lista de livros para ler mais tarde.                                | ALTA       |
|  RF-008  | A aplicação deve permitir o usuário criar sua conta e acessar seu histórico de leituras.                          | ALTA       |
|  RF-009  | A aplicação deve permitir o usuário a editar seu perfil onde o mesmo pode ter status de público ou privado.       | ALTA       |
|  RF-010  | A aplicação deve permitir o usuário a editar, excluir e mandar seu perfil para outras pessoas.                    | ALTA       |
|  RF-011  | A aplicação deve permitir o usuário a criar uma descrição sobre a obra cadastrada juntamente com a imagem da capa.| ALTA       |
|  RF-011  | A aplicação deve permitir o usuário recuperar sua senha atráves do email cadastrado.                              | ALTA       |


### Requisitos não Funcionais

| ID      | Descrição do Requisito                                                                           | Prioridade |
|---------|--------------------------------------------------------------------------------------------------|------------|
| RNF-001 | A aplicação deverá ser de fácil leitura e entendimento.                                          | MÉDIA      |
| RNF-002 | A aplicação deve ser desenvolvida em ReactJS                                                     | MÉDIA      |
| RNF-003 | A aplicação deverá ser responsiva e poderá ser acessada em diversos dispositivos e equipamentos. | MÉDIA      |
| RNF-004 | A aplicação deverá ser compatível com diversos navegadores.                                      | MÉDIA      |


## Diagrama de Casos de Uso

<img src="/src/img/diagrama-de-casos-de-uso.jpg">
