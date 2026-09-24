# Formulário do Ensaio — MPS Photography

Site estático (HTML puro) para a cliente preencher seus próprios dados e escolhas
(pacote, itens extras, forma de pagamento, direitos de imagem) e enviar tudo formatado
direto para o WhatsApp da fotógrafa, com 1 toque.

Não depende de nada exclusivo do Claude — funciona normal no GitHub Pages,
igual aos outros dois projetos (Contrato e Galeria).

## Como publicar

1. Cria um repositório novo no GitHub (ex: `Formulario-MPS-Photography`).
2. Sobe o `index.html` desta pasta.
3. Em Settings → Pages, ativa o GitHub Pages na branch main.
4. O link final fica tipo: `https://prhyiscyillah.github.io/Formulario-MPS-Photography/`

## Como usar

- Manda esse link pra cliente antes do contrato (ex: quando ela fecha o orçamento).
- Ela preenche tudo e envia pelo WhatsApp — chega uma mensagem organizada com todos
  os dados e escolhas dela.
- Você usa essas informações pra preencher o painel do Contrato Digital e gerar o
  link de assinatura pra ela.

## Importante

O número de WhatsApp que recebe as respostas está fixo no arquivo
(`WHATSAPP_FOTOGRAFA` no início do `<script>`, atualmente configurado para
5511914746140). Se esse número mudar, é só editar essa linha e subir de novo.
