<p align="center">
  <img src="assets/icon.png" width="104" alt="Mach3 Studio">
</p>

<h1 align="center">Mach3 Studio</h1>

<p align="center">
  <b>Editor visual e gratuito de telas para o Mach3</b> — moderno, com tema claro/escuro, scripts, macros,<br>
  instalação com backup e controle por IA.
</p>

<p align="center">
  <a href="../../releases/latest"><img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Baixar-Windows%2010%20%2F%2011-ea580c?style=for-the-badge" alt="Baixar para Windows"></a>
  <a href="#-apoie-o-projeto"><img src="https://img.shields.io/badge/%F0%9F%A7%A1%20Apoiar-LivePix-f59e0b?style=for-the-badge" alt="Apoiar o projeto"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/vers%C3%A3o-0.1.1-ea580c" alt="versão 0.1.1">
  <img src="https://img.shields.io/badge/licen%C3%A7a-freeware-16a34a" alt="licença freeware">
  <img src="https://img.shields.io/badge/Mach3-3.x-555" alt="Mach3 3.x">
  <img src="https://img.shields.io/badge/idioma-portugu%C3%AAs-555" alt="português">
</p>

<p align="center">
  <img src="assets/editor.png" alt="Editor do Mach3 Studio" width="920">
</p>

---

## ⬇️ Download

Baixe a versão mais recente na página de **[Releases](../../releases/latest)**:

| Arquivo | Para quem |
|---|---|
| **`Mach3-Studio-Setup-<versão>.exe`** | **Recomendado.** Instalador comum, com atalhos na área de trabalho e no menu Iniciar. |
| `Mach3-Studio-Portatil-<versão>.exe` | Roda sem instalar (pendrive). Não recomendado para uso com IA. |

**Requisitos:** Windows 10 ou 11 (64 bits). Não precisa de administrador nem de internet.
As telas criadas funcionam em **qualquer Mach3 3.x** — inclusive em PCs antigos com Windows XP/7 na máquina.

> [!NOTE]
> **"O Windows protegeu o computador"?** O instalador ainda não tem assinatura digital, então o Windows avisa na
> primeira vez. Clique em **Mais informações → Executar assim mesmo**. Baixe sempre por esta página.

---

## ✨ O que ele faz

- **Abre as telas que você já usa** (`.set` / `.lset`), inclusive telas personalizadas de plasma e oxicorte, sem perder
  nenhuma função — importar nunca altera o arquivo original.
- **Editor visual de verdade:** arrastar, redimensionar, alinhar, distribuir, grade com encaixe, zoom, camadas, travas,
  copiar/colar e até 300 passos de desfazer/refazer.
- **Todos os controles do Mach3:** botões, botões de imagem, DROs, LEDs, rótulos, imagens, linha MDI, janela de
  G-code, toolpath, jogball e barra de rolagem.
- **Funções sem decorar códigos:** catálogo das funções e códigos OEM do Mach3 com busca.
- **Scripts VB** com destaque de sintaxe, autocompletar e ajuda das funções do Mach3, e gerenciador de **macros (M-codes)**.
- **Imagens de fundo e botões com imagem**, com prévia no editor.
- **Instala direto no Mach3** com **backup automático** de tudo o que for substituído.
- **Tema claro e escuro.**
- **Funciona com IA:** Claude, Codex, Cursor e outros assistentes podem criar e editar telas pelo Studio (MCP),
  com você vendo tudo ao vivo e podendo desfazer.

---

## 🚀 Primeiros passos

1. Instale e abra o **Mach3 Studio**. Ele encontra o Mach3 em `C:\Mach3` (ou escolha a pasta em *Mach3 → Pasta do Mach3…*).
2. Clique em **Importar do Mach3** para abrir uma tela existente — ou **Novo projeto** para começar do zero.
3. Edite à vontade e salve com **Ctrl+S** (o projeto fica em uma pasta própria, com imagens e macros).
4. **Feche o Mach3** e clique em **Instalar no Mach3** (**F5**). Escolha o perfil e pronto.

