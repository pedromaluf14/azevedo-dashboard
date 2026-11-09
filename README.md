# Painel de campanhas · Azevedo Imobiliária

Painel de Meta Ads da Azevedo no padrão LUZIAC. Um GitHub Action busca os dados no
Windsor.ai de hora em hora, grava `metrics.json` e a página (`index.html`) lê esse arquivo.

- **Lead** = "Conversas por mensagem iniciadas" (WhatsApp), o "Resultado" do Gerenciador.
- **Empreendimentos** saem automaticamente do nome da campanha, sem as etiquetas entre colchetes.
- **FIV · LUZIAC**: campanhas com `[FIV]` no nome têm aba própria. As conversas vão para a equipe da LUZIAC, que atende e agenda a visita.
- **Instagram**: a campanha com "Engajamento" no nome vira o card de topo do funil (visitas ao perfil e novos seguidores).

Secret necessário: `WINDSOR_API_KEY` (Settings → Secrets and variables → Actions).
