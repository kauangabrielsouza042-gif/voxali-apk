# Voxali Android

Projeto Android do Voxali preparado para GitHub Actions.

## Como usar

1. Crie um repositório no GitHub.
2. Envie **todo o conteúdo desta pasta** para o repositório.
3. Vá em **Actions**.
4. Abra **Build Voxali APK**.
5. Clique em **Run workflow** (ou faça um push na branch `main`).
6. Quando terminar, abra a execução e baixe o artefato **Voxali-APK**.

O APK é um aplicativo próprio: os arquivos do Voxali ficam dentro do APK. Ele **não redireciona para voxali.com.br**. O aplicativo usa os mesmos serviços Firebase/backend já presentes no projeto, então contas, mensagens, amigos, servidores e dados continuam sincronizados com o site.

### Observação
O APK de debug gerado pelo GitHub é instalável diretamente no Android. Para publicar na Google Play, depois será necessário configurar uma chave de assinatura própria.
