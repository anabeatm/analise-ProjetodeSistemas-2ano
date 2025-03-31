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
