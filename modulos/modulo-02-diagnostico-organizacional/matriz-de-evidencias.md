
# Matriz de Evidências

## Sistema Operacional do Estúdio LICHTARA

**Módulo:** 2 — Diagnóstico Organizacional
**Tipo:** Método de organização e rastreabilidade diagnóstica
**Versão:** 0.1
**Status:** Em desenvolvimento e validação pela prática
**Data de criação:** 01/08/2026

**Documentos relacionados:**

* `README.md`
* `fundamentos-do-diagnostico.md`
* `protocolo-de-diagnostico.md`
* `templates/matriz-de-evidencias.md`
* `templates/sintese-diagnostica.md`

---

# 1. Finalidade

A Matriz de Evidências é o mecanismo utilizado pelo Estúdio LICHTARA para organizar e tornar rastreável o raciocínio diagnóstico.

Ela relaciona:

* questões de investigação;
* hipóteses;
* fontes;
* evidências;
* interpretações;
* divergências;
* lacunas;
* graus de confiança;
* achados diagnósticos;
* implicações;
* necessidades de aprofundamento.

Sua função é impedir que conclusões sejam produzidas apenas a partir de:

* memória;
* impressão geral;
* relato isolado;
* autoridade de uma pessoa;
* aplicação automática de ferramentas;
* resumo produzido por inteligência artificial;
* preferência por determinada solução.

A matriz permite reconstruir o caminho entre uma pergunta inicial e uma conclusão diagnóstica.

Ela responde:

> Que evidências sustentam o que estamos afirmando?

---

# 2. Posição da matriz no diagnóstico

A Matriz de Evidências está localizada entre a coleta e a formulação dos achados.

O fluxo simplificado é:

```text
Questão diagnóstica
        ↓
Hipóteses iniciais
        ↓
Plano de investigação
        ↓
Coleta de evidências
        ↓
Matriz de Evidências
        ↓
Interpretação
        ↓
Achados diagnósticos
        ↓
Síntese e validação
```

A matriz não substitui:

* notas de entrevistas;
* registros de observação;
* documentos originais;
* mapas;
* análises específicas;
* relatório final.

Ela funciona como uma camada de conexão entre esses materiais.

---

# 3. O que a matriz deve permitir

Uma matriz adequadamente preenchida deve permitir que outra pessoa compreenda:

1. qual pergunta estava sendo investigada;
2. que hipótese orientava a investigação;
3. de onde veio cada informação;
4. o que foi efetivamente observado;
5. o que foi relatado;
6. o que foi interpretado;
7. quais fontes convergem;
8. quais fontes divergem;
9. que informações ainda faltam;
10. qual é a qualidade da evidência;
11. que conclusão provisória pode ser sustentada;
12. qual é o grau de confiança;
13. que achado poderá ser formulado;
14. que decisão ou etapa posterior será afetada.

---

# 4. Princípios da matriz

## 4.1 Uma linha não representa automaticamente uma conclusão

Cada linha registra uma unidade de evidência ou um conjunto diretamente relacionado de evidências.

A conclusão emerge da análise de várias linhas, não do preenchimento isolado de uma célula.

---

## 4.2 Evidência e interpretação devem permanecer separadas

### Evidência

> Foram localizadas doze propostas enviadas sem próxima ação registrada.

### Interpretação

> A ausência de próxima ação pode estar contribuindo para a perda de continuidade comercial.

A evidência descreve o que foi encontrado.

A interpretação atribui significado.

---

## 4.3 Relatos são evidências situadas

Um relato não deve ser descartado por ser subjetivo.

Também não deve ser tratado automaticamente como descrição completa da organização.

Deve ser registrado com:

* fonte;
* posição da pessoa;
* contexto;
* exemplos;
* convergências;
* divergências;
* possibilidade de verificação.

---

## 4.4 Ausência de registro não prova ausência de prática

Quando um documento ou registro não for localizado, a formulação adequada é:

> Não foi localizado registro do acompanhamento no período analisado.

Não se deve concluir automaticamente:

> O acompanhamento não acontece.

Pode existir:

* prática informal;
* documento inacessível;
* registro em outro ambiente;
* perda de arquivo;
* ausência real da atividade.

---

## 4.5 Contradições não devem ser eliminadas

Quando duas fontes divergem, ambas devem permanecer visíveis.

A divergência pode revelar:

