# sdk-android-4-linux-wiki-catala
Una altra wiki no oficial de l'SDK d'Android en entorn Linux, en Català.


## Instal·lació SDK mínim sense Android Studio a Linux Debian Bookworm
- S'instal·larà la versió mínima per a utilitzar l'SDK des de línia de comandas.
- Per a utilitzar l'SDK amb GUI des de l'entorn gràfic de Linux, caldria instal·lar l'SDK amb Android Studio, situació que no es contempla en aquest apartat.
- Descarregar l'SDK
  ```{.scrollable}
  wget https://dl.google.com/android/repository/commandlinetools-linux-7302050_latest.zip
  ```
- Descomprimir-lo.
- Configurar el PATH

  ```{.scrollable}
  echo 'export PATH="$HOME/android-sdk/cmdline-tools/bin:$PATH"' >> ~/.bashrc
  source ~/.bashrc
  ```

- Descàrrega de diferents versions d'api
  ```{.scrollable}
  sdkmanager "platforms;android-31" "build-tools;31.0.0"
  sdkmanager "platforms;android-30" "build-tools;30.0.3"
  sdkmanager "platforms;android-29" "build-tools;29.0.3"
  sdkmanager "platforms;android-28" "build-tools;28.0.3"
  sdkmanager "platforms;android-27" "build-tools;27.0.3"
  sdkmanager "platforms;android-26" "build-tools;26.0.3"
  sdkmanager "platforms;android-25" "build-tools;25.0.3"
  sdkmanager "platforms;android-24" "build-tools;24.0.3"
  sdkmanager "platforms;android-23" "build-tools;23.0.3"
  sdkmanager "platforms;android-22" "build-tools;22.0.1"
  sdkmanager "platforms;android-21" "build-tools;21.1.2"
  ```
  
