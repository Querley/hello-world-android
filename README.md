# Hello World Android

Atividade 02 da disciplina Desenvolvimento de Sistemas para Dispositivos Móveis.

Projeto básico com uma única Activity, seguindo a estrutura do modelo Empty Activity. O aplicativo usa Kotlin e Jetpack Compose e mostra a mensagem **Hello World!** no centro da tela.

[Baixar o APK](https://github.com/Querley/hello-world-android/releases/latest/download/app-debug.apk)

## Como executar

1. Clone ou baixe o repositório.
2. Abra a pasta no Android Studio e aguarde a sincronização do Gradle.
3. Se necessário, instale o Android SDK 35 solicitado pela IDE.
4. Selecione um emulador ou celular com Android 8.0 ou superior.
5. Clique em **Run** para abrir o aplicativo.

Use JDK 17 ou 21 nas configurações do Gradle. O arquivo `.gitignore` exclui os arquivos temporários, as configurações locais e as pastas de compilação.

## Compilação e teste

No terminal do Android Studio, no Windows:

```powershell
.\gradlew.bat assembleDebug testDebugUnitTest
```

No Linux ou macOS, use `./gradlew`. O APK gerado fica em `app/build/outputs/apk/debug/app-debug.apk`.

O teste abre a Activity com Robolectric (ambiente Android simulado) e verifica se a mensagem aparece na tela. Essa verificação não substitui executar o APK no celular ou emulador.