* processos diferentes;
* experiências distintas;
* acesso desigual à informação;
* mudança recente;
* exceção;
* conflito;
* ausência de definição compartilhada.

---

## 4.6 O grau de confiança deve acompanhar a força da evidência

A linguagem diagnóstica deve corresponder à qualidade e à convergência das fontes.

A matriz não existe para produzir certeza artificial.

Ela existe para tornar a incerteza explícita e administrável.

---

## 4.7 Toda evidência deve estar vinculada a uma finalidade

Não devem ser inseridas informações apenas porque foram coletadas.

Cada evidência deve estar relacionada a:

* uma questão;
* uma hipótese;
* um achado potencial;
* uma decisão;
* uma necessidade de contexto.

---

# 5. Unidades de registro

A matriz trabalha com diferentes unidades.

---

## 5.1 Questão diagnóstica

Pergunta principal que o diagnóstico procura responder.

### Exemplo

> Como as oportunidades comerciais são registradas e acompanhadas atualmente, e onde ocorrem perdas de continuidade?

---

## 5.2 Pergunta secundária

Pergunta específica que ajuda a decompor a questão principal.

### Exemplos

* Onde os contatos são registrados?
* Quem acompanha as propostas?
* Como a próxima ação é definida?
* Que informações costumam ser perdidas?
* Que ferramentas já são utilizadas?

---

## 5.3 Hipótese

Explicação provisória a ser examinada.

### Exemplo

> As perdas de continuidade podem estar relacionadas à dispersão das informações e à ausência de uma rotina de acompanhamento.

---

## 5.4 Fonte

Origem da informação.

Pode ser:

* pessoa;
* documento;
* sistema;
* dado;
* processo observado;
* material de comunicação;
* registro histórico;
* fonte externa.

---

## 5.5 Evidência

Informação utilizada para sustentar, questionar ou reformular uma hipótese.

---

## 5.6 Interpretação

Significado atribuído à evidência no contexto da investigação.

---

## 5.7 Achado

Conclusão diagnóstica estruturada, produzida a partir da análise de um conjunto de evidências.

---

# 6. Identificação das evidências

Cada evidência relevante deve receber um identificador.

Utilizar o padrão:

```text
EVD-NNN
```

### Exemplos

```text
EVD-001
EVD-002
EVD-003
```

O identificador deve ser único dentro de cada diagnóstico.

Quando o volume de evidências for elevado, pode-se incluir o identificador do diagnóstico:

```text
DIA-2026-001-EVD-001
```

O ID permite que:

* relatórios façam referência à evidência;
* achados indiquem suas bases;
* correções sejam rastreadas;
* fontes permaneçam vinculadas;
* divergências sejam localizadas.

---

# 7. Identificação das fontes

As fontes também podem receber identificadores.

## Pessoas entrevistadas

```text
ENT-001
ENT-002
```

## Observações

```text
OBS-001
OBS-002
```

## Documentos

```text
DOC-001
DOC-002
```

## Conjuntos de dados

```text
DAD-001
DAD-002
```

## Sistemas ou ferramentas

```text
SIS-001
SIS-002
```

## Materiais externos

```text
EXT-001
EXT-002
```

Em documentos destinados ao cliente, os identificadores podem substituir nomes quando a exposição da fonte não for necessária.

---

# 8. Tipos de evidência

Cada registro deve indicar o tipo de evidência.

---

## 8.1 Declarada

Informação fornecida por uma pessoa.

### Exemplos

* relato de entrevista;
* resposta de questionário;
* declaração em reunião;
* explicação sobre um processo.

---

## 8.2 Documental

Informação presente em documento ou registro.

### Exemplos

* contrato;
* proposta;
* procedimento;
* planejamento;
* mensagem;
* relatório;
* pauta;
* arquivo institucional.

---

## 8.3 Observacional

Informação obtida por observação direta.

### Exemplos

* sequência real de execução;
* comportamento durante reunião;
* uso de ferramentas;
* interrupções;
* transferência de informações.

---

## 8.4 Quantitativa

Informação expressa numericamente.

### Exemplos

* quantidade;
* tempo;
* taxa;
* custo;
* frequência;
* volume;
* conversão.

---

## 8.5 Sistêmica

Informação extraída de plataforma ou sistema.

### Exemplos

* histórico de CRM;
* registro de edição;
* log;
* status de tarefas;
* dados de atendimento.

---

## 8.6 Comparativa

