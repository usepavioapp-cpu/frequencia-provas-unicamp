# Frequência de assuntos nas provas de Cálculo e Física da Unicamp

Levantamento do **Pavio, app de estudos para alunos de exatas da Unicamp**: quantas vezes cada assunto apareceu em provas antigas de seis disciplinas da graduação.

| Disciplina | Provas | Período | Questões classificadas |
|---|---|---|---|
| MA111 Cálculo I | 56 | 2008 a 2026 | 181 |
| MA141 Geometria Analítica e Vetores | 55 | 2008 a 2026 | 190 |
| MA211 Cálculo II | 62 | 2006 a 2024 | 145 |
| MA311 Cálculo III | 57 | 2007 a 2025 | 198 |
| F 128 Física Geral I | 36 | 2004 a 2023 | 181 |
| F 328 Física Geral III | 28 | 2008 a 2023 | 75 |

Arquivo: [`frequencia-assuntos-provas-unicamp.csv`](frequencia-assuntos-provas-unicamp.csv)

## Colunas
`disciplina`, `assunto`, `questoes` (quantas questões do assunto), `percentual_das_classificadas`, `questoes_classificadas`, `provas`, `ano_inicial`, `ano_final`.

## Método
- **Fontes das provas:** [unicampers/banco-de-provas](https://github.com/unicampers/banco-de-provas) e [SOS Cursão](https://soscursao.com.br/), material publicado por alunos.
- Cada questão foi classificada por assunto a partir da ementa da disciplina. **A classificação é automática e não foi revisada uma a uma.**
- Questões que não puderam ser classificadas (prova escaneada ilegível ou sem divisão em questões) ficaram fora das porcentagens.
- Provas variam de professor para professor: use para priorizar o estudo, não para descartar assunto.
- Este repositório tem só a contagem. As provas não são redistribuídas aqui.

## Leitura comentada
- Site: https://pavio-app.vercel.app/pavio
- Artigos por disciplina: https://pavio-app.vercel.app/blog

Projeto independente, sem vínculo oficial com a Unicamp. Dados de 24/11/2026. Licença dos dados: CC BY 4.0 (cite "Pavio, app de estudos para alunos de exatas da Unicamp").
