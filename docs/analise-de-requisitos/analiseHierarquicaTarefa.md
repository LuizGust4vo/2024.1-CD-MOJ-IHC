# <a>Análise Hierárquica de Tarefas (HTA)</a>

## <a>Introdução</a>

A Análise Hierárquica de Tarefas (HTA) é uma técnica de análise que decompõe uma tarefa complexa em uma estrutura hierárquica de metas, submetas e procedimentos. Essa abordagem ajuda a esclarecer como uma tarefa é executada e identifica áreas que precisam de melhorias. A HTA é frequentemente aplicada em uma variedade de áreas, incluindo desenvolvimento de produtos, serviços e otimização de processos. Para visualizar a análise, pode-se usar diagramas ou tabelas, detalhados na representação gráfica exemplificada na figura 1.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 1</b> - Notação diagrama HTA.</p></font>

![Diagrama HTA](./assets/diagramaHTA.png){width: 350}

<font size="3"><p style="text-align: center">Fonte: BARBOSA e SILVA, 2021, p.179.<a id=anchor_1 href="#REF1"><sup>1</sup></a></p></font>

</figure>

## <a>Análise de Tarefas</a>

No que diz respeito às tarefas para análise com o método HTA, foram escolhidas a criação de problemas e contests, o login e a submissão de respostas, conforme explicitado nas figuras de 2 a 7 e nas tabelas de 1 a 6.

### <a>Submissão de Problema</a>

Nesta tarefa, o usuário tem o objetivo de submeter uma solução para um problema de programação. A seguir, apresentamos o diagrama e a tabela HTA desta tarefa.

<center>

<figure markdown>
<font size="3"><b>Figura 2</b> - Diagrama HTA de Submissão de Problemas.</font>

![Diagrama HTA 1](docs/analise-de-requisitos/assets/HTA_01.png){width: 300}

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Tabela HTA de Submissão de Problema</p></font>

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| **0. Submeter solução** | |
| **1. Selecionar problema** | **Input:** Usuário escolhe o problema a partir da lista.<br>**Feedback:** Detalhes do problema são exibidos. |
| **2. Escrever código** | **Input:** Usuário escreve solução no editor integrado.<br>**Feedback:** Realce de sintaxe e erros de compilação em tempo real. |
| **3. Testar código** | **Input:** Usuário executa testes locais.<br>**Feedback:** Resultados dos testes exibidos. |
| **4. Submeter solução** | **Input:** Usuário clica em 'Submeter'.<br>**Feedback:** Solução é enviada para avaliação. |
| **5. Receber feedback** | **Feedback:** Resultados da avaliação (correto, erro de execução, tempo excedido, etc.). |

