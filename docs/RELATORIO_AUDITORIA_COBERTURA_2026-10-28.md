# Auditoria de cobertura — TJSP Escrevente 2027

**Data:** 28/10/2026  
**Referência de controle:** arquivo do edital fornecido no projeto, Anexo VIII, pp. 61–63. Página oficial da banca: https://www.vunesp.com.br/TJSP2607.

## Resultado executivo

A biblioteca foi ampliada e a cobertura programática foi mapeada para os livros, mas **não está homologada nem pode ser anunciada como 100% coberta em profundidade**. A matriz anterior possuía 937 linhas; 926 estavam explicitamente marcadas como não homologadas. A nova matriz reúne 1062 linhas: 937 linhas do índice anterior (algumas representam diplomas/seções inteiros, não artigos atomizados), 30 referências a dispositivos com sufixos identificadas nas varreduras iniciais, 56 tópicos não jurídicos/redação e 39 linhas adicionais de detalhamento das seções internas do TJSP e dos títulos do Regimento.

Nova matriz: [MATRIZ_COBERTURA_ANEXO_VIII_2026-10-28.csv](MATRIZ_COBERTURA_ANEXO_VIII_2026-10-28.csv).

## Materiais criados ou ampliados

### Livros/cadernos gerais
- [Português](../livros/v3/PORTUGUES_LIVRO_TEXTO.md) — ampliado com textos não verbais, coerência/cohesão/intertextualidade e classes do edital.
- [Matemática e Raciocínio Lógico](../livros/v3/MATEMATICA_RACIOCINIO_LOGICO_LIVRO_TEXTO.md) — ampliado com sistemas, gráficos, medidas, geometria, sequências figurais e avaliação de condições.
- [Informática](../livros/v3/INFORMATICA_LIVRO_TEXTO.md) — ampliado com os recursos específicos de Word, Excel, macros, Teams e OneDrive.
- [Atualidades](../livros/v3/ATUALIDADES_CADERNO_DE_ESTUDO.md) — boletim econômico com corte em 28/10/2026; permanece necessariamente sujeito a atualização semanal.
- [Redação](../livros/v3/REDACAO_LIVRO_TEXTO.md) — livro-base existente.
- [Rubrica oficial da redação](../livros/v3/REDACAO_RUBRICA_EDITAL.md) — critérios, riscos de nota zero e protocolo de produção.

### Livros jurídicos criados
- [Direito Penal](../livros/v3/DIREITO_PENAL_LIVRO_TEXTO.md)
- [Direito Processual Penal](../livros/v3/DIREITO_PROCESSUAL_PENAL_LIVRO_TEXTO.md)
- [Direito Processual Civil](../livros/v3/DIREITO_PROCESSUAL_CIVIL_LIVRO_TEXTO.md)
- [Direito Constitucional](../livros/v3/DIREITO_CONSTITUCIONAL_LIVRO_TEXTO.md)
- [Direito Administrativo](../livros/v3/DIREITO_ADMINISTRATIVO_LIVRO_TEXTO.md)
- [Legislação Interna do TJSP](../livros/v3/LEGISLACAO_INTERNA_TJSP_LIVRO_TEXTO.md)
- [LBI — Estatuto da Pessoa com Deficiência](../livros/v3/LBI_CADERNO_ESTUDO.md)
- [Processo Penal — unidade específica anterior](../livros/v3/DIREITO_PROCESSUAL_PENAL_CPP_251_258_261_267_274.md)

## Achados que exigem atenção

1. **A matriz não é prova de cobertura substantiva.** Uma linha com referência e livro-alvo não prova que cada artigo, parágrafo, exceção, prazo ou sanção foi explicado e exercitado.
2. **Sufixos legais:** a atomização anterior contava principalmente artigos inteiros. A revisão identificou CP 313-A/313-B; CPP 394-A/396-A/400-A; Estatuto paulista 267-A–267-P (exceto K); Lei 9.099 art. 12-A; LBI art. 2-A; NSCGJ art. 27-A e arts. 189-A–189-G dentro dos intervalos do edital. Essa busca inicial não substitui uma varredura completa de sufixos em todos os diplomas.
3. **Legislação interna:** os cinco blocos de Normas da Corregedoria estão indexados, mas ainda precisam ser atomizados até o item/subitem efetivamente previsto. Regimento Interno e LC 1.111/2010 precisam de mapas por dispositivo/anexo.
4. **Atualidades:** o boletim contém indicadores econômicos verificáveis, não todos os fatos políticos, sociais, culturais e internacionais do período. Atualizar até a prova é parte do trabalho, não uma etapa que possa ser encerrada em outubro de 2026.
5. **Informática:** o texto explica os tópicos, mas falta validar operações em ambiente real do Microsoft 365 e criar exercícios práticos com arquivos.
6. **Matemática/Lógica:** as seções adicionais ampliam a cobertura conceitual; a bateria de questões ainda não é suficiente para declarar domínio de todos os subtópicos.
7. **Redação:** a rubrica foi transcrita em forma de guia a partir do edital, mas a nota de cada redação exige correção humana.

## Fronteira entre trabalho automatizável e validação humana

### Ainda automatizável/editorial
- Fazer varredura completa de artigos com sufixos, revogações e remissões.
- Criar fichas artigo a artigo, com requisitos, exceções, prazos e distinções.
- Ampliar questões por tópico e conferir cálculos/gabaritos de forma independente.
- Validar links, atualizar o índice e gerar nova matriz com rastreabilidade.
- Atualizar o boletim de Atualidades com fatos novos e datas de corte.
- Produzir versão Markdown/PDF e registrar hashes/versão.

### Exige validação humana antes de homologar
- Revisão jurídica independente da redação vigente de cada dispositivo, incluindo legislação estadual e atos internos.
- Confirmação humana de interpretações controversas e de jurisprudência aplicável.
- Teste real de operações no Microsoft 365 e revisão de acessibilidade/legibilidade dos materiais.
- Correção de redações por avaliador humano, especialmente tema, coerência, repertório e argumentação.
- Aprovação editorial final do pacote completo antes de ser tratado como material definitivo.

## Estado correto

**Materiais ampliados e mapeados; conteúdo jurídico ainda não homologado.** Não declarar “edital 100% coberto” até completar a conferência artigo a artigo e as validações indicadas. A próxima etapa de desenvolvimento deve aprofundar as 937 referências legais e a atomização das normas internas, não apenas alterar etiquetas de status.

## Compilação editorial — 28/10/2026

Foi criada a compilação única [TODAS_AS_APOSTILAS_TJSP_ESCREVENTE_2027.md](../livros/v3/TODAS_AS_APOSTILAS_TJSP_ESCREVENTE_2027.md), organizada em Conhecimentos Gerais e Conhecimentos Jurídicos, por matéria e capítulos. Ela reúne 12 cadernos/livros e preserva exercícios, gabaritos e avisos editoriais. A compilação é um índice de conveniência; não resolve lacunas de cobertura nem substitui a validação humana.

O PDF consolidado foi gerado com sucesso e commitado em `livros/v3/TODAS_AS_APOSTILAS_TJSP_ESCREVENTE_2027.pdf` (215.152 bytes; workflow de build concluído com sucesso). A versão editável está em `livros/v3/TODAS_AS_APOSTILAS_TJSP_ESCREVENTE_2027.md`. A geração confirma a existência dos artefatos, não a homologação jurídica ou a cobertura integral do edital.