Informação produzida pela comparação entre situações.

### Exemplos

* processo prescrito e processo praticado;
* dois períodos;
* diferentes áreas;
* resultado esperado e realizado;
* experiências de dois públicos.

---

## 8.7 Inferencial

Conclusão indireta derivada de outras informações.

Evidências inferenciais exigem maior cuidado e não devem ser apresentadas como observação direta.

---

# 9. Estrutura principal da matriz

A matriz pode ser organizada com os seguintes campos:

| Campo                     | Função                                            |
| ------------------------- | ------------------------------------------------- |
| **ID**                    | Identificar a evidência                           |
| **Questão**               | Indicar qual pergunta está sendo investigada      |
| **Hipótese relacionada**  | Mostrar que explicação está sendo examinada       |
| **Fonte**                 | Registrar a origem                                |
| **Tipo**                  | Classificar a natureza da evidência               |
| **Data ou período**       | Situar temporalmente                              |
| **Evidência**             | Descrever o que foi observado ou relatado         |
| **Interpretação inicial** | Registrar o significado possível                  |
| **Convergências**         | Identificar outras evidências compatíveis         |
| **Divergências**          | Registrar contradições                            |
| **Qualidade**             | Avaliar a força da evidência                      |
| **Confiança**             | Indicar o grau de confiança da interpretação      |
| **Lacuna**                | Registrar o que ainda falta                       |
| **Ação necessária**       | Definir aprofundamento, validação ou encerramento |
| **Achado relacionado**    | Vincular a conclusão diagnóstica                  |
| **Sensibilidade**         | Definir cuidados de acesso e exposição            |

---

# 10. Modelo completo

```markdown
| ID | Questão | Hipótese | Fonte | Tipo | Data/período | Evidência | Interpretação inicial | Convergências | Divergências | Qualidade | Confiança | Lacuna | Ação necessária | Achado relacionado | Sensibilidade |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| EVD-001 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
```

Em diagnósticos pequenos, a matriz pode ser reduzida.

---

# 11. Modelo reduzido

Para diagnósticos focais:

```markdown
| ID | Pergunta | Fonte | Evidência | Interpretação | Confiança | Lacuna ou próximo passo |
|---|---|---|---|---|---|---|
| EVD-001 |  |  |  |  |  |  |
```

A versão reduzida não elimina a necessidade de distinguir evidência e interpretação.

---

# 12. Registro da evidência

O campo **Evidência** deve conter uma descrição precisa e suficientemente contextualizada.

Deve informar, quando pertinente:

* o que aconteceu;
* onde;
* quando;
* quem participou;
* frequência;
* quantidade;
* documento ou sistema de origem;
* exemplo concreto.

---

## 12.1 Formulação adequada

> Das 18 propostas enviadas entre maio e julho de 2026, 11 não possuíam próxima ação registrada no documento ou no sistema analisado.

---

## 12.2 Formulação inadequada

> As propostas não são acompanhadas direito.

A segunda formulação mistura:

* observação;
* avaliação;
* generalização;
* linguagem imprecisa.

---

# 13. Registro da interpretação

A interpretação deve explicar o significado possível da evidência sem exceder seu alcance.

### Exemplo

> A ausência de próxima ação registrada sugere que o acompanhamento depende de memória ou de comunicações não centralizadas.

Quando a interpretação ainda for frágil, utilizar linguagem proporcional:

* pode indicar;
* sugere;
* é compatível com;
* uma explicação possível;
* ainda precisa ser confrontado com;
* não é suficiente para afirmar.

---

# 14. Avaliação da qualidade da evidência

Cada evidência pode ser avaliada a partir de seis critérios:

1. pertinência;
2. proximidade;
3. atualidade;
4. integridade;
5. rastreabilidade;
6. convergência.

---

## 14.1 Pertinência

A evidência ajuda diretamente a responder à questão?

* **Alta:** relação direta.
* **Média:** relação parcial ou contextual.
* **Baixa:** relação indireta.

---

## 14.2 Proximidade

A fonte está próxima do fenômeno?

* **Alta:** observação direta, registro original ou pessoa responsável pela execução.
* **Média:** pessoa envolvida indiretamente ou documento secundário.
* **Baixa:** informação de terceiros sem verificação.

Proximidade não significa neutralidade.

Quem está próximo também pode possuir visão parcial.

---

## 14.3 Atualidade

A evidência representa o período investigado?