<font size="3">Fonte: [João Artur](https://github.com/joao-artl).</font>

</center>

### <a>Login em Contest</a>

Para o acesso a competições ou "contests", o usuário deve realizar o login no sistema. Esta é uma etapa crucial para garantir que apenas participantes autorizados possam entrar e competir. Abaixo, está o diagrama e a tabela HTA para a tarefa de Login em Contest.

<center>

<figure markdown>
<font size="3"><b>Figura 3</b> - Diagrama HTA de Login em Contest.</font>

![Diagrama HTA 2](docs/analise-de-requisitos/assets/HTA_02.png){width: 300}

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Tabela HTA de Login em Contest</p></font>

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| **0. Acessar contest** | |
| **1. Abrir a página de login** | **Input:** Usuário acessa a página de login.<br>**Feedback:** Página de login exibida. |
| **2. Inserir credenciais** | **Input:** Usuário insere nome de usuário e senha.<br>**Feedback:** Visualização de caracteres de senha opcional. |
| **3. Autenticar** | **Input:** Clique em 'Entrar'.<br>**Feedback:** Verificação de credenciais e redirecionamento para a página do contest. |
| **4. Acessar página do contest** | **Feedback:** Exibição das informações do contest e participação habilitada. |

<font size="3">Fonte: [João Artur](https://github.com/joao-artl).</font>

</center>

### <a>Verificação de Submissões</a>

Nesta tarefa, o usuário ou o administrador verifica o resultado das submissões feitas durante um contest. Abaixo, está o diagrama e a tabela HTA desta tarefa:

<center>

<figure markdown>
<font size="3"><b>Figura 4</b> - Diagrama HTA de Verificação de Submissões.</font>

![Diagrama HTA 3](docs/analise-de-requisitos/assets/HTA_03.png){width: 300}

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>

</figure>

<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Tabela HTA de Verificação de Submissões</p></font>

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| **0. Verificar submissões** | |
| **1. Acessar lista de submissões** | **Input:** Usuário ou administrador acessa a lista de submissões do contest.<br>**Feedback:** Lista de submissões exibida. |
| **2. Analisar resultado** | **Input:** Seleção de uma submissão específica.<br>**Feedback:** Detalhes do resultado da submissão (correto, erro, tempo excedido, etc.). |
| **3. Verificar logs de execução** | **Input:** Acesso aos logs de execução para detalhamento de erros.<br>**Feedback:** Logs exibidos para diagnóstico. |

<font size="3">Fonte: [João Artur](https://github.com/joao-artl).</font>

</center>

### <a>Ranking de Contest</a>

Esta tarefa aborda como os resultados dos participantes são calculados e exibidos em forma de ranking durante ou após um contest.

<center>

<!--<figure markdown>
<font size="3"><b>Figura 5</b> - Diagrama HTA de Ranking de Contest.</font>

![Diagrama HTA](docs/analise-de-requisitos/assets/diagramaHTA.png){width: 300}

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>

</figure> -->

<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Tabela HTA de Ranking de Contest</p></font>

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| **0. Exibir ranking** | |
| **1. Calcular pontos** | **Input:** Sistema processa os resultados das submissões.<br>**Feedback:** Pontuação calculada com base em critérios predefinidos. |
| **2. Ordenar resultados** | **Input:** Sistema ordena participantes com base na pontuação e outros critérios.<br>**Feedback:** Ranking atualizado e exibido. |
| **3. Exibir detalhes** | **Input:** Usuário acessa detalhes de performance individual e comparações.<br>**Feedback:** Detalhes exibidos incluem tempo de submissão, número de tentativas, etc. |
| **4. Atualizar ranking em tempo real** | **Input:** Sistema atualiza o ranking conforme novas submissões são processadas.<br>**Feedback:** Ranking dinâmico e sempre atualizado. |

<font size="3">Fonte: [João Artur](https://github.com/joao-artl).</font>

</center>


### <a>Criação de Problema (Administrador)</a>

Nesta tarefa, o administrador cria e configura novos problemas para os usuários resolverem. Incluímos o diagrama e a tabela HTA desta tarefa.

<center>

<!--<figure markdown>
<font size="3"><b>Figura 6</b> - Diagrama HTA de Criação de Problema.</font>

![Diagrama HTA](docs/analise-de-requisitos/assets/diagramaHTA.png){width: 300}

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font>

</figure> -->

<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Tabela HTA de Criação de Problema</p></font>

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| **0. Criar problema** | |
| **1. Definir enunciado** | **Input:** Administrador escreve o enunciado.<br>**Feedback:** Pré-visualização do texto. |
| **2. Configurar testes** | **Input:** Entradas e saídas esperadas são definidas.<br>**Feedback:** Testes salvos para validação. |
| **3. Definir restrições** | **Input:** Limites de tempo e memória.<br>**Feedback:** Restrições registradas no sistema. |
| **4. Publicar problema** | **Input:** Clique em 'Publicar'.<br>**Feedback:** Problema disponível para usuários. |

<font size="3">Fonte: [João Artur](https://github.com/joao-artl).</font>

</center>

### <a>Criação de Contest (Administrador)</a>

Nesta tarefa, o administrador organiza competições (contests) que agregam diversos problemas para serem resolvidos pelos participantes dentro de um tempo definido. Abaixo estão o diagrama e a tabela HTA desta tarefa.

<center>

<!--<figure markdown>
<font size="3"><b>Figura 7</b> - Diagrama HTA de Criação de Contest.</font>

![Diagrama HTA](docs/analise-de-requisitos/assets/diagramaHTA.png){width: 300}

<font size="3"><p style="text-align: center">Fonte: [João Artur](https://github.com/joao-artl).</p></font> -->

<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Tabela HTA de Criação de Contest</p></font>

| Objetivos/Operações | Problemas e Recomendações |
|---------------------|---------------------------|
| **0. Criar contest** | |
| **1. Definir informações básicas** | **Input:** Nome, duração e tipo de acesso (público ou privado).<br>**Feedback:** Informações registradas. |
| **2. Selecionar problemas** | **Input:** Escolher problemas da biblioteca ou criar novos.<br>**Feedback:** Problemas adicionados ao contest. |
| **3. Configurar participantes** | **Input:** Definir se o contest é aberto a todos ou apenas por convite.<br>**Feedback:** Configuração salva. |
| **4. Definir regras de pontuação** | **Input:** Estabelecer critérios de pontuação e penalidades.<br>**Feedback:** Regras estabelecidas para o contest. |
| **5. Publicar contest** | **Input:** Clique em 'Publicar'.<br>**Feedback:** Contest disponível para inscrição ou participação direta. |

<font size="3">Fonte: [João Artur](https://github.com/joao-artl).</font>

</center>

## <a>Bibliografia</a>
> <a id="REF1" href="#anchor_1">1.</a>Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)Interação Humano-Computador e Experiência do usuário.

## <a>Histórico de Versão</a>

| Versão| Data | Data Prevista de Revisão| Descrição  | Autor(es)  | Revisor(es) |
| ------- | ------ | ------ | ------- | -------- | -------- |
| `1.0` | 13/04/2024 | 20/04/2024 | Criação da página de Análise Hierárquica de Tarefas.| [João Artur](https://github.com/joao-artl)|[Diego Sousa](https://github.com/DiegoSousaLeite)|
| `1.1` | 21/04/2024 | 23/04/2024 | Adicionando imagem dos diagramas.| [João Artur](https://github.com/joao-artl)|[Diego Sousa](https://github.com/DiegoSousaLeite)|