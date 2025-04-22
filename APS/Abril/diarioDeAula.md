# 📔 Diário de Aula

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

## 🍳 15/04

### Referência: IEEE 830, com o formato simplificado de: ID, descrição, prioridade, origem, critérios de aceitação.

| ID      | Descrição                                          | Prioridade | Origem      | Critérios de Aceitação                                      |
|---------|----------------------------------------------------|------------|-------------|-------------------------------------------------------------|
| REQ-001 | Controle de entrada de materiais novos | Alta       | LRP001 | Pemitir que os administradores tenham acesso ao controle de entrada de materiais novos |

- Utilizamos os dados da aula passada (levantamento de requisitos), para nossa tabela de requisitos, seguindo o padrão utilizado no mercado há algum tempo.
- Nossa base de dados fora, desde o começo, a entrevista com o Edmar, onde fizemos perguntas que pudessem nos auxiliar.
- Focando em rastreabilidade, focamos em ter coerência e coesão, sempre seguindo o padrão.