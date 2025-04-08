# 📔 Diário de Aula
Por Ana Beatriz Tavares Malaquias - 2º ano Engenharia de Software - IFPR
Olá, esse é meu diário de aula sobre a matéria de Análise e Projeto de Sistemas (APS) do professor Hélio Toshio Kamakawa.

## 🎋 11/03
Foi explicado em aula o que significa essas três palavras: estruturação, execução, finalização, verificação e validação.

> **Estruturação**: define o "o que" e o "como" do sistema.
> **Verificação**: garante que o sistema foi construído conforme o planejado.
> **Validação**: garante que o sistema atende às necessidades reais do usuário.
> **Planejamento x execução**: sempre questionar, compartilhar conhecimento.

Também foi nos passado as seguintes três perguntas:

> A avaliação tem o objetivo de medir o desempenho dos alunos. Você acha que é justo avaliar todo o aprendizado de um aluno em um único dia? Por quê? Quais poderiam ser alternativas mais eficazes?
> O que significa recuperação de estudo? Como um aluno pode revisar o conteúdo de forma eficiente após uma avaliação?
:Entre uma única avaliação e o estudo contínuo, qual desses métodos você acredita ser (1) o mais fácil para aprovação e o (2) mais eficiente para o aprendizado? Justifique sua resposta.
> 
Eu e minha equipe elaboramos, então, as respostas:
> Não. Porquê se trata de um sistema que foca decorar o conteúdo, não aprendê-lo, além de fatores externos (como falta de tempo para se dedicar) e internos (como fatores psicológicos). Auxilio dos professores, compreensão e flexibilidade com empatia para que a avaliação final não seja APENAS uma única prova e faça com que o aluno tenha mais oportunidades de avaliação.
Recuperação de estudo, se trata de novo prazo para demonstrar maior rendimento posterior a prova inicial. Ponderar nos erros que foram causados na avaliação e pontos de maior dificuldade, focando neles para que consiga eliminar as fraquezas e melhorar seu rendimento.
> Estudo contínuo = mais eficiente para o aprendizado, pois reforça o conteúdo todo o dia. Única avaliação = mais fácil para aprovação, decora o conteúdo apenas para a avaliação que, após sua execução, o aluno esquece o que estudou. Pois estudou para decorar, não aprender.

**Nessa aula fui: Júnior.**

## 🎶 18/03

### 👥 **Atividade em equipe 001**

Houve uma atividade em equipe, onde era necessário responder a algumas questões que o professor passou em sala de aula. São elas:

> Buscar pelo menos 3 diferentes exemplos de ciclos de vida de desenvolvimento de software (SDLC);
> Fazer a análise dos SDLCs encontradas, verificar as fases e classifique em Estruturação, Execuação e Finalização;
> Citar metodologias ágeis.

Minha equipe fez as seguintes respostas:
> Planejamento (estruturação): Escopo. Os analistas fazem a análise de custo-benefício para o projeto, fazem metas, criam estimativas. O escopo define as expectativas e as metas que vão ajudar no planejamento.
> Projeto: a equipe ou equipes vão analisar os requisitos que foram criados no planejamento e identificaram as melhores formas para criar o software, podendo ser ferramentas de desenvolvimentos e fazer escolhas mais técnicas/tecnológicas
> Implementação (execução): a equipe irá codificar o projeto, identificam as tarefas saídas do planejamento e colocará em prática, diariamente tentando alcançar o objetivo final
> Teste: o projeto passará por vários testes ao mesmo tempo, já que o mesmo está dividindo em partes, pois assim auxiliará e deixará a manutenção mais barata. Tentando sempre verificar se o projeto está atendendo o pedido do cliente.
> Implantação (finalização): diferente do teste, o projeto já está em seu último estágio, onde há uma cópia do original, deixando o mesmo para o usuário. com essa cópia poderá ser feito correções sem o usuário sofrer com essas alterações, o objetivo da implantação é mover a cópia mais recentes para o ambiente de produção
> Manutenção: aqui o projeto já foi 100% lançado, nessa fase é feitos correções de bugs que passaram batido ou melhorias de ferramentas para atender cada vez mais o usuário, como melhoria na segurança e performance.

