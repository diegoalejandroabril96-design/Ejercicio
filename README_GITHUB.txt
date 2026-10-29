30 FUERTE - COMPILAR APK CON GITHUB ACTIONS

1. En GitHub crea un repositorio NUEVO, por ejemplo: 30-FUERTE-APP.
2. Descomprime este ZIP en tu computador.
3. En el repositorio: Add file > Upload files.
4. Arrastra TODO EL CONTENIDO de la carpeta descomprimida (no la carpeta exterior).
   Debes ver en la raiz: .github, app, build.gradle, settings.gradle, gradle.properties.
5. Commit changes.
6. Abre la pestaña Actions.
7. Entra a "Build 30 FUERTE APK".
8. Si no empezo automaticamente: Run workflow > Run workflow.
9. Cuando termine en verde, abre la ejecucion.
10. Abajo, en Artifacts, descarga "30-FUERTE-APK".
11. Descomprime ese artifact. Adentro esta app-debug.apk.
12. Pasa app-debug.apk al celular e instalalo.

IMPORTANTE:
- No subas el ZIP como un unico archivo. Debes subir su CONTENIDO descomprimido.
- El APK debug generado por Android/Gradle es un APK real y firmado para pruebas.
- Package: com.fuerte30.app
- minSdk: 23
- target/compile SDK: 35
