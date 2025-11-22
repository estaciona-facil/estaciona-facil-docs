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