* **Alta:** atual ou diretamente correspondente.
* **Média:** anterior, mas ainda possivelmente válida.
* **Baixa:** desatualizada ou sem data conhecida.

---

## 14.4 Integridade

A informação está suficientemente completa?

* **Alta:** registro completo e contextualizado.
* **Média:** existem lacunas que não inviabilizam seu uso.
* **Baixa:** ausência de partes relevantes.

---

## 14.5 Rastreabilidade

É possível localizar e verificar a origem?

* **Alta:** fonte, data e contexto identificados.
* **Média:** origem conhecida, mas registro parcial.
* **Baixa:** origem incerta ou impossível de reconstruir.

---

## 14.6 Convergência

Outras fontes independentes sustentam informação semelhante?

* **Alta:** múltiplas fontes independentes.
* **Média:** alguma sustentação adicional.
* **Baixa:** fonte isolada ou contradita.

---

# 15. Classificação geral da qualidade

A classificação geral não precisa ser calculada matematicamente.

Ela deve resultar do julgamento dos critérios anteriores.

## Qualidade alta

A evidência é:

* pertinente;
* atual;
* rastreável;
* suficientemente íntegra;
* próxima do fenômeno;
* apoiada por outras fontes ou diretamente verificável.

## Qualidade moderada

A evidência é útil, mas apresenta:

* lacuna;
* dependência de relato;
* contexto parcial;
* atualidade limitada;
* pouca triangulação.

## Qualidade baixa

A evidência:

* possui origem incerta;
* é pouco pertinente;
* está desatualizada;
* depende de inferência ampla;
* apresenta contradições não examinadas;
* não pode ser verificada.

Evidência de qualidade baixa pode permanecer na matriz.

Ela apenas não deve sustentar, sozinha, conclusão relevante.

---

# 16. Grau de confiança da interpretação

A qualidade da evidência e a confiança da interpretação são relacionadas, mas não idênticas.

Uma evidência pode ser confiável, mas permitir mais de uma interpretação.

---

## 16.1 Confiança alta

Utilizar quando:

* existem evidências de boa qualidade;
* diferentes fontes convergem;
* explicações alternativas foram examinadas;
* a relação com o fenômeno é direta;
* não existem lacunas capazes de alterar significativamente a conclusão.

---

## 16.2 Confiança moderada

Utilizar quando:

* existem evidências relevantes;
* a interpretação é plausível;
* permanecem lacunas;
* existem explicações concorrentes;
* a triangulação é parcial.

---

## 16.3 Confiança baixa

Utilizar quando:

* a fonte é isolada;
* há pouca evidência;
* existem contradições;
* a interpretação depende de inferência extensa;
* o contexto não está suficientemente compreendido.

---

## 16.4 Inconclusiva

Utilizar quando não existe base suficiente para sustentar uma interpretação.

Nesse caso, a matriz deve indicar:

* que informação falta;
* como poderia ser obtida;
* se a lacuna impede a continuidade;
* se a incerteza será aceita.

---

# 17. Convergências

O campo **Convergências** deve registrar outras evidências que sustentam interpretação semelhante.

### Exemplo

```text
Converge com EVD-003, EVD-006 e EVD-009.
```

A convergência pode ocorrer entre:

* relato e documento;
* relato e observação;
* dado e processo;
* diferentes participantes;
* diferentes períodos.

É importante verificar se as fontes são realmente independentes.

Três pessoas repetindo uma informação originada pela mesma liderança podem representar apenas uma fonte primária reproduzida.

---

# 18. Divergências

O campo **Divergências** deve registrar evidências incompatíveis, diferentes ou parcialmente contraditórias.

### Exemplo

> A liderança afirma que todas as propostas são acompanhadas semanalmente. Os documentos analisados não apresentam registro desse acompanhamento em 11 dos 18 casos observados.

A divergência pode gerar:

* nova pergunta;
* entrevista adicional;
* observação;
* alteração do grau de confiança;
* reconhecimento de processos distintos;
* registro de perspectiva divergente.

Ela não deve ser resolvida escolhendo automaticamente a fonte com maior autoridade.

---

# 19. Lacunas

Lacuna é uma informação ausente que limita a compreensão.

As lacunas podem ser classificadas como:

---

## 19.1 Crítica

Impede conclusão responsável ou decisão relevante.

### Exemplo

Não existe acesso aos dados necessários para determinar se a queda de vendas ocorreu em toda a operação ou apenas em um canal.

