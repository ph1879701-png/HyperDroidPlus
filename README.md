# HyperDroid Plus 0.6

Projeto Android do HyperDroid Plus, um launcher/desktop inspirado no Windows 11, desenvolvido em Java + WebView.

## Estrutura
O código-fonte e os recursos estão no arquivo `HyperDroidPlus-v0.6-GitHub.zip`, na raiz deste repositório. O workflow do GitHub Actions extrai o projeto, compila o APK de debug e publica o resultado como artefato.

## Gerar o APK
1. Abra a aba **Actions**.
2. Selecione **Gerar APK HyperDroid Plus**.
3. Abra a execução mais recente.
4. Quando terminar com sucesso, baixe o artefato **HyperDroidPlus-APK**.
5. Extraia o ZIP do artefato e instale `app-debug.apk` no Android.

Requisitos usados pelo workflow: JDK 17, Android SDK Platform 35, Build Tools 35.0.0 e Gradle 8.9.

## Observação
O APK de debug serve para testes. A compilação precisa terminar com sucesso e o aplicativo ainda deve ser testado no aparelho antes de ser considerado pronto.
