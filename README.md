# Recanto do Jakinha — conceito de presença digital

Protótipo mobile-first com três caminhos visuais alternáveis na mesma página:

- **Raiz:** narrativa editorial da propriedade e das vivências.
- **Quintal:** estrutura de vitrine, com descoberta rápida de experiências e produtos.
- **Mata:** entrada imersiva com fotografia ampla e atmosfera de floresta.

Abra `index.html` localmente ou sirva esta pasta como conteúdo estático. Os botões no topo trocam a direção sem recarregar a página. O catálogo permite filtrar geleias, itens sazonais e cestas; os contatos abrem conversas pré-preenchidas no WhatsApp. Instagram e localização também estão ligados.

## Conteúdo e precisão

O conteúdo foi organizado a partir dos três prints enviados do portfólio do Recanto. Fatos sobre hospedagem, produtos, cultivo e vivências seguem o que está legível nas imagens. Preços, datas, disponibilidade, condições de visita e detalhes operacionais ficaram para confirmação direta com a equipe.

As seis fotografias em `assets/` são **imagens conceituais geradas para este protótipo**, não fotos documentais do Recanto. O rodapé informa que devem ser trocadas pelas imagens originais aprovadas antes de publicação final.

## Referências de implementação

- Frontend Design, frontend-app-builder, UI/UX Pro Max e Front-End Checklist Global.
- Sem dependências ou backend. Fontes carregam do Google Fonts; se indisponíveis, há fontes de sistema como fallback.
- Motion de entrada usa apenas opacidade e deslocamento, desativa com `prefers-reduced-motion`.

## Pendências antes de produção

- Confirmar texto institucional, nome/identidade visual e autorização para uso das fotos.
- Confirmar endereço/pino do Maps, horários, preços, temporadas, capacidade, regras de visita e disponibilidade.
- Substituir as imagens conceituais pelas fotos aprovadas pelo Recanto.
- Validar cada link de WhatsApp, Instagram e Maps com a equipe.
