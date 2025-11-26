# Design

Para a realização do levantamento de requisitos, o primeiro passo é entender o problema e identificar os atores que irão interagir com o sistema. Somente após compreender o contexto e os envolvidos é possível definir funcionalidades coerentes e alinhadas às necessidades reais.

## O Problema

O principal problema que nosso produto busca solucionar está relacionado ao processo de controle e pagamento do tempo de permanência em estacionamentos. Entre as dores identificadas estão:

- Dificuldade em saber o valor a ser pago antecipadamente, pois o usuário só descobre o total no momento da saída.

- Falta de informações claras sobre pagamento e tempo de permanência, deixando o usuário sem visibilidade do seu consumo.

- Dependência dos totens físicos, que obrigam o cliente a deslocar-se até pontos específicos da propriedade apenas para consultar ou pagar.

- Poucas opções de pagamento, limitando a experiência e tornando o processo menos prático.

Nosso sistema visa resolver essas limitações oferecendo praticidade, transparência e autonomia ao usuário durante todo o processo.

## Atores

Ao analisarmos os possíveis atores que interagem com o sistema, percebemos que eles são facilmente identificáveis — afinal, nós mesmos já vivenciamos essas situações. Quem nunca estacionou o carro em um shopping ou evento e tentou adivinhar o valor a ser pago na saída? Quem nunca precisou depender dos totens espalhados pelo estabelecimento, enfrentando filas para quitar um valor simples ou até se surpreendendo com o total a pagar?

Com esse contexto em mente, identificamos os seguintes atores do sistema:

- Pessoa: Qualquer usuário que deseja utilizar o sistema, mesmo sem cadastro.

- Cliente cadastrado: Usuário que opta por registrar-se para armazenar seus dados, histórico e preferências.

- Administrador do estacionamento: Responsável por gerenciar informações gerais, acompanhar métricas e supervisionar o funcionamento do estacionamento.

Esses atores representam todas as perspectivas necessárias para compreender o fluxo de interação do sistema.

## Casos de Uso

Após identificar e descrever os atores que irão interagir com o sistema, o próximo passo é detalhar as interações possíveis entre eles e a solução proposta. Para isso, precisamos primeiro reconhecer cada ação relevante que esses atores podem executar dentro do sistema.

Com esse objetivo, elaboramos o seguinte diagrama de casos de uso, que representa visualmente todas as interações previstas e serve como base para o entendimento e desenvolvimento das funcionalidades.

<p align="center">
  <img src="https://github.com/estaciona-facil/estaciona-facil-docs/blob/main/docs/public/casosDeUso.png?raw=true" />
</p>


## Casos de usuário

Após identificar os casos de uso que o sistema deverá contemplar, é necessário enumerá-los para facilitar a priorização e o planejamento do desenvolvimento. Com base no diagrama elaborado, os casos de uso foram listados e organizados abaixo.

| US   | Ator     | Descrição |
|------|----------|-----------|
| US01 | Pessoa   | Eu **como** Pessoa **desejo** consultar a placa do meu veículo **para** obter informações sobre minha estadia no estacionamento. |
| US02 | Pessoa   | Eu **como** Pessoa **desejo** me cadastrar no sistema **para** que meus registros sejam salvos e recuperados posteriormente. |
| US03 | Cliente  | Eu **como** Cliente **desejo** acessar o sistema com minha conta **para** ter acesso às funcionalidades e aos meus registros. |
| US04 | Cliente  | Eu **como** Cliente **desejo** visualizar meus veículos **para** consultar as informações cadastradas sobre cada um deles. |
| US05 | Cliente  | Eu **como** Cliente **desejo** cadastrar um veículo **para** vinculá-lo ao meu perfil no sistema. |
| US06 | Cliente  | Eu **como** Cliente **desejo** editar os dados de um veículo **para** manter suas informações atualizadas. |
| US07 | Cliente  | Eu **como** Cliente **desejo** excluir um veículo **para** manter meus registros consistentes com a realidade. |
| US08 | Cliente  | Eu **como** Cliente **desejo** registrar a entrada de um veículo no estacionamento **para** iniciar o controle de tempo de permanência. |
| US09 | Cliente  | Eu **como** Cliente **desejo** visualizar as informações do meu veículo no estacionamento **para** me manter informado sobre tempo e valores acumulados. |
| US10 | Cliente  | Eu **como** Cliente **desejo** registrar a saída do estacionamento **para** finalizar a utilização e encerrar a contagem de tempo. |
| US11 | Cliente  | Eu **como** Cliente **desejo** realizar o pagamento **para** quitar o valor referente à utilização do estacionamento. |

# Protóripo de alta fidelidade

Para a elaboração do protótipo de alta fidelidade contei com duas ferramentas, o figma e o v0. O v0 ajudou inicialmente para a geração de estrutra e inspiração e após isso utilizei o figma para contruir as telas da minha forma. Você pode acessar o figma pelo link X e o v0 pelo link U.

Pode ser que não esteja mais disponível e por isso abaixo deixo o resultado do protótipo.

### Login e Cadastro (Figma)
<img width="848" height="295" alt="image" src="https://github.com/user-attachments/assets/15bc73fa-0a48-4ca6-8be7-793ef49689d2" />

### Consultar Placas (Figma)
<img width="1386" height="802" alt="image" src="https://github.com/user-attachments/assets/6706d78b-d83a-4d37-8895-d9ff90bd371f" />
<img width="1392" height="837" alt="image" src="https://github.com/user-attachments/assets/3372aad3-74c6-4127-a25f-578670cff61b" />

### Veículos Estacionados (Figma)
<img width="390" height="283" alt="image" src="https://github.com/user-attachments/assets/5f14e1b5-34a7-492d-b025-262303a3fb37" />

## Dados do Estacionamento (v0)
<img width="1214" height="640" alt="image" src="https://github.com/user-attachments/assets/368fd300-dbb3-46e5-98f3-8e1f3dac8a04" />



