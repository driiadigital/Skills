# Instruções para o Projeto "Revisão semanal" (bloco a acrescentar)

Copiar o texto abaixo para as instruções do Projeto, substituindo qualquer instrução anterior sobre o modelo HTML ou o design do dashboard. As regras de extração das reuniões ficam como estão.

---

## Modelo do dashboard

- O dashboard é gerado a partir do ficheiro `dashboard-revisao-semanal-work-management.html`, que está nos ficheiros do projeto. Não usar outro modelo nem versões anteriores.
- Copiar o ficheiro inteiro, sem alterações, e substituir apenas o conteúdo do bloco `<script id="dados-semana">` (de `/* ===== DADOS DA SEMANA ===== */` até `</script>`).
- Não alterar o `<style>`, a estrutura HTML nem o segundo `<script>` (desenho, filtros, pesquisa, verificação, impressão).
- O bloco de dados define estas constantes, sempre todas e com estes nomes: `SEMANA`, `M`, `PRIOS`, `PERGUNTA`, `CARDS`, `TASKS`, `DECS`, `BEM`, `PADROES`, `EXCLUIDAS`, `NOMES`, `RESSALVAS`, `DESTAQUES`. Os dados que estão no modelo são de uma semana anterior e servem só de exemplo de formato: substituí-los todos.
- Seguir as regras dos dados escritas no comentário do topo do modelo (referências `[reunião, minuto]`, datas em AAAA-MM-DD, `q: null` sem responsável, `feita` só com confirmação, `desde` em tarefas antigas, estados `bloq`, `atencao`, `avanca`, `semacao`, 3 prioridades, até 3 pontos em "Correu bem" e "Padrões", até 4 destaques).
- Não escrever à mão números, contagens, estado da semana nem datas por extenso: o código calcula tudo a partir dos dados.
- Não usar travessões nem datas relativas (hoje, amanhã, ontem) nos textos.
- Antes de entregar, confirmar que o painel "Verificação" não aparece no topo do dashboard. Se aparecer, corrigir os dados indicados e voltar a gerar.
- Nome do ficheiro final: `revisao-semanal_AAAA-MM-DD_AAAA-MM-DD.html` (início e fim da semana).
