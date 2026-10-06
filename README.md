# Aroeira Odontologia — peça de portfólio

Cinco roteiros de anúncio para Instagram e Facebook (Feed e Stories) de uma clínica
odontológica, feitos como demonstração de trabalho para prospects do nicho de saúde e odontologia.

**Aroeira Odontologia é um negócio fictício.** Nenhum dado real de cliente foi usado — nome,
serviços e localização são ilustrativos, e isso é declarado em cada arquivo. Nota e número de
avaliações do Google ficam como variáveis (`[NOTA]` e `[N]`), para não inventar prova social que
pareça real.

## Ver o site

Publicado via GitHub Pages: https://jhandersonsites.github.io/portfolio-anuncios-odontologia/

## O que tem aqui

Um anúncio para cada "dor" do paciente, todos na mesma estrutura:
**Gancho forte → Problema → Solução (a clínica) → CTA**.

| # | Dor | Foco | Arquivo |
|---|-----|------|---------|
| 1 | O Medroso | Manejo de ansiedade e atendimento humanizado | [anuncios/01-medroso.md](anuncios/01-medroso.md) |
| 2 | O Vaidoso | Estética, sorriso natural e autoconfiança (lentes e clareamento) | [anuncios/02-vaidoso.md](anuncios/02-vaidoso.md) |
| 3 | O Funcional | Dentes perdidos e próteses antigas (implantes e reabilitação) | [anuncios/03-funcional.md](anuncios/03-funcional.md) |
| 4 | A Conveniência | Localização central e facilidade de agendamento | [anuncios/04-conveniencia.md](anuncios/04-conveniencia.md) |
| 5 | A Prova Social | Nota e avaliações do Google como autoridade imediata | [anuncios/05-prova-social.md](anuncios/05-prova-social.md) |

Cada arquivo traz o texto de Feed, um gancho alternativo para teste A/B, título e descrição, o
roteiro de Stories em 4 telas e o criativo sugerido (imagem ou vídeo).

## Como foram pensados

- Linguagem elegante, mas acessível
- Ganchos escritos sem afirmar condição do leitor, para não esbarrar na política de atributos
  pessoais da Meta
- Fora dos textos: preço, parcelamento, "gratuito", superlativos, promessas de resultado e
  antes/depois — itens que costumam ser restritos pelo CFO e/ou pela Meta
- Gancho com no máximo ~125 caracteres, para aparecer inteiro antes do "ver mais"
- Feed em 4:5 · Stories em 9:16, com topo e base livres de texto

## Antes de usar com um cliente real

- Validar os textos com o responsável técnico (RT) da clínica
- Incluir nome da clínica e RT/CRO na legenda ou na arte
- Usar pacientes nos criativos só com termo de autorização de imagem
- Preencher `[NOTA]` e `[N]` com o que o perfil do Google mostra. Média 5,0 não garante que todas
  as avaliações sejam de 5 estrelas: escreva "nota 5,0 com N avaliações", e não "N avaliações
  5 estrelas", a menos que seja o caso
- Só citar trechos de avaliação se forem reais e vierem do perfil da clínica

## Stack

Arquivo único `index.html`, HTML + CSS puro (sem framework, sem build, sem JavaScript), Google
Fonts como única dependência externa. Mobile-first, acessível (contraste AA, foco visível,
`prefers-reduced-motion`).

Os textos do site espelham os arquivos em [`anuncios/`](anuncios/), que continuam sendo a fonte
em Markdown.
