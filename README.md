# macOS InstallAssistant Browser

Aplicativo para macOS que facilita encontrar e baixar rapidamente as versões do InstallAssistant diretamente dos catálogos oficiais da Apple.

## 🚀 Como baixar

1. Acesse a página de *Releases* deste repositório público.
2. Baixe o arquivo `macOS-InstallAssistant-Browser.dmg` mais recente.
3. Abra o DMG e arraste o app para a pasta `/Applications`.

## 🔓 Primeira execução (Gatekeeper)

Se o macOS bloquear a abertura do app na primeira vez:

```bash
sudo xattr -dr com.apple.quarantine "/Applications/macOS-InstallAssistant-Browser.app"
chmod -R a+x "/Applications/macOS-InstallAssistant-Browser.app"
```

Depois, abra novamente ou vá em **Configurações do Sistema ▸ Privacidade e Segurança** e clique em **Abrir assim mesmo**.

## 🔑 Ativação da licença

1. Efetue a compra no site oficial Hackintosh and Beyond.
2. Você receberá por e-mail o número de série vinculado ao seu endereço.
3. Abra o app e, na tela de ativação, informe o mesmo e-mail da compra e o serial recebido.
4. Clique em **Ativar Licença**.

Se precisar gerar novamente o serial, basta solicitar pelo painel ou entrar em contato com o suporte.

## 📦 O que o app faz

- Lista builds oficiais do macOS disponíveis nos catálogos Apple.
- Permite filtrar por canal (Release, Beta, Developer) e tipo (PKG/DMG).
- Exibe versão, build, data, tamanho e URL de download.
- Copia o link direto ou inicia o download com um clique.

## 💬 Suporte

- E-mail: hackintoshandbeyond@gmail.com
- Comunidade: Discord / Telegram do Hackintosh and Beyond
- FAQs e tutoriais: https://hackintoshandbeyond.com

## 🔐 Termos

Utilize os downloads apenas em conformidade com os termos de licença da Apple. O aplicativo não hospeda nenhum arquivo proprietário — ele apenas referencia os servidores oficiais.

---

> **Importante:** O arquivo DMG não é versionado neste repositório. Publique-o manualmente na aba *Releases* para mantê-lo acessível ao público sem expor o código-fonte privado.

