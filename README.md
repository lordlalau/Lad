<p align="center">
  <img src="icone.png" width="120" alt="Ícone do Lad." />
</p>

<h1 align="center">Lad.</h1>

<p align="center">
  Uma ilha no topo da tela do Windows que ouve, responde e mexe no computador por você.<br />
  Esta versão foi pensada para ser <b>um Jarvis para o seu computador</b>.
</p>

<p align="center">
  <img src="gifs/abertura.gif" alt="Abertura do Lad." />
</p>

## O que é

O Lad. fica no topo da tela, pequeno e discreto. Você segura uma tecla, fala, e ele faz: abre programas e
sites, fecha janelas, pesquisa, tira print, grava a tela, mostra FPS e temperatura, responde perguntas e
conversa por voz. O que dá para fazer sem inteligência artificial ele faz na hora, direto no Windows; o resto
ele passa para a IA.

[**⬇ Baixar o Lad.**](https://github.com/lordlalau/lad/releases/latest)

> Os GIFs desta página foram gravados da interface do Lad. com dados de exemplo.

## A ilha

<p align="center">
  <img src="gifs/ilha.gif" alt="A ilha aberta, passando pelas abas" />
</p>

Passe o mouse no topo da tela e a ilha abre. As abas:

| Aba | O que tem |
|---|---|
| **Início** | Saudação, hora e data. |
| **Música** | O que está tocando, com atalhos para Spotify e YouTube Music. |
| **Chat** | Conversa por texto com ChatGPT ou Claude. |
| **FPS** | FPS, 1% low, tempo de quadro, uso e temperatura de GPU e CPU, VRAM e RAM. |
| **Alarmes** | Cronômetro, alarmes, lembretes e um calendário com datas fixas. |
| **Gastos** | Quanto a sua conta da OpenAI gastou, com gráfico por dia. |
| **Configurações** | Tudo o que dá para ajustar. |

## Voz

<p align="center">
  <img src="gifs/voz.gif" alt="O núcleo ouvindo, pensando e respondendo; dados e avisos na ilha fechada" />
</p>

Segure a tecla de falar (padrão: **End**), fale e solte. O núcleo mostra se o Lad. está ouvindo, pensando ou
respondendo. Alguns exemplos do que ele entende:

**Computador**
- "abre o YouTube no canal do Alanzoka", "pesquisa preço da RTX 5080", "abre o Spotify"
- "fecha o Discord", "força fechar o Chrome", "fecha tudo", "minimiza essa janela"
- "aumenta o volume", "pausa a música", "abre o gerenciador de tarefas", "abre a pasta Downloads"
- "esvazia a lixeira", "limpa os arquivos temporários", "quanto espaço tenho no disco", "modo escuro"
- "bloqueia a tela", "tira um print", "que horas são?"

**O próprio Lad.**
- "coloca FPS, GPU e VRAM na ilha", "tira os dados da ilha"
- "me lembra de beber água às 15h", "cronômetro de 10 minutos", "marca no calendário dia 20: reunião"
- "lembra que meu monitor principal é o da esquerda" (memória de longo prazo)

**Capturas**
- "tira um print", "print do monitor 2"
- "grava a tela", "para de gravar", "liga o replay", "salva os últimos 30 segundos"

**Star Citizen** (dados reais da [UEX](https://uexcorp.space) e da [Star Citizen Wiki](https://star-citizen.wiki))
- "qual a melhor rota de comércio saindo de Area18?", "onde vende Polaris Bit?"
- "consigo quebrar uma pedra de 12 mil de massa com 30% de resistência?"

Ações que precisam de administrador não são feitas escondido: o Windows mostra a pergunta de permissão e
você decide.

## Chat

<p align="center">
  <img src="gifs/chat.gif" alt="Aba de chat" />
</p>

Conversa por texto com ChatGPT (chave da OpenAI) ou Claude (chave da Anthropic), dentro da ilha.

## Configurações

<p align="center">
  <img src="gifs/configuracoes.gif" alt="Configurações" />
</p>

- **Geral:** tecla de falar, voz, microfone, volume, sons.
- **Visual** e **Ilha e tempo:** aparência, cidade do clima, comportamento da ilha.
- **Chat:** chaves de API e modelo.
- **Resumo do dia:** o que o Lad. fala quando abre (saudação, alarmes, calendário, clima, gastos, notícias).
- **Capturas:** pasta dos prints e vídeos, atalhos de até 3 teclas (ex.: Alt + Q), replay, 60 ou 30 fps,
  gravar ou não o microfone.

## Prints e gravação

- Os arquivos vão para **Imagens › Lad imagens** (dá para trocar a pasta).
- O print é feito pelo próprio Lad., do monitor inteiro onde está a janela da frente.
- A gravação e o replay usam o gravador que já vem no Windows, sem abrir a tela dele. Por isso gravam a
  janela de um jogo ou programa, não a Área de Trabalho.

## Como instalar

1. Abra a página de [**Releases**](https://github.com/lordlalau/lad/releases/latest).
2. Em **Assets**, baixe o arquivo **`Lad_x.x.x_x64-setup.exe`** e abra.
3. Se aparecer **"O Windows protegeu o computador"**, clique em **Mais informações** e depois em
   **Executar assim mesmo**. O aviso aparece porque o app é novo.
4. Abra a ilha, vá em **Configurações › Chat** e cole a sua chave da OpenAI (a voz e a IA usam essa chave).
5. Em **Configurações › Geral**, escolha a tecla de falar, a voz e o microfone.
6. Opcional: para ver FPS e temperaturas, aceite instalar o Intel PresentMon (no instalador ou pela aba **FPS**).
7. Opcional: para a aba **Gastos**, cole uma chave de administrador (Admin key) da OpenAI.

As chaves ficam guardadas no Gerenciador de Credenciais do Windows, não em arquivos do Lad.
O Lad. se atualiza sozinho quando sai uma versão nova.

Requer **Windows 10 ou 11 (64 bits)**.

## Privacidade

- Por padrão, o microfone só é usado enquanto você segura a tecla de falar; o que você fala vai para a OpenAI, que faz a voz e a IA.
- O registro de diagnóstico da voz guarda apenas etapas e contagem de palavras, nunca a chave nem o que foi dito.
- A memória de longo prazo fica só no seu PC.

## Licença

© 2026 Lad. Todos os direitos reservados.

Spotify, YouTube, ChatGPT, OpenAI, Claude, Star Citizen e Xbox são marcas dos seus donos. O Lad. não tem
ligação com essas empresas.
