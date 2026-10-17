# Sensei Flow Automation

Gere imagens no Google Flow pelo painel lateral do Chrome ou Microsoft Edge.
Sem cadastro ou login na extensão; sujeito à cota da sua conta Google.

## Download

[Baixar a versão mais recente](https://github.com/felopes128/sensei-flow-automation-releases/releases/latest).

Em **Assets**, escolha o ZIP com **Chrome** ou **Edge** no nome.
Cada pacote inclui `LEIA-ME-INSTALACAO.txt` com o tutorial completo.

## Instalação rápida

1. Extraia o ZIP para uma pasta permanente.
2. Abra `chrome://extensions` ou `edge://extensions` no navegador escolhido.
3. Ative **Modo do desenvolvedor** e clique em **Carregar sem compactação**.
4. Selecione a pasta que contém `manifest.json`.
5. Abra o painel da extensão; não é necessário fazer login no Microstock Sensei.
6. Entre com sua conta Google no Flow, abra um projeto em https://flow.google.com/
   e clique em **Conectar aba** no painel. Cole ou importe um prompt por linha.

Mantenha o navegador e a aba abertos e o computador acordado. Pode usar outros
programas ou minimizar a janela. O aviso de depuração durante o lote é esperado.
Downloads ficam em `Sensei Flow Automation/AAAA-MM-DD/` dentro da pasta padrão
de downloads configurada no navegador. A data é o dia local em que a imagem ficou pronta.
Não é necessário escolher ou autorizar pastas.

## Recursos da versão 1.0.10

- Sem limite fixo de quantidade de prompts por lote, inclusive importação de TXT e rascunhos.
- Download direto na qualidade escolhida, 1K ou 2K, com espera de 2 a 3 segundos antes do menu.
- Fila com pausa e retomada, preservando imagens já geradas para tentar novamente o download.
- Suporte a projetos de diferentes contas Google, incluindo endereços `/u/3/project/ID`.
- Para trocar de conta na mesma fila: pause, abra o projeto da outra conta, conecte e retome.
  Prompts ainda não enviados seguem no novo projeto. Tarefas já enviadas ficam guardadas
  no projeto original e podem ser retomadas ao reconectá-lo.

Mantida a validação de até 6.000 caracteres por prompt individual. Memória, espaço em disco
e as cotas da conta Google continuam sendo limites reais.

## Atualização

Pause o lote. Baixe o ZIP novo, substitua os arquivos na mesma pasta e clique em
**Recarregar** na página de extensões. Atualize a aba Flow e reabra o painel.
A fila e os arquivos já salvos são preservados; não é necessário descartar o lote.
A instalação manual por ZIP não atualiza automaticamente.

Este repositório distribui apenas os pacotes da extensão. As releases do aplicativo
desktop Microstock Sensei continuam no repositório próprio.
