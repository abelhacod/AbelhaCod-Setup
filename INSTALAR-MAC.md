# 🍎 Como instalar o AbelhaCod no MacBook (macOS)

> O AbelhaCod roda no **macOS** (MacBook, iMac, Mac mini). Ele **não** roda em iPhone ou iPad (iOS/iPadOS):
> nesses aparelhos a Apple não permite editores com terminal e compilação.

**Precisa de:** macOS 12 (Monterey) ou mais novo · cerca de 1 GB livre · internet para as IAs.

---

## 1. Descubra o chip do seu Mac

Clique no menu **** (canto superior esquerdo) › **Sobre este Mac**:

| Aparece | Seu Mac é | Baixe |
|---|---|---|
| **Chip Apple M1, M2, M3 ou M4** | Apple Silicon | `AbelhaCod-macOS-arm64-<versão>.dmg` |
| **Processador Intel** | Intel | `AbelhaCod-macOS-x64-<versão>.dmg` |

> Baixou o errado? No Apple Silicon a versão Intel até abre (pelo Rosetta), mas fica mais lenta. Prefira a certa.

## 2. Baixe

Abra **[Releases › última versão](../../releases/latest)**, role até **Assets** e clique no `.dmg` do seu chip.
O arquivo vai para a pasta **Downloads**.

## 3. Instale

1. Dê dois cliques no `.dmg` baixado. Abre uma janela com o ícone da colmeia e a pasta **Aplicativos**.
2. **Arraste o AbelhaCod para a pasta Aplicativos.**
3. Feche a janela e ejete o disco "AbelhaCod" (botão ⏏ ao lado dele no Finder).

## 4. Abra pela primeira vez (só uma vez)

O AbelhaCod ainda não tem o selo de notarização da Apple, então o macOS pede uma confirmação na primeira vez.

**macOS 15 (Sequoia) ou mais novo**
1. Abra **Aplicativos › AbelhaCod**. Aparece *"AbelhaCod não pode ser aberto…"*: clique em **OK** (não em "Mover para o Lixo").
2. Abra **Ajustes do Sistema › Privacidade e Segurança**.
3. Role até **Segurança**: aparece *"AbelhaCod foi bloqueado…"*. Clique em **Abrir Mesmo Assim**.
4. Confirme com a senha do Mac ou o Touch ID e clique em **Abrir**.

**macOS 14 (Sonoma) ou mais antigo**
1. Em **Aplicativos**, clique com o **botão direito** (ou Control + clique) no AbelhaCod › **Abrir**.
2. Na mensagem, clique em **Abrir** de novo.

**Apareceu "está danificado e não pode ser aberto"?**
Isso é a quarentena do download, não um defeito. Abra o **Terminal** (⌘ + Espaço, digite *Terminal*, Enter), cole e aperte Enter:

```
xattr -dr com.apple.quarantine /Applications/AbelhaCod.app
```

Depois abra o AbelhaCod normalmente. Das próximas vezes ele abre direto.

## 5. Deixe à mão

- **No Dock:** com o AbelhaCod aberto, botão direito no ícone do Dock › **Opções › Manter no Dock**.
- **Comando no Terminal:** no AbelhaCod, ⌘ + Shift + P › *Shell Command: Install 'abelhacod' command in PATH*. Depois `abelhacod .` abre a pasta atual.
- No Mac, os atalhos usam **⌘ (Command)** no lugar de Ctrl: ⌘ + ⌥ + A abre o Copiloto, ⌘ + ⌥ + R testa no navegador…

## 6. Primeiros passos

1. **Arquivo › Abrir Pasta** e escolha o seu projeto.
2. Clique na **colmeia** na barra lateral (o Copiloto).
3. No botão **IA**, escolha Claude, Gemini, Grok, Meta AI ou o **Chat Grátis** (não precisa pagar nada).
4. Peça o que quiser. O tutorial completo abre sozinho na primeira vez.

**Android no Mac:** "Testar no Android" baixa o que precisar. Nos Macs M1–M4 o emulador usa a imagem ARM, que é rápida e nativa.

## 7. Atualizar

O AbelhaCod avisa quando sai versão nova. Clique em **Baixar e instalar**: o `.dmg` novo abre. Feche o AbelhaCod, arraste o novo para **Aplicativos**, escolha **Substituir** e libere de novo como no passo 4.

## 8. Desinstalar

Arraste **Aplicativos › AbelhaCod** para o **Lixo**. Para apagar também as configurações, no Finder use **Ir › Ir para a Pasta…** e apague:
`~/Library/Application Support/AbelhaCod` e `~/.abelhacod`.

---

### 💬 Suporte
Não conseguiu instalar? **(85) 98414-6479 — Suporte AbelhaCod.**
