# Fluxo de Páginas

## Princípio

O repositório público contém somente planejamento e material oficialmente aprovado. Rascunhos, tentativas e revisões visuais permanecem na bancada local de produção.

## Estados públicos

- PLANEJADA: existe no sumário, mas ainda não foi aprovada.
- APROVADA: Kili declarou explicitamente que a página passou.
- PUBLICADA: a versão aprovada foi incorporada ao site e à montagem do livro.

Os estados de trabalho RASCUNHO e REVISAO existem apenas durante a produção local e não são registrados no repositório.

## Regra de aprovação

Somente Kili pode aprovar uma página.

Quando Kili declarar que uma página passou:

1. a versão aprovada recebe seu número definitivo;
2. o arquivo final é adicionado a `pages/approved/`;
3. a página é incorporada ao site;
4. `page-status.json` é atualizado;
5. as alterações são enviadas ao repositório.

A ausência de resposta nunca significa aprovação.

## Alterações posteriores

Se uma página já publicada precisar mudar, a versão publicada permanece intacta enquanto a nova revisão é produzida localmente. Ela somente é substituída depois de uma nova aprovação explícita.

## Identificação

O arquivo oficial usa o número definitivo, sem número de revisão:

- `p001-capa.png`
- `p002-folha-de-rosto.png`
- `p003-abertura.png`

As revisões podem usar sufixos como `-r01`, `-r02` e `-r03` apenas na bancada local.

## Arquivos públicos

- `pages/approved/`: páginas aprovadas.
- `assets/`: elementos visuais autorizados.
- `site/`: apresentação pública das páginas aprovadas.
- `page-status.json`: registro legível por ferramentas e pelo site.

## Apresentação para aprovação

Para cada página em desenvolvimento, Kili recebe a renderização completa e pode solicitar quantas mudanças forem necessárias. O histórico de tentativas não é publicado.
