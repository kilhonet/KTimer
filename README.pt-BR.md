# KTimer

**Temporizador de desligamento gratuito para Windows: quando o tempo definido acaba, ele desliga o PC ou o coloca em suspensão.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, a [versão em coreano](README.ko.md) prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/ktimer?lang=pt)

![Tela do KTimer](images/ktimer-en.webp)

> A interface do programa não tem tradução para português; ela é exibida em inglês. Os nomes de botões abaixo aparecem como na tela.

## Visão geral

Dormir vendo um filme, ou deixar um download ou backup longo rodando enquanto se ausenta — às vezes você só quer que o PC se desligue sozinho quando terminar.

Com o KTimer, ajuste o tempo com alguns toques nos botões e clique em **Run**. Um relógio de cartões conta até zero e então o PC desliga. Em vez de desligar, ele também pode colocar o PC em **hibernação ou suspensão**.

Logo antes de desligar, o KTimer **captura a tela e a mostra na próxima vez que você ligar o PC.** De manhã você vê de relance se o download terminou e quais janelas estavam abertas.

## Principais recursos

- **Desligamento agendado** — De 1 minuto até 7 horas; o PC desliga quando o tempo acaba.
- **Hibernação · Suspensão** — Coloque o PC para dormir em vez de desligá-lo. O KTimer escolhe o que este PC suporta.
- **Ver a última tela** — A tela logo antes do desligamento é salva e mostrada no navegador na próxima inicialização.
- **Relógio de cartões** — O tempo restante aparece em grandes cartões de horas : minutos : segundos, legíveis de relance.
- **Tempo só com botões** — `−5` `−1` `+1` `+5` somam e subtraem; `5` `10` `30` definem o valor diretamente.
- **Nada para configurar** — Sem janela de configurações nem permissão de administrador; um único executável.
- **9 idiomas** — Coreano · inglês · japonês · chinês · russo · italiano · francês · espanhol · árabe. Segue o idioma de exibição do Windows.

## Download / Instalação