---

## 19.2 Relevante

Reduz a confiança, mas não impede toda conclusão.

### Exemplo

Não foi possível entrevistar uma pessoa envolvida em uma etapa específica.

---

## 19.3 Complementar

Poderia ampliar o contexto, mas possui baixo impacto sobre a conclusão atual.

---

## 19.4 Lacuna aceita

Em alguns casos, o custo ou o tempo necessários para obter a informação são superiores ao valor provável.

A aceitação deve ser registrada com:

* justificativa;
* risco;
* impacto sobre o grau de confiança;
* responsável pela decisão.

---

# 20. Ações relacionadas à evidência

Após registrar uma evidência, podem ser definidas ações como:

* validar com outra fonte;
* localizar documento;
* entrevistar pessoa;
* observar processo;
* solicitar dado;
* comparar período;
* corrigir registro;
* reclassificar;
* anonimizar;
* descartar por irrelevância;
* incorporar ao achado;
* manter como contexto;
* encerrar investigação.

A matriz deve orientar a investigação, não apenas arquivar informações.

---

# 21. Da evidência ao achado

Um achado não deve ser criado pela simples soma de evidências.

Ele exige interpretação estruturada.

O caminho recomendado é:

1. reunir evidências relacionadas;
2. verificar qualidade;
3. identificar convergências;
4. examinar divergências;
5. considerar hipóteses concorrentes;
6. reconhecer lacunas;
7. formular interpretação;
8. definir grau de confiança;
9. registrar limites;
10. produzir o achado.

---

## 21.1 Estrutura do achado

### ID do achado

```text
ACH-NNN
```

### Título

Descrição curta.

### Afirmação

O que o diagnóstico sustenta?

### Evidências relacionadas

```text
EVD-001, EVD-003, EVD-006
```

### Interpretação

Como o conjunto foi compreendido?

### Confiança

* alta;
* moderada;
* baixa.

### Limites

O que não pode ser afirmado?

### Implicação

Por que importa?

### Encaminhamento

Preservar, corrigir, desenvolver, investigar, monitorar ou interromper.

---

# 22. Matriz de achados

Além da matriz de evidências, diagnósticos funcionais e sistêmicos podem utilizar uma síntese de achados.

```markdown
| ID | Achado | Tipo | Evidências relacionadas | Confiança | Implicação | Prioridade | Encaminhamento |
|---|---|---|---|---|---|---|---|
| ACH-001 |  |  |  |  |  |  |  |
```

## Tipos de achado

* capacidade;
* problema;
* risco;
* restrição;
* oportunidade;
* contradição;
* lacuna;
* requisito;
* questão aberta.

---

# 23. Registro de hipóteses

Hipóteses também podem ser organizadas em tabela própria.

```markdown
| ID | Hipótese | Evidências favoráveis | Evidências contrárias | Estado | Confiança | Próxima ação |
|---|---|---|---|---|---|---|
| HIP-001 |  |  |  | Em investigação |  |  |
```

## Estados possíveis

* proposta;
* em investigação;
* parcialmente sustentada;
* sustentada;
* enfraquecida;
* rejeitada;
* inconclusiva;
* substituída.

Uma hipótese rejeitada não deve ser apagada.

Ela registra aprendizado e evita repetição de caminhos já examinados.

---

# 24. Sensibilidade e acesso

Cada evidência deve ser classificada quando contiver informação com restrição de acesso.

## Pública

Pode ser compartilhada sem risco relevante.

## Interna

Destinada ao funcionamento da organização.

## Confidencial

A divulgação pode gerar risco organizacional ou comercial.

## Sensível

Envolve, por exemplo:

* dados pessoais;
* dados financeiros;
* saúde;
* conflitos;
* informações jurídicas;
* estratégia;
* propriedade intelectual;
* credenciais;
* segurança.

A matriz geral deve evitar reproduzir conteúdo sensível quando um identificador ou resumo for suficiente.

---

# 25. Minimização de dados

A matriz não deve se tornar uma cópia integral de todas as fontes.

Ela deve registrar apenas o necessário para:

* identificar;
* compreender;
* verificar;
* relacionar;
* interpretar.

Transcrições, documentos e dados originais devem permanecer em locais apropriados, com acesso compatível.

Quando possível, utilizar:

* síntese;
* referência;
* trecho mínimo;
* anonimização;
* pseudonimização.

