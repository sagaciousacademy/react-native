## Acesse o meu Curriculum

http://bit.ly/curriculum-marcelo

## Acesse o meu Portfólio

http://bit.ly/portfolio-marcelo

## React Brasil

https://medium.com/reactbrasil

https://github.com/react-brasil

## ReactJS

https://reactjs.org/

## React Native

https://facebook.github.io/react-native/

## React Native - Documentação

https://facebook.github.io/react-native/docs/getting-started.html

## Cases

https://facebook.github.io/react-native/showcase.html

## NATIVE BASE - Framework com diversos componentes prontos

https://nativebase.io/

## JSX

https://facebook.github.io/jsx/

## EXPO

https://expo.io/

## NODE.JS

https://nodejs.org/en/

## FLEXBOX

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## REACT NAVIGATION

https://reactnavigation.org/

## JEST

https://jestjs.io/

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

    ou

    [Desktop Entry]
    Version=1.0
    Type=Application
    Terminal=false
    Icon[pt_BR]=gnome-panel-launcher
    Name[pt_BR]=Android-Studio
    Exec=/opt/andoid-studio/bin/studio.sh
    Comment[pt_BR]=Android-Studio
    Name=Android-Studio
    Comment=Android-Studio
    Icon=/opt/andoid-studio/bin/studio.png

Apareceu esse erro na primeira abertura do Android Studio

Gtk-Message: 01:02:35.549: Failed to load module "canberra-gtk-module"

Configuring VM acceleration on Linux

https://developer.android.com/studio/run/emulator-acceleration?utm_source=android-studio#vm-linux

Adicionar o path das variaveis de ambiente do Linux

    export ANDROID_HOME=$HOME/Android/Sdk
    export PATH=$PATH:$ANDROID_HOME/tools
    export PATH=$PATH:$ANDROID_HOME/platform-tools

## Módulo 4 - Configurando Ambiente no Linux - Aula 4 - Aula Provisória: Aviso de versão

    react-native init NomedoProjeto --vesion=0.55.4

## Módulo 4 - Configurando Ambiente no Linux - Aula 5 - Criando o Primeiro Projeto

    react-native init PrimeiroProjeto

## Módulo 4 - Configurando Ambiente no Linux - Aula 6 - Configurando o Simulador

grant current access /dev/kvm

https://quynguyen.wordpress.com/2018/05/17/fix-your-ubuntu-android-studio-kvm-permission-denied/

http://nmp90.com/2018/04/dev-kvm-permission-denied-ubuntu-18-04/

Rodando o projeto no Emulador

    react-native run-android

Para usar o Expo

    sudo npm install -g create-react-native-app

Criando o segundo projeto para ser simulado no Expo

    create-react-native-app SegundoProjeto

Incializado o Expo no terminal SSH para leitura do código via celular

    expo start

Inicializando o NPM para leitura do código de barras no Expo

    sudo npm start

Criando o terceiro projeto

    react-native init TerceiroProjeto --vesion=0.55.4

Comando para correção do erro 500

    npm install --save-dev @babel/runtime

Lista de dispositivos conectados no computador

    adb devices

    sudo apt install adb

Para rodar o aplicativo no celular

    react-native run-android

## Módulo 8 - React Native Básico (JSX e ES6)

Estrutura Básica de um App (App.js)

        import React, { Component } from 'react';
        import { View,Text } from 'react-native';

        export default class PrimeiroProjeto extends Component {
        render() {
            return (
                <View>
                <Text>Olá Mundo</Text>
                <Text>Olá Mundo</Text>
                <Text>Olá Mundo</Text>
                </View>
            );

            }
        }

## Módulo 8 - Detalhes sobre ES6

Declarando a variável, com estilização e funções anônimas

        import React, { Component } from 'react';
        import { View,Text, StyleSheet, Button } from 'react-native';

        export default class PrimeiroProjeto extends Component {

            somar(n1, n2) {
                return n1 + n2;
            }

            render() {

                let nome = "Marcelo";

                return (
                    <View>
                    <Text style={styles.texto}>Olá {nome} - A soma de 2+2 é {this.somar(2, 2)}</Text>

                    <Button title="Aperte" onPress={()=>{
                        alert("me apertou")
                    }} />
                    </View>
                );

            }
        }

        const styles = StyleSheet.create({
            texto: {
                fontSize: 30
            }
        });