| Tipo | Link |
|---|---|
| Instalador | [Download](https://down.kilho.net/ktimer?lang=pt) |
| Portátil (ZIP) | [Download](https://down.kilho.net/ktimer?lang=pt&nosetup) |

Com o instalador, o KTimer abre assim que a instalação termina e é adicionado ao menu Iniciar. Na versão portátil, descompacte o ZIP e execute `KTimer.exe`.

## Como usar

### Primeiros passos

1. Abra o KTimer. A janela aparece no centro da tela com o relógio pronto em **00 : 05 : 00** (5 minutos).
2. Ajuste o tempo com os botões. Por exemplo: `30` → 30 minutos; `30` e depois `+5` seis vezes → 1 hora.
3. Veja o ícone de energia para saber o que vai acontecer. O **símbolo de energia** significa desligar; clique uma vez para trocar para a **lua** e suspender.
4. Clique em **Run**. O relógio diminui segundo a segundo, e os pontos entre os dígitos piscam para mostrar que está contando.
5. Ao chegar a zero, o botão muda para **Shutting down…** (ou **Hibernating…** / **Sleeping…**) e o PC desliga ou dorme. O KTimer fecha junto.

### Organização da tela

| Elemento | O que faz |
|---|---|
| Relógio de cartões | Tempo restante (horas : minutos : segundos). Os pontos piscam durante a contagem |
| `−5` `−1` `+1` `+5` | Subtraem ou somam esses minutos |
| `5` `10` `30` | Definem o tempo diretamente nesses minutos |
| Ícone de energia | Cada clique alterna **Shut down** (símbolo de energia) ↔ **Sleep** (lua). Passe o mouse para ver o nome |
| **Run** / **Stop** | Iniciar / parar a contagem regressiva |

- Durante a contagem, os botões de tempo e o ícone de energia somem e só resta **Stop**, então o tempo não muda por acidente.
- O intervalo é de **1 minuto a 7 horas**. Ao tentar ir além, ele para no limite.

### O que fazer quando…

**Dormir com um filme ou música tocando**
Um filme costuma ter cerca de 2 horas. Pressione `30`, acrescente folga com `+5`, clique em **Run** e vá dormir. O PC desliga perto do fim.

**Deixar um download, backup ou conversão de vídeo rodando**
Agende o tempo que a tarefa deve levar, com um pouco de folga (até 7 horas). Na próxima vez que ligar o PC, a última tela antes do desligamento abre, para você conferir na hora se a tarefa terminou mesmo.

**Ver o que estava na tela logo antes do desligamento**
Quando o KTimer desliga o PC, ele salva a tela do **monitor onde estava o mouse**. Na próxima vez que você ligar o PC e entrar, o navegador padrão abre e mostra essa tela. Não é preciso fazer nada.
- Com vários monitores, deixe o mouse no monitor com a janela que você quer conferir.
- Isso só acontece com **Shut down**. Na suspensão, a tela continua lá quando você acorda o PC, então não é necessário.

**Há documentos não salvos**
Quando chega a hora, outros programas não conseguem segurar o desligamento — o PC desliga com certeza. Ele nunca fica a noite toda parado num aviso de "Salvar alterações?", mas **o que não foi salvo não é mantido**, então salve antes de clicar em Run.

**Colocar o PC para dormir em vez de desligar**
Antes de clicar em Run, clique no ícone de energia para trocá-lo para a **lua**. Passe o mouse sobre o ícone para ver o que este PC vai realmente fazer.
- **Hibernation** — Salva as janelas abertas e o trabalho e depois desliga. Ao ligar de novo, tudo volta como estava.
- **Sleep** — Aguarda consumindo pouquíssima energia. Acorda rapidamente.
PCs que suportam hibernação hibernam; os demais entram em suspensão. O KTimer confere de novo logo antes de agir, então, se você mudar as configurações de energia durante a espera, ele as segue.

**Cancelar ou mudar o agendamento**
Clique em **Stop** para pausar a contagem e trazer de volta os botões de tempo. Ajuste o tempo e clique em **Run** para contar de novo a partir desse tempo. Para cancelar de vez, basta fechar a janela — ao fechá-la, o agendamento é cancelado.

**A janela atrapalha**
**Minimize-a** — ela continua contando em segundo plano. Abra de novo pela barra de tarefas quando quiser ver o tempo restante.

**Não encontro a janela**
Execute o KTimer outra vez. Em vez de abrir uma nova, a janela que já está contando vem para a frente (só há um agendamento por vez).

**Dicas para ajustar o tempo rápido**
- Para os comuns 5 · 10 · 30 minutos, pressione o botão uma vez.
- 1 hora é `30` e depois `+5` seis vezes; 45 minutos é `30` e depois `+5` três vezes.
- Ajuste minuto a minuto com `+1` · `−1`. Por mais que pressione `−1`, nunca fica abaixo de 1 minuto.

## Configuração

Não há janela de configurações e nada é salvo. Cada inicialização começa assim:

| Item | Valor inicial |
|---|---|
| Tempo | 5 minutos |
| Ação | Desligar |
| Aparência | Tema escuro |
| Idioma | Idioma de exibição do Windows (inglês se não for suportado) |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- Não requer permissão de administrador nem runtime adicional para executar o programa.
- A visualização da última tela abre no navegador padrão. A conexão com a Internet é usada apenas para essa visualização e para avisos de nova versão.

## Atualizações

O KTimer **não** se atualiza sozinho. Ao iniciar, verifica se há uma versão nova e mostra um aviso; ao pressionar **Sim**, a página de download é aberta e o programa é encerrado. As novas versões são publicadas manualmente após verificação interna e anunciadas na [página do KTimer](https://kilho.net/ktimer). Veja o [aviso sobre a política de atualização](https://en.kilho.net/archives/notice/2940).

## Licença

O KTimer é **freeware**. Use gratuitamente e sem restrições em qualquer lugar — empresa, casa, órgãos públicos, escola — e redistribua livremente.

## Links

- Site: <https://kilho.net/ktimer>
- Fórum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
