# React Native

## Acesse o meu Curriculum

http://bit.ly/curriculum-marcelo

## Acesse o meu Portfólio

http://bit.ly/portfolio-marcelo

## Módulo 1 - Introdução Geral - Aula 1 - O que é React Native?

Show Cases- http://facebook.github.io/react-native/showcase.html

## Módulo 1 - Introdução Geral - Aula 2 - Aplicativo Nativo x Aplicativo Híbrido

As principais viabilidades dos aplicativos nativos é o fato de existir menos camada entre o aplicativo e o sistema operacional do smartphone, proporcionando performance, rendimento, menos consumo de memória e bateria, além de possibilitar desenvolver projetos com custo de desenvolvimento menos elevado, pois por intermédio da mesma codificação é possível gerar aplicativos para plataformas distintas (Android e IOS).

Aplicativo híbrido possui mais camadas entre o aplicativo e o sistema operacional do smartphone, tornando o processo mais complexo com custo de desenvolvimento mais elevado, pois é necessário desenvolver codificação distinta para cada plataforma (Android e IOS).

## Módulo 1 - Introdução Geral - Aula 3 - App Android vs App iOS

São utilizados componentes nativos de cada sistema operacional, dessa forma, pode haver diferenças na interface gráfica esteticamente.

## Módulo 1 - Introdução Geral - Aula 4 - Como funciona desenvolvimento mobile

    :: Possuir as ferramentas necessárias;
    :: Programar;
    :: Testar o aplicativo das seguintes formas:
    -- Emulador consumindo mais memória - Android Studio
    -- No próprio celular via USB
    -- Expo - Intepreta o aplicativo direto no celular
    :: Exportar o aplicativo;
    :: Publicar o aplicativo na Apple Store (Iphone);
    :: Publicar o aplicativo na Play Store (Android), podendo ser instalado direto no celular.

## Módulo 4 - Configurando Ambiente no Linux - Aula 2 - Instalando NodeJS, JDK8 e RN Cli

https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

    curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -

    sudo apt-get install -y nodejs

Confirmando a instalação

    npm

Instalando o repositório do Java

    sudo add-apt-repository ppa:webupd8team/java

Atualizando

    sudo apt update

Instalando o JDK8

    sudo apt install oracle-java8-installer

Verificando a versão do Java

    javac -version

Setando automaticamente as variáveis de ambiente

    sudo apt install oracle-java8-set-default

Instalando o React Native Cli

    sudo npm install -g react-native-cli

## Módulo 4 - Configurando Ambiente no Linux - Aula 3 - Instalando Android Studio

Download do Android Studio

https://developer.android.com/studio/

Descompactando na pasta OPT

    sudo unzip android-studio-ide-181.5014246-linux.zip -d opt

Inserindo o ícone de carregamento do Android Studio na área de trabalho

    nano ~/.local/share/applications/androidstudio.desktop

    [Desktop Entry]
    Version=1.0
    Type=Application
    Name=Android Studio
    Exec="/opt/android-studio/bin/studio.sh" %f
    Icon=/opt/android-studio/bin/studio.png
    Categories=Development;IDE;
    Terminal=false
    StartupNotify=true
    StartupWMClass=android-studio
