# BRIEF — Peça de portfólio · Aroeira Odontologia (projeto conceitual)

> **Isto é um projeto conceitual.** A clínica não existe. Serve como demonstração do meu
> trabalho para prospects do nicho de saúde e odontologia.
> Nenhum dado real de cliente pode entrar aqui.

## Objetivo

Cinco roteiros de anúncio para Instagram e Facebook (Feed e Stories) que eu possa mostrar a
qualquer prospect do nicho sem depender de autorização de ninguém. Precisam estar **completos**:
texto pronto para usar, roteiro de Stories e criativo sugerido. A única exceção, deliberada, é a
nota e o número de avaliações do Google, que ficam como variáveis — prova social não se inventa.

## A clínica (fictícia)

- **Nome:** Aroeira Odontologia
- **Praça:** Vitória — ES, Centro
- **Posicionamento:** clínica completa, com foco em prevenção, estética e reabilitação,
  atendimento humanizado e tecnologia digital
- **Serviços:** clínico geral · clareamento, lentes e facetas · implantes · endodontia · urgências
- **Endereço, telefone e WhatsApp:** não exibir. Os textos usam "Centro de Vitória" e o CTA padrão

## Estrutura de cada anúncio

Gancho forte → Problema → Solução (a clínica) → CTA

**CTA fixo:** "Clique no botão e agende sua avaliação via WhatsApp."

Cada arquivo em `anuncios/` traz: texto de Feed, gancho alternativo (teste A/B), título e
descrição, roteiro de Stories em 4 telas e criativo sugerido (imagem ou vídeo).

## As cinco dores

| # | Dor | Foco | Arquivo |
|---|-----|------|---------|
| 1 | O Medroso | Manejo de ansiedade e atendimento humanizado, para quem tem trauma de dentista | [anuncios/01-medroso.md](anuncios/01-medroso.md) |
| 2 | O Vaidoso | Estética, sorriso natural e autoconfiança (lentes e clareamento) | [anuncios/02-vaidoso.md](anuncios/02-vaidoso.md) |
| 3 | O Funcional | Quem perdeu dentes ou tem prótese antiga (implantes e reabilitação) | [anuncios/03-funcional.md](anuncios/03-funcional.md) |
| 4 | A Conveniência | Localização central e facilidade de agendamento | [anuncios/04-conveniencia.md](anuncios/04-conveniencia.md) |
| 5 | A Prova Social | Nota e avaliações do Google como autoridade imediata | [anuncios/05-prova-social.md](anuncios/05-prova-social.md) |

## Regras de escrita

- Linguagem elegante, mas acessível
- Gancho com no máximo ~125 caracteres, para aparecer inteiro antes do "ver mais"
- Ganchos que não afirmam condição do leitor (política de atributos pessoais da Meta)
- Fora dos textos: preço, parcelamento, "gratuito", superlativos, promessas de resultado
  ("garantido", "sem dor") e antes/depois — itens que costumam ser restritos pelo CFO e/ou pela Meta

## Regras de conteúdo — nada que pareça real

- **Não invente nota, número de avaliações, prêmio, certificação ou volume de pacientes**
  ("5.000 sorrisos", "a melhor clínica de Vitória"). Um projeto conceitual não precisa mentir
  para ser convincente
- Sem depoimentos de pacientes. Onde o anúncio de prova social comporta uma avaliação, ela fica
  como espaço opcional, a ser preenchido com um trecho real do perfil do cliente
- Sem imagens de antes e depois

## O site

Página única publicada via GitHub Pages, no mesmo padrão das outras peças de portfólio.

- Arquivo único `index.html` autocontido, CSS em `<style>`, sem framework, sem build, sem JavaScript
- Mobile-first, a partir de 360px, sem rolagem horizontal
- Corpo com no mínimo 16px; toque mínimo de 44x44px; contraste mínimo de 4.5:1
- HTML semântico, um único `h1`; foco visível no teclado; `prefers-reduced-motion` respeitado
- Google Fonts permitido (Fraunces e DM Sans); nenhuma outra dependência externa
- `lang="pt-BR"`, Open Graph completo, imagem de compartilhamento em `img/og.png`
- **Sem** dados estruturados `LocalBusiness` — a clínica não existe e não deve ser indexada como real
- Rodapé com a linha: "Projeto conceitual — esta clínica é fictícia"
- Os textos do site espelham os arquivos de `anuncios/`: ao mudar um, mude o outro

## Direção visual (ilustrativa)

- Verde-sálvia e rosa-pimenta (a cor do fruto da aroeira) sobre fundo off-white
- Títulos em serifada elegante, corpo em sans-serif limpa
- Feed em 4:5 · Stories em 9:16, com topo e base livres de texto
