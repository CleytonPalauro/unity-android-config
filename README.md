# Instalação e configuração do SDK e JDK na Unity para gerar o build do Android

## Instalação da Unity:
* Faça o download da Unity versão 2017.x (2017.3.1) no [Unity download archive](https://unity3d.com/pt/get-unity/download/archive);
* Após o download, instale a Unity;
* Durante a instalação, selecionar o módulo Android para ser instalado.

## Documentação da Unity:
* [Primeiros passos no desenvolvimento do Android](https://docs.unity3d.com/2017.3/Documentation/Manual/android-GettingStarted.html);
* [Configuração do Android SDK/NDK](https://docs.unity3d.com/2017.3/Documentation/Manual/android-sdksetup.html).

## Instalação e configuração do SDK:
* Precisamos instalar o SDK (Kit de Desenvolvimento de Software) e o JDK (Kit de Desenvolvimento Java);
* Na Unity, selecione a aba *Edit>Preferences>External Tools*;

<p align="center">
  <img src="https://github.com/CleytonPalauro/unity-android-config/blob/master/Screenshots/unity-preferences.jpg" width="600"/>
</p>

* Clique no botão SDK Download;
* A unity vai redirecionar o usuário para a pagina de download do Android Studio. Clique em Download Options e selecione a IDE (Ambiente de desenvolvimento integrado) na versão Windows (64-bit) Recommended;

<p align="center">
  <img src="https://github.com/CleytonPalauro/unity-android-config/blob/master/Screenshots/android-studio-download.jpg" width="600"/>
</p>

* Após o download, instale a o Android Studio;
* Após a instalação, abra o Android Studio, clique em *Configure>SDK Manager*;

<p align="center">
  <img src="https://github.com/CleytonPalauro/unity-android-config/blob/master/Screenshots/welcome-android-studio.jpg" width="600"/>
</p>

* Verifique se está instalado a última versão do SDK Platform.

<p align="center">
  <img src="https://github.com/CleytonPalauro/unity-android-config/blob/master/Screenshots/sdk-platforms.jpg" width="600"/>
</p>

## Atualização do SDK:
* Abra a página de instalação do Android e renomeie a pasta *"tools"* para *"tools-bkp"*;
* Faça o download do [Android SDK Tools Revision 25.2.5 (January 2017)](http://dl-ssl.google.com/android/repository/tools_r25.2.5-windows.zip);
* Após extrair o conteúdo da pasta ZIP, mova a pasta *"tools"* deste arquivo (Revision 25.2.5) para o mesmo local onde você acabou de renomear a pasta *"tools-bkp"*;
* Configure o caminho do SDK na caixa *Edit>Preferences>External Tools*.

## Instalação e configuração do JDK:
* Clique no botão JDK Download;
* A unity vai redirecionar o usuário para a pagina de download do Java Platform Standard Edition;
* Clique em JDK Download na seção "Java SE 8u211 / Java SE 8u212";
* Aceite o contrato de licença da versão "Java SE 8u211" e selecione o [JDK na versão Windows x64](https://javadl.oracle.com/webapps/download/AutoDL?BundleId=238713_478a62b7d4e34b78b671c754eaaf38ab);

<p align="center">
  <img src="https://github.com/CleytonPalauro/unity-android-config/blob/master/Screenshots/java-se-dev-kit.jpg" width="600"/>
</p>

* Após o download, instale o JDK;
* Configure o caminho do JDK na caixa *Edit>Preferences>External Tools*.

# Gerando a Build para Android

## Documentação da Unity:
* [Por dentro do processo de criação do Android](https://docs.unity3d.com/Manual/android-BuildProcess.html)

[Download APK](https://drive.google.com/file/d/1RggX_95cpDXQA-EyhZKE4KEDxIgzOrYW/view)
