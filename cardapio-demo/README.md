# Cardápio Digital Demo

Demo comercial em **HTML + CSS + JavaScript** para mostrar um cardápio digital no celular, com visual clean e funções extras para apresentação.

## Arquivos

- `index.html` → cardápio digital principal
- `feedback.html` → página separada para avaliação
- `admin.html` → painel admin com avaliações, chamados e pedidos demo
- `xlsx.bundle.js` → biblioteca local usada para gerar o relatório em Excel

## O que esta demo mostra

### Cardápio
- visual mais limpo e coerente com o restante do projeto
- busca por prato, ingrediente ou bebida
- filtros rápidos
- favoritos
- pré-pedido demo com carrinho
- envio do pedido para WhatsApp
- botão de chamada de atendimento

### Avaliação
- página separada do cardápio
- nota de **atendimento** de 1 a 5 estrelas
- nota de **comida** de 1 a 5 estrelas
- campo para comentário escrito

### Admin
- total de avaliações
- média do atendimento
- média da comida
- lista de comentários
- contagem de chamados demo
- contagem de pedidos demo
- botão **Baixar relatório** em Excel (`.xlsx`)

## Como funciona

- o cliente acessa `index.html`
- quando quiser avaliar, abre `feedback.html`
- o admin abre `admin.html`
- tudo é salvo no **mesmo navegador/dispositivo** usando `localStorage`

## Sobre o relatório

O botão **Baixar relatório** gera um arquivo Excel com:

- aba **Resumo**
- aba **Avaliações**
- aba **Solicitações**
- aba **Pedidos demo**
- colunas mais largas para leitura melhor
- acentos preservados
- nomes de campos amigáveis

## Importante

Como esta é uma demo sem backend:

- os dados não vão para internet nem banco de dados
- os dados não são compartilhados entre dispositivos diferentes
- para um projeto real, o ideal é integrar com Firebase, Supabase, banco de dados ou API própria

## Publicar no GitHub Pages

1. Crie um repositório no GitHub
2. Envie estes arquivos para a raiz do repositório
3. Vá em **Settings > Pages**
4. Ative o GitHub Pages apontando para a branch principal
5. Use o link público gerado para criar o QR Code

## Ideias de evolução para projeto real

- login de administrador
- integração com banco de dados
- painel de cozinha
- impressão de pedidos
- integração com WhatsApp oficial
- pedidos com pagamento online
