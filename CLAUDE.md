# Contexto do projeto

Site da **Perfect Clínica Avançada** (pilates, fisioterapia, yoga, dry needling, laser e Sala Moviment: musculação, crosspilates e funcional), em Contagem/MG. Em 2026-11-12 o template da madeireira Essência Madeiras foi convertido para a Perfect, mantendo o layout; a versão da madeireira está em original-madeireira/. Continue a partir do código existente.

## Dados reais da Perfect

- Endereço: R. Vítor Diniz Moreira, 61 - São Gonçalo, Contagem - MG, 32042-020.
- WhatsApp: (31) 97159-8301 (https://wa.me/5531971598301). Instagram: @perfectclinicaavancada.
- Horários e valores NÃO confirmados: não publicar. Não inventar depoimentos, números ou certificações.
- Logo: assets/perfect/logo.svg. Cor de destaque: verde-água (#0fa39b / #0b7f78); os tons de madeira do template foram convertidos para verde-água. Não refaça do zero e não converta para outro framework sem solicitação.

## Design aprovado

- Fundo branco, textos pretos e detalhes em verde-água da Perfect.
- DM Sans é a fonte principal; preservar o uso de Playfair Display em destaque na hero.
- Preservar a tipografia atual de cada seção, inclusive localização.
- Cabeçalho branco, logo em SVG, navegação e botão de orçamento. Altura reduzida recentemente: 86px desktop e 74px celular.
- Fotos sem sombreado branco ou degradê branco. Preservar o contraste escuro discreto da hero.
- Cards de produtos alinhados, com fresta de 6px. Preservar comportamento de destaque e rolagem no celular.
- Sobre a empresa com duas imagens sobrepostas e texto ao lado.
- Introdução dos produtos sem caixa: “Encontre a madeira para o seu projeto.”
- Rodapé claro com a mesma logo, seções, Instagram e contatos ilustrativos.
- Não restaurar as seções removidas: serviços, processo, faixa de categorias e CTA com deck “Da primeira peça ao último detalhe”.

## Seções e navegação

`#inicio`, `#sobre`, `#produtos`, `#por-que-escolher`, `#inspiracoes`, `#perguntas-frequentes`, `#localizacao` e rodapé.

## Funcionalidades

- Menu expansível no celular com aria-expanded e fechamento ao selecionar uma seção ou apertar Escape.
- Botões de orçamento abrem o mesmo diálogo.
- Cards abrem diálogo de produto e permitem preparar cotação da linha escolhida.
- O formulário abre o WhatsApp da Perfect com a mensagem pronta (nada é enviado sem o visitante confirmar no WhatsApp).
- FAQ usa details/summary.
- Mapa do Google embutido e botões Como chegar (Google Maps) e Waze com o endereço real.
- Rodapé com WhatsApp, Instagram e endereço reais da Perfect.

## Trabalho no código

HTML, estilos e script estão em `index.html`. Há regras CSS acumuladas de ajustes anteriores; as regras finais prevalecem. Preserve o resultado visual ao reorganizar. Imagens locais estão em `assets/`; algumas fotos de versões anteriores foram preservadas por compatibilidade. Não remover arquivos sem checar referências no HTML e CSS.

Para conferir, rode `npm run dev` e verifique desktop e celular. Verifique navegação, menu, FAQ e modais ao alterar partes relacionadas. Não adicionar estatísticas, depoimentos, certificações ou promessas comerciais sem confirmação do usuário.
