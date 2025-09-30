# macOS InstallAssistant Browser

Aplicativo para macOS que facilita encontrar e baixar rapidamente as versões do InstallAssistant diretamente dos catálogos oficiais da Apple.

## 🛒 Como comprar

1. Acesse o site oficial Hackintosh and Beyond e escolha o plano do **macOS InstallAssistant Browser**.
2. Informe seu e-mail (será usado para vincular a licença) e complete os dados solicitados.
3. Conclua o pagamento pelo método desejado:
   - **PIX** (liberação mais rápida);
   - **Cartão de crédito (Stripe)**;
   - **PayPal**.
4. Após o pagamento você será redirecionado para a página de confirmação. Em até poucos minutos o painel sinaliza a aprovação.

> **Importante:** mantenha o mesmo e-mail durante todo o processo; o serial é gerado de forma determinística a partir dele.

## 📬 Como funciona a entrega

- Assim que o pagamento é confirmado, o sistema envia automaticamente um e-mail com:
  - seu número de série exclusivo;
  - link para este repositório público (downloads e instruções);
  - comprovante da transação.
- Se não visualizar o e-mail em até 10 minutos, verifique a caixa de spam/lixo.
- Ainda com dúvidas? Entre em contato pelo suporte e informe o e-mail da compra; é possível reenviar o serial a qualquer momento.

## 🚀 Download do app

1. Abra a aba **Releases** deste repositório público.
2. Baixe o arquivo `macOS-InstallAssistant-Browser.dmg` mais recente.
3. Monte o DMG e arraste o app para `/Applications`.

## 🔓 Primeira execução (Gatekeeper)

Caso o macOS bloqueie a abertura na primeira tentativa, execute os comandos abaixo no Terminal e tente novamente:

```bash
sudo xattr -dr com.apple.quarantine "/Applications/macOS-InstallAssistant-Browser.app"
chmod -R a+x "/Applications/macOS-InstallAssistant-Browser.app"
```

Se o bloqueio persistir, vá em **Configurações do Sistema ▸ Privacidade e Segurança** e clique em **Abrir assim mesmo**.

## 🔑 Ativar a licença

1. Abra o app instalado.
2. Informe o **mesmo e-mail utilizado na compra**.
3. Digite o serial recebido por e-mail (copiar/colar funciona normalmente).
4. Clique em **Ativar Licença**. O app valida o par e-mail/serial localmente e libera todas as funcionalidades.

### Reenvio ou recuperação do serial
- Procure o e-mail com o assunto *“Sua licença do macOS InstallAssistant Browser”*.
- Caso não encontre, solicite o reenvio pelos canais de suporte informando o e-mail cadastrado.

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

