# Como gerar o APK

Este pacote é um projeto Android Studio (Kotlin/Compose). O ambiente desta sessão não possui Android SDK/Gradle instalados, então o APK binário não pôde ser compilado aqui.

No Android Studio:
1. Abra a pasta `OlixPlayAndroid`.
2. Aguarde o Gradle sincronizar.
3. `Build > Build APK(s)`.
4. O APK de debug ficará em `app/build/outputs/apk/debug/app-debug.apk`.

No projeto já estão incluídos:
- login via API;
- Live/VOD/Séries;
- categorias;
- player Media3;
- logo/identidade Olix Play;
- API sem acesso direto ao MySQL.

Antes de distribuir, configure HTTPS no servidor e teste somente com conteúdo/serviços para os quais você tenha autorização.
