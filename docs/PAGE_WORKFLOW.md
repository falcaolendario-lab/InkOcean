# Fluxo de Páginas

## Estados

- PLANEJADA: existe no sumário, mas ainda não foi produzida.
- RASCUNHO: primeira composição em desenvolvimento.
- REVISAO: apresentada a Kili e aguardando correções ou decisão.
- APROVADA: Kili declarou explicitamente que a página passou.
- PUBLICADA: versão aprovada foi incorporada ao site e à montagem do livro.

## Regra de aprovação

Somente Kili pode alterar uma página de REVISAO para APROVADA.

Mudanças posteriores numa página aprovada criam uma nova revisão e devolvem seu estado para REVISAO até nova confirmação.

## Identificação

Cada página recebe:

- número;
- título interno;
- revisão;
- estado;
- data da última mudança;
- arquivos visuais utilizados;
- observações de aprovação.

Padrão sugerido de nome:

p001-capa-r01
p002-folha-de-rosto-r01
p003-abertura-r01

## Arquivos

- pages/drafts: versões em produção e revisão.
- pages/approved: versões aprovadas.
- assets: elementos visuais de origem.
- site: apresentação pública das páginas aprovadas.
- page-status.json: registro legível por ferramentas e pelo site.

## Formato de revisão

Para cada página, serão apresentados:

1. imagem renderizada completa;
2. objetivo da página;
3. texto utilizado;
4. recursos visuais;
5. observações técnicas relevantes.

A ausência de resposta não significa aprovação.