O manual completo está dentro do programa: **Ajuda → Manual do usuário** (**F1**).

---

## 🤖 Usando com Inteligência Artificial

O Studio traz um servidor **MCP** (Model Context Protocol). Abra **Ajuda → Conectar assistentes de IA**, copie a
configuração pronta para o seu assistente e peça coisas como:

- *"Crie uma tela de jog com botões grandes para X, Y e Z e um DRO de cada eixo."*
- *"Deixe esta tela com visual escuro e moderno sem mudar nenhuma função."*
- *"Escreva um botão que liga a tocha, espera 2 segundos e desliga."*

Com o Studio aberto, cada alteração aparece na hora e pode ser desfeita com **Ctrl+Z**. Instalar no Mach3 sempre pede
a sua confirmação. O guia completo está em **Ajuda → Guia de uso com IA**.

---

## ⚠️ Segurança

O Mach3 controla máquinas de verdade. **Antes de produzir com uma tela nova ou alterada**, teste todos os botões com a
máquina em condição segura (sem tocha/oxigênio, sem ferramenta girando, com a emergência ao alcance).

Se algo der errado, os arquivos originais ficam guardados em `C:\Mach3\Mach3Studio-backups\<data>\`.

---

## 🧡 Apoie o projeto

<table>
  <tr>
    <td width="250" align="center">
      <a href="https://livepix.gg/inovamaker"><img src="assets/qr-apoio.png" width="220" alt="QR code para contribuir via LivePix"></a><br>
      <sub>Aponte a câmera do celular</sub>
    </td>
    <td>
      <b>O Mach3 Studio é gratuito para a comunidade</b> — use à vontade e compartilhe com os amigos.<br><br>
      Se ele te ajudou e você quiser apoiar o desenvolvimento de <b>novas ferramentas</b>, contribua com
      <b>qualquer valor</b> pelo QR code ou pelo link:<br><br>
      👉 <a href="https://livepix.gg/inovamaker"><b>livepix.gg/inovamaker</b></a><br><br>
      <sub>A contribuição é voluntária e não muda nada no programa: ele continua gratuito para todos.
      Obrigado por fazer parte!</sub>
    </td>
  </tr>
</table>

<p align="center">
  <img src="assets/apoio.png" width="640" alt="Mensagem de apoio dentro do Mach3 Studio">
</p>

---

## 💬 Dúvidas, erros e sugestões

Abra uma **[Issue](../../issues)** contando o que aconteceu (versão do Studio, do Windows e, se puder, o arquivo
`.set` ou um print). Sugestões de novas ferramentas também são muito bem-vindas.

---

## 📄 Licença

O Mach3 Studio é **freeware** — gratuito, mas **não é código aberto**. Em resumo:

| ✅ Pode | ❌ Não pode |
|---|---|
| Usar de graça, em casa ou na empresa, em quantos PCs quiser | Vender, alugar ou cobrar pelo programa |
| Compartilhar o instalador original com outras pessoas | Modificar, descompilar ou redistribuir versões alteradas |
| Usar, vender e distribuir as **telas que você criar** — elas são suas | Remover os avisos de autoria e da licença |

O programa é fornecido **sem garantia**. Leia os termos completos em **[LICENSE](LICENSE)**.

<sub>Mach3 é marca de seus respectivos titulares (ArtSoft / Newfangled Solutions). O Mach3 Studio é um projeto
independente, sem afiliação, patrocínio ou endosso dessas empresas.</sub>

---

<details>
<summary><b>English</b></summary>

**Mach3 Studio** is a free, modern visual editor for Mach3 screensets (`.set` / `.lset`): drag-and-drop layout,
buttons/DROs/LEDs, VB scripts and macros, background images, light/dark theme, one-click install into Mach3 with
automatic backup, and AI control through MCP. Windows 10/11, interface in Portuguese.
Download it from **[Releases](../../releases/latest)**. Freeware, closed source — see [LICENSE](LICENSE).
Support development at **[livepix.gg/inovamaker](https://livepix.gg/inovamaker)**.

</details>
