# Conversa em foco

A página organiza uma ação simples: iniciar uma conversa. A apresentação ampla cria identidade sem competir com os campos. O formulário mantém rótulos permanentes, contornos nítidos e uma ordem que se percorre rapidamente. A referência visual gerada está em `design-reference.png`; a implementação segue a estrutura e a legibilidade dessa direção, preservando os textos e o comportamento reais do projeto.

O grafite e o verde claro dão ao tema escuro uma presença própria. No tema claro, a mesma hierarquia usa papel claro, tinta verde profunda e um acento mais fechado para manter o contraste. A alternância fica visível no cabeçalho e a escolha é lembrada no navegador.

Instrument Sans sustenta título e controles. A diferença de escala cria a composição; bordas finas e intervalos regulares organizam os campos. Há uma única ação principal. O aviso de demonstração aparece antes do preenchimento, pois a ausência de serviço de envio não pode ficar escondida atrás do botão.

O movimento acompanha entrada, foco, processamento e confirmação. É discreto o suficiente para não atrapalhar a leitura e respeita a preferência por movimento reduzido.

## Contrato da página

- Objetivo: facilitar contato de recrutadores, clientes e colaboradores.
- Composição: apresentação à esquerda, formulário à direita; coluna única abaixo de 960 px.
- Conteúdo: título e descrição solicitados; perfil configurável; nome, e-mail, assunto, orçamento opcional e mensagem.
- Tema escuro inicial e tema claro opcional, com preferência local.
- Estados: vazio, foco, erro junto ao campo, envio pendente, conclusão e falha recuperável.
- Demonstração: identificação permanente antes de qualquer ação; nenhuma requisição e nenhuma confirmação fictícia de envio.
- Entrega: HTML semântico, CSS adaptável, GSAP local com redução de movimento e envio configurável sem credenciais públicas.
- Critério de acabamento: revisar os dois temas em desktop e celular, estados de erro, teclado e preservação do texto após falha.

## Referências técnicas

- GSAP: https://gsap.com/docs/v3/GSAP/gsap.matchMedia()/
- Formspree AJAX: https://help.formspree.io/articles/building-your-form/submit-forms-with-javascript-ajax/