Ciclos de vida da SDLC: (https://aws.amazon.com/pt/what-is/sdlc/)

**Sobre os modelos SDLC:**

**Cascata**: sequencial: única entrega. depende de cada resultado da fase anterior, o design vai fluindo de uma fase para a outro. alto custo de manutenção, pois não deixa abertura para testes durante o desenvolvimento. Erro de comunicação.

**Incremental**: entregas rápidas / em pedaços. diminuiu a escala de custo do cascata.
Espiral: combina os pequenos ciclos repetidos do modelo iterativo com o fluxo sequencial linear do modelo cascata, a fim de priorizar a análise de riscos. cliente sempre participa de todas as etapas. o mesmo não sabe o quer.

**Iterativo**: o desenvolvimento é a partir de tarefas divididas, ao passar do tempo do projeto, vai sendo aprimorado até que o software esteja pronto para produção, uma nova versão é desenvolvida ao final de cada iteração.

**Ágil**: iterativo e incremental. Com resultados significativos. organiza o SDLC em vários ciclos. a equipe itera todas as fases, fazendo alterações pequenas (diariamente) onde a cada implementação será feito um teste, avaliando sempre os planos e resultados para que possam responder ao pedido o mais rápido possível: valores principais: Cliente, Equipe, Processo, Software (pronto) -> Manifesto Ágil

Algumas anotações:
```
--> levantamento de dados = entender oq o cliente precisa 
--> analise de requisitos = identificar tecnicamente oq é necessário 
--> modelagem do software = exp: UML 
--> desenvolver --> testar 
--> implantação --> manutenção
```

**Nessa aula fui: Estagiário.**

## 👾 25/03

**Levantamento de requisitos: se errar aqui, já era na outras fases.**

--> Conhecer o certo (entender o cliente: 1. comunicação entre todos;
    2. interpretação. tem que estar alinhados nas ideias;
    3. falta de conhecimento ou o analista não entender direito), analisar certo (1. técnico; 2. experiência)
--> Descrever o certo (descrição e interpretação) -> padrões e técnicas;

-> **Stakeholder**: tanto a equipe quanto os clientes;

-> **Levantamento de dados**: pesquisa de mercado (entender o domínio);
**Entrevista**s (perguntas e resposta guiada); **Etnografia** (vivencia a empresa); **Observação** (limitado;
depende, segredos industrial, por isso difere da observação
da etnografia); **Questionário** (estático; objetivo); **Workshops** (qnd não tem ideia do que **precisa** ser feito,
 tentando buscar um modelo, em conjunto busca uma solução); **Joint Aplication Design (jad)** - noção clara do que precisa ser feito e tecnicamente aplica -;
**Prototipação** (cria um protótipo, conceitual ou prático; para validar); **Análise documental** (analisa os documentos da empresa,
entende o funcionamento burocrático da empresa; todo documento da empresa que te ajuda o que precisa ser feito).

--> **Erros comuns**: permissões, erro na comunicação, viés tendenciosos, interpretação, usar mais do que uma técnica.


### 👥 **Atividade em Equipe 002**
#### Fontes:
[https://www.produttivo.com.br/blog/controle-de-materiais/#:~:text=O%20controle%20de%20materiais%20%C3%A9%20um%20m%C3%A9todo%20de%20organiza%C3%A7%C3%A3o%20que,em%20boas%20condi%C3%A7%C3%B5es%20de%20uso.]

[https://www.nomus.com.br/blog-industrial/controle-de-materiais/]

> Método de organização que tem como objetivo principal assegurar um estoque equilibrado;
>  É importante se certificar que a empresa está atendendo essas normas da Anvisa e que seus colaboradores entendem a importância em respeitá-las;
>  A falta de controle pode trazer diversas consequências para uma empresa, como a falha em mensurar se o consumo dos materiais está de acordo com as necessidades.

#### Perguntas
```
1. como é feito o controle de estoque?
2. como é a análise de necessidades e demandas de reposição?
3. existe um local de fácil organização? como há segurança de que está tudo em ordem?
4. como é mapeado seu controle? e por quê?
5. o controle é atualizado todo dia? de quanto em quanto tempo ele é atualizado?
6. como é feito a entrada e saída de materiais?
7. existe alguma lei que precisa ser seguida? se sim, como garante que todos os produtos estão dentro dessas leis?
8. em caso de algum problema no estoque, como é resolvida a situação? como é a comunicação com os fabricantes?
9. há relatórios fotográficos?
```
## 🍙 01/04
### Entrevista

> Cooperar com a formação dos alunos; Organização é pra racionalizar as tarefas; Formulário de controle; Empréstimo de materias que possibilita o fator de formação de qualidade; Orienta os alunos por meio de fichário e diálogos para que os alunos usem os materiais de forma correta; Regulamento;
> Fichário contem o material que ta sendo fornecido: livro, caderno, cartolina, indentificação de quem tá emprestando o material (aluno, professor), se for professor: coloca a turma, se é o aluno: série, aluno, horário de retirada e devolução; recolhido, faz baixa e confere se está tudo no normal.
> Sociabilidade: como o aluno se sente no Instistuto, como formas de exclusão; fazendo o caminhamento para um profissional que cuide desse aluno;
> Sinalizando e indicando que às vezes o professor não percebe;
> Auxilia diretamente o aluno num processo de formação de qualidade.

#### Perguntas:
1. A saida e entrada é diretamente pelo aluno e professor?
   Sim.
2. Existe um controle virtual?
   Sim, às vezes.
3. Não tem id de identificação, por quê?
   Material de consumo próprio, sua usuabilidade é curto.
4. Tipos de materiais:
   A maioria.
5. FLuxo de entrada e saída de alunos. A demanda de mais materias vai depender da demanda, se tudo estiver no normal.
6. 3 fichários: 1. Achados e Perdidos; 2. Talheres, materiais esportivos, etc...;
7. Justificativa para solicitar um material, entrar num processo com o coordenador, sebrae etc...;
8. Maior dificuldade:
   Perda de materiais. Quando é de uso coletivo, é restrito.
9. Tempo de empréstimo:
    Por exemplo, chave de armário, entrega no mesmo dia.
10. Normativa de perda (achados e perdidos): 3 meses.
11. Dificuldade de recursos;
12. Material danificado: vai passar por um processo.

#### Perguntas da equipe:
1. Aluno fica retido de pegar outro material quando advertido?
2. Como é feito a entrada de material novo?
3. Como está sendo o agendamento de sala no novo sistema?
   Há planilha e no suap, precisa ter mais informações para ter uma resposta. O agendamento está sempre vistoriado.
6. Como funciona a classificação dos blocos de materiais?
   Acahados e perdidos; Controle de Chaves; Outros materiais.

## 🎟️ 08/04

-> Sempre validar (se entendeu direito) e verificar (se está fazendo corretamente).

### Organização Prática de Requisitos com Foco em Rastreabilidade
#### Objetivo
> Organizar e refinar requisitos de forma prática e incremental, garantindo rastreabilidade, clareza e focos.

Necessário decompor as fases e incrementar conforme essas fases.

### Fase 01 - Rastrear
* Código identificador de requisitos;
* Conexão entre requisitos principais e específicos.
  
-> LRP000 - levantamento de requisitos principal.
-> LRE000 - levantamento de requsitos específico.

> Fase 01: Como deixar rastreável?
> Identificação e decomposição.

* Fase 02 e 03: Identificar de que forma os requisitos se diferem e especificar conforme as necessidades.
* Fase 04: Identificar os atores: classificar os usuários.
* Fase 05: Funcionalidades necessárias após os requisitos forem definidos.
* Fase 06: Deixar aberto a entrada de novas funcionalidades fora do escopo inicial, pois podem ter prioridades diferentes.
* Fase 07: Validar e verificar.

### Estudo de Caso em equipe
```
[LRP001] Realizar a gestão de materiais emprestados pelo IFPR.
    [LRE001] Pemitir que os administradores tenham acesso ao controle de entrada de materiais novos (administradtor).
        [AR01-001] Que se adeque quando é produto com ID governamental ou não.
    [LRE002] Pemitir que os administradores tenham acesso ao controle de saída de materiais.
    [LRE003] Pemitir que os administradores tenham acesso Chefe para editar, adicionar ou remover materiais.
    [LRE004] Pemitir que os administradores tenham acesso a classificação de materiais.
    [LRE005] Tanto usuário quando adminisrador podem ter acesso ao monitoramento do estado do material.
    [LRE006] Tanto usuário quando adminisrador podem ter acesso ao monitoramento do tempo de empréstimo.
        [AR06 - 001] Caso passe do tempo de empréstimo, emitir um alerta via email ou SMS para a pessoa emprestada.
        [AR06 - 002] Ter um campo para o motivo do atraso.
    [LRE007] Permitir que os administradores façam um encaminhamento de relatórios de materiais danificados para a sessão administradora.
    [LRE008] Permitir que o usuário faça a solicitação do material que deseja.
```

### Documentação
Análse de Requisitos: o que vale é o conhecimento; mais técnico.

* Cadastro: dados
* Entidade: representa um objeto.
* Dependências: quando um ou mais objeto precisam de seus relacionamentos.
* Campos e características.
* Regras de Negócio: definir regras em cada cadastro.
* Requisitos não funcionais: descrições de funcionalidade.
-> Overleaf: formato SBC.
