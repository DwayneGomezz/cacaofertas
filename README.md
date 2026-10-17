# cacaofertas
Bot de afiliados Shopee: busca as melhores ofertas de qualquer nicho a cada 10 minutos e monta cartões prontos (texto, imagem e link de afiliado) para copiar e colar no WhatsApp. Node.js, sem dependências.
CaçaOfertas busca produtos na API oficial de afiliados da Shopee, escolhe os melhores por uma nota que combina desconto, vendas, comissão e avaliação, evita repetir ofertas e entrega tudo numa página local com botões para copiar o texto, copiar a imagem e abrir no WhatsApp. Também aceita ofertas manuais do Mercado Livre e da Amazon. Roda no Windows com um duplo clique.

Incluí no ZIP um arquivo .gitignore, que impede o GitHub de receber o seu .env (onde ficam o App ID e o App Secret da Shopee), o histórico e os cartões locais. Antes de subir, confira que o .env não aparece na lista de arquivos que o GitHub vai enviar. Se as suas credenciais já foram enviadas alguma vez, gere novas no painel da Shopee, porque apagar o arquivo depois não remove do histórico.