---

# 26. Participação da inteligência artificial

A inteligência artificial pode apoiar a construção da matriz como:

* organizadora;
* classificadora;
* sintetizadora;
* comparadora;
* identificadora de padrões;
* revisora de consistência;
* geradora de perguntas;
* detectora de possíveis lacunas.

---

## 26.1 Atividades permitidas

A IA pode:

* sugerir categorias;
* relacionar notas a questões;
* identificar trechos semelhantes;
* apontar possíveis divergências;
* organizar evidências por tema;
* propor hipóteses alternativas;
* verificar campos ausentes;
* apoiar a redação de interpretações provisórias.

---

## 26.2 Limites

A IA não deve:

* inventar evidências;
* preencher lacunas como fatos;
* criar fontes inexistentes;
* alterar registros originais;
* determinar sozinha a confiabilidade;
* inferir intenção de pessoas;
* produzir avaliação psicológica;
* transformar frequência textual em importância organizacional;
* aprovar achados;
* definir a conclusão final.

---

## 26.3 Verificação humana

Toda classificação ou síntese produzida pela IA deve ser confrontada com:

* fonte original;
* contexto;
* questão diagnóstica;
* critérios metodológicos;
* julgamento humano.

---

## 26.4 Registro da participação

Quando a IA contribuir materialmente, registrar:

* sistema;
* data;
* tarefa;
* fontes fornecidas;
* medidas de proteção;
* saída utilizada;
* alterações humanas;
* pessoa responsável pela validação.

---

# 27. Controle de versões

A matriz pode mudar durante o diagnóstico.

Devem ser preservadas alterações relevantes, especialmente quando:

* evidência for corrigida;
* classificação mudar;
* hipótese for rejeitada;
* interpretação for reformulada;
* achado for alterado;
* fonte for invalidada;
* grau de confiança diminuir ou aumentar.

O histórico pode registrar:

| Data | Evidência ou achado | Alteração | Motivo | Responsável |
| ---- | ------------------- | --------- | ------ | ----------- |
|      |                     |           |        |             |

Correções não devem apagar o fato de que determinada interpretação existiu e influenciou o trabalho, quando isso for relevante para a compreensão do diagnóstico.

---

# 28. Revisão da matriz

A matriz deve ser revisada em pontos específicos.

---

## 28.1 Após a coleta inicial

Verificar:

* cobertura das perguntas;
* fontes ausentes;
* redundâncias;
* hipóteses não examinadas.

---

## 28.2 Antes da formulação dos achados

Verificar:

* evidências sem rastreabilidade;
* mistura entre fato e interpretação;
* divergências ignoradas;
* qualidade;
* confiança;
* lacunas.

---

## 28.3 Antes da validação com o cliente

Verificar:

* linguagem;
* exposição de fontes;
* dados sensíveis;
* afirmações sem suporte;
* coerência com o escopo.

---

## 28.4 Antes do encerramento

Verificar:

* achados relacionados;
* hipóteses atualizadas;
* lacunas registradas;
* evidências descartadas;
* histórico;
* destinação dos dados.

---

# 29. Critérios mínimos de completude

Uma matriz está suficientemente completa quando:

* [ ] cada questão relevante possui evidências relacionadas;
* [ ] as fontes estão identificadas;
* [ ] evidência e interpretação estão separadas;
* [ ] os tipos de evidência foram classificados;
* [ ] a qualidade foi avaliada;
* [ ] convergências relevantes estão registradas;
* [ ] divergências não foram apagadas;
* [ ] lacunas estão explícitas;
* [ ] o grau de confiança corresponde às evidências;
* [ ] cada achado pode ser reconstruído;
* [ ] dados sensíveis receberam tratamento adequado;
* [ ] a participação da IA está registrada;
* [ ] ações pendentes possuem responsável;
* [ ] o histórico relevante foi preservado.

---

# 30. Exemplo de aplicação

## Questão diagnóstica

> Como as oportunidades comerciais são acompanhadas atualmente e onde ocorre perda de continuidade?

## Hipótese inicial

> A perda de continuidade decorre principalmente da dispersão dos registros e da ausência de próxima ação definida.

### Matriz

