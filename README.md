<p align="center">
  <img src="imagens/chapeu.png" alt="Chapéu de cozinheiro" width="140">
</p>

<h1 align="center">D'Ana Comida Caseira</h1>

<p align="center">
  Programa para Windows que organiza os pedidos do dia, a contagem das quentinhas e o fechamento das contas.
</p>

<p align="center">
  <a href="../../releases/latest"><b>⬇ Baixar a versão mais nova</b></a>
</p>

---

## O que o programa faz

- **Pedidos do dia**: lança cliente, prato e quantidade só pelo teclado e mostra a lista em ordem alfabética, do mais antigo ou do mais recente.
- **Contagem do dia**: soma quantas quentinhas de cada prato vão sair.
- **Fechar conta**: mostra quem está devendo, gera a cobrança e o recibo em PDF com QR Code do Pix e imprime na impressora térmica.
- **Comprovante de pagamento**: lê o comprovante (PDF ou foto), acha o valor e sugere de qual cliente é.
- **Clientes e produtos**: cadastro com preços.
- **Visual confortável**: letra grande, modo claro e modo noturno, e menu lateral que pode ser recolhido.

## Como instalar

1. Clique em **[Baixar a versão mais nova](../../releases/latest)**.
2. Em *Assets*, baixe o arquivo **`DAna.exe`**.
3. Coloque o arquivo numa pasta do computador (por exemplo, na Área de Trabalho) e abra.

Não precisa instalar mais nada.

## Atualizações automáticas

Toda vez que o programa abre, ele confere aqui se existe uma versão mais nova. Quando existe, aparece o aviso
**"Nova versão disponível"** com dois botões:

- **Atualizar agora**: baixa a versão nova, troca o programa e abre de novo sozinho.
- **Depois**: lembra de novo na próxima vez que o programa abrir.

Pedidos, clientes e configurações **não são mexidos** pela atualização. Eles ficam guardados no próprio
computador, em `%APPDATA%\DAna`, com cópia de segurança diária.

Também dá para procurar na hora em **Configurações → Sobre → Procurar atualização**.

## Privacidade

Esta página tem **só o programa**. Nenhum dado de cliente, pedido ou pagamento é enviado para cá.

---

<p align="center"><sub>Feito com Rust e <a href="https://slint.dev">Slint</a>.</sub></p>