| ID      | Pergunta                          | Fonte               | Tipo          | Evidência                                                                                        | Interpretação                                                           | Qualidade | Confiança | Divergência ou lacuna                          | Ação                         |
| ------- | --------------------------------- | ------------------- | ------------- | ------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------- | --------- | --------- | ---------------------------------------------- | ---------------------------- |
| EVD-001 | Onde os contatos são registrados? | ENT-001 — fundadora | Declarada     | A fundadora relata utilizar WhatsApp, Instagram, e-mail e caderno.                               | As informações podem estar distribuídas entre diferentes ambientes.     | Moderada  | Moderada  | Verificar registros reais.                     | Analisar canais utilizados.  |
| EVD-002 | Onde os contatos são registrados? | OBS-001             | Observacional | Foram observados contatos ativos em três aplicativos e em anotações físicas.                     | A dispersão relatada ocorre na prática.                                 | Alta      | Alta      | Não foi analisado o e-mail.                    | Incluir o e-mail na amostra. |
| EVD-003 | Como a próxima ação é definida?   | DOC-001 — propostas | Documental    | Onze de dezoito propostas não possuíam próxima ação registrada.                                  | O acompanhamento pode depender da memória da fundadora.                 | Alta      | Moderada  | Pode existir acompanhamento fora do documento. | Verificar mensagens.         |
| EVD-004 | Existem perdas?                   | ENT-001             | Declarada     | A fundadora recorda três oportunidades que deixaram de receber retorno.                          | Existem sinais de perda de continuidade.                                | Moderada  | Moderada  | Relato depende de memória.                     | Buscar casos nos canais.     |
| EVD-005 | Existem perdas?                   | SIS-001 — mensagens | Sistêmica     | Foram localizadas duas conversas em que o cliente solicitou continuidade sem resposta posterior. | Ao menos parte das oportunidades não recebe acompanhamento sistemático. | Alta      | Alta      | Amostra limitada.                              | Comparar período maior.      |

---

## Achado resultante

### ACH-001 — Acompanhamento comercial dependente de registros dispersos

**Afirmação:**
O acompanhamento das oportunidades comerciais depende de informações distribuídas entre múltiplos canais e não possui uma rotina consistente de registro da próxima ação.

**Evidências:**
EVD-001, EVD-002, EVD-003 e EVD-005.

**Interpretação:**
A dispersão não constitui apenas uma preferência de organização. Ela reduz a capacidade de visualizar oportunidades e aumenta a dependência da memória da fundadora.

**Confiança:**
Alta quanto à dispersão; moderada quanto à extensão total das perdas.

**Limites:**
O período analisado é restrito e nem todos os canais foram examinados integralmente.

**Implicação:**
O crescimento do volume de contatos tende a ampliar perdas e sobrecarga.

**Encaminhamento:**
Desenvolver no Módulo 3 uma estrutura mínima de acompanhamento antes de selecionar ferramenta definitiva.

---

# 31. Antipadrões

## 31.1 Matriz como depósito

Inserir grandes quantidades de informação sem relação com perguntas ou hipóteses.

---

## 31.2 Interpretação escrita como evidência

> A equipe resiste à mudança.

Essa formulação é uma interpretação e exige evidências específicas.

---

## 31.3 Qualidade definida por cargo

Considerar a informação mais confiável apenas porque foi fornecida por liderança.

---

## 31.4 Contagem como verdade

Tratar o número de vezes que uma percepção foi repetida como prova suficiente de sua correção.

---

## 31.5 Divergência eliminada

Excluir informações incompatíveis para produzir narrativa mais simples.

---

## 31.6 Confiança sem justificativa

Classificar uma conclusão como alta sem avaliar qualidade, convergência e lacunas.

---

## 31.7 Matriz produzida apenas pela IA

Aceitar classificações, interpretações ou achados sem retornar às fontes originais.

---

## 31.8 Detalhamento excessivo

Transformar a matriz em transcrição completa e inviabilizar seu uso analítico.

---

## 31.9 Evidência sem data

Utilizar informação sem considerar o período a que pertence.

---

## 31.10 Achado sem implicação

Produzir afirmação correta, mas sem explicar por que ela é relevante para a organização.

---

# 32. Perguntas de controle

Antes de utilizar uma evidência em um achado, perguntar:

1. Qual é a fonte?
2. O que foi efetivamente observado ou relatado?
3. Que parte constitui interpretação?
4. A evidência está dentro do escopo?
5. Ela representa o período investigado?
6. Existe forma de verificá-la?
7. Outra fonte converge?
8. Existe evidência contrária?
9. Há explicação alternativa?
10. Que lacuna permanece?
11. Qual grau de confiança é justificável?
12. A linguagem excede a evidência?
13. Existe informação sensível desnecessária?
14. A IA influenciou a classificação?
15. Esta evidência é necessária para a decisão ou o achado?

---

# 33. Invariantes da matriz

## Invariante 1

Nenhuma interpretação deve ser registrada como se fosse observação direta.

## Invariante 2

Nenhum achado relevante deve existir sem evidências relacionadas.

## Invariante 3

Nenhuma divergência material deve ser omitida para aumentar artificialmente a coerência.

## Invariante 4

Nenhuma fonte deve ser considerada completa apenas por ocupar posição de autoridade.

## Invariante 5

Nenhuma ausência de registro deve ser tratada automaticamente como ausência de prática.

## Invariante 6

Nenhum grau de confiança deve exceder a força das evidências.

## Invariante 7

Nenhuma evidência de baixa qualidade deve sustentar sozinha decisão de alto impacto.

## Invariante 8

Nenhum dado sensível deve ser reproduzido quando uma referência ou síntese for suficiente.

## Invariante 9

Nenhuma classificação produzida por IA deve ser aceita sem verificação humana.

## Invariante 10

Nenhuma evidência deve permanecer na matriz sem relação com uma finalidade diagnóstica.

---

# 34. Estrutura sugerida nos registros reais

```text
DIA-AAAA-NNN-nome-do-diagnostico/
├── matriz-de-evidencias.md
├── registro-de-fontes.md
├── registro-de-hipoteses.md
├── matriz-de-achados.md
└── fontes/
    ├── entrevistas/
    ├── observacoes/
    ├── documentos/
    └── dados/
```

Em diagnósticos focais, esses registros podem ser reunidos em um único arquivo.

Em diagnósticos sistêmicos, recomenda-se separá-los para facilitar manutenção e controle de acesso.

---

# 35. Relação com a síntese diagnóstica

A síntese diagnóstica deve apresentar apenas os elementos necessários para compreensão e decisão.

A Matriz de Evidências preserva a base analítica detalhada.

A relação entre ambas deve permitir:

```text
Síntese
   ↓
Achado
   ↓
Evidências
   ↓
Fontes originais
```

Essa cadeia constitui a rastreabilidade do diagnóstico.

---

# 36. Aprendizagem metodológica

Ao final de cada diagnóstico, revisar:

* que tipos de evidência foram mais úteis;
* quais fontes apresentaram baixa qualidade;
* quais lacunas poderiam ter sido previstas;
* que campos da matriz foram excessivos;
* que classificações foram ambíguas;
* como a IA contribuiu ou distorceu;
* que perguntas de controle precisam ser aprimoradas;
* que padrões podem ser reutilizados;
* que alterações devem ser realizadas no template.

A matriz deve evoluir com a prática.

Ela não deve se tornar uma estrutura rígida que aumente o trabalho sem ampliar compreensão.

---

# 37. Princípio de encerramento

A Matriz de Evidências existe para tornar visível a arquitetura do raciocínio diagnóstico.

Ela deve permitir que o Estúdio LICHTARA produza conclusões sem apagar:

* a origem das informações;
* as diferenças entre fontes;
* os limites do conhecimento;
* as hipóteses rejeitadas;
* as incertezas;
* a participação interpretativa humana.

Uma conclusão confiável não é aquela apresentada com maior segurança verbal.

É aquela cujo caminho pode ser examinado, questionado e reconstruído.

---

# 38. Síntese

A Matriz de Evidências transforma:

> perguntas em investigação;
> fontes em registros;
> registros em evidências;
> evidências em interpretações;
> interpretações em achados;
> achados em compreensão;
> compreensão em base para decisão.

Seu papel é impedir que o diagnóstico dependa apenas da autoridade de quem o produz.

---

# 39. Histórico de versões

| Versão | Data       | Alteração                                 | Responsável      |
| ------ | ---------- | ----------------------------------------- | ---------------- |
| 0.1    | 01/08/2026 | Criação do método da Matriz de Evidências | Estúdio LICHTARA |

Com este arquivo, o núcleo metodológico do Módulo 2 está estabelecido: **fundamentos, protocolo e rastreabilidade das evidências**. O próximo movimento coerente é começar os templates operacionais, iniciando pelo `briefing-de-diagnostico.md`, que será a porta de entrada de cada investigação real.
