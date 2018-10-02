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

## Native Base - Framework com diversos componentes prontos

https://nativebase.io/

## JSX

https://facebook.github.io/jsx/

## Expo

https://expo.io/

## Genymotion

https://www.genymotion.com/fun-zone/

https://sempreupdate.com.br/como-instalar-genymotion-no-ubuntu-fedora-debian/

https://docs.genymotion.com/latest/Content/01_Get_Started/Installation.htm

Couldn't start project on Android: could not install *smartsocket* listener: Address already in use
ADB server didn't ACK
* failed to start daemon *
error: cannot connect to daemon

https://stackoverflow.com/questions/35959350/react-native-android-genymotion-adb-server-didnt-ack

## VSCODE

https://code.visualstudio.com/docs/setup/linux

https://eslint.org/

https://medium.com/@sgroff04/configure-eslint-prettier-and-flow-in-vs-code-for-react-development-c9d95db07213

https://medium.com/@deadcoder0904/eslint-setup-in-react-native-using-vscode-c3122a1da9c7

https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint

https://github.com/prettier/prettier

https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

https://flow.org/

https://marketplace.visualstudio.com/items?itemName=flowtype.flow-for-vscode

VS Code file watcher

https://code.visualstudio.com/docs/setup/linux#_visual-studio-code-is-unable-to-watch-for-file-changes-in-this-large-workspace-error-enospc

## Node.JS

https://nodejs.org/en/

## NPM

https://www.npmjs.com/

## Flexbox

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## React Navigation

https://reactnavigation.org/

## Jest

https://jestjs.io/

## Firebase

https://firebase.google.com/

## Cursos Gratuitos do ecossistema da stack ReactJS, NodeJS e React Native

https://rocketseat.com.br/starter

https://www.youtube.com/rocketseat

## Cursos Pago de React Native

http://lp.b7web.com.br/rn-pre-venda/

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

## Módulo 8 - Entendendo PROPS

Carregamento de imagens externas

        import React, { Component } from 'react';
        import { View, Text, Image } from 'react-native';

        export default class PrimeiroProjeto extends Component {

            render() {

                let imagem = {uri:'https://cdn3.iconfinder.com/data/icons/luchesa-vol-9/128/Lollipop-512.png'};

                return (
                    <View>
                    <Text>Olá Mundo</Text>
                    <Text>Olá Mundo</Text>
                    <Text>Olá Mundo</Text>
                    <Text style={{fontSize:25, color:'red', margin:20}}>Olá Mundo</Text>

                    <Image source={{uri:'https://cdn3.iconfinder.com/data/icons/softicons/PNG/Tips.png'}} style={{width:128, height:128}} />

                    <Image source={imagem} style={{width:128, height:128}} />
                    </View>
                );

            }
        }

## Módulo 8 - Criando Próprios Componentes

Carregamento de imagens de forma dinâmica

        import React, { Component } from 'react';
        import { View, Text, Image } from 'react-native';

        class Imagem extends Component {

            render() {

                let imagem = {
                    uri:'https://cdn3.iconfinder.com/data/icons/luchesa-vol-9/128/'+this.props.nome+'.png'
                };

                return (

                        <Image source={imagem} style={{width:parseInt(this.props.largura), height:parseInt(this.props.altura)}} />

                );
            }

        }

        export default class PrimeiroProjeto extends Component {

            render() {

                return (
                    <View>
                    <Text>Olá Mundo</Text>
                    <Text>Olá Mundo</Text>
                    <Text>Olá Mundo</Text>
                    <Text style={{fontSize:25, color:'red', margin:20}}>Olá Mundo</Text>

                    <Imagem nome='Lollipop-512' largura='256' altura='256' />

                    Entendendo STATES</View>
                );

            }
        }

## Módulo 8 - Entendendo STATES

Lição referente a mudança automática dos tipos de comidas

    import React, { Component } from 'react';
    import { View, Text, Image } from 'react-native';

    class Janta extends Component {

    constructor(props) {
        super(props);
        this.state = {comida:props.comida};
        var comidas = ['Pizza', 'Lasanha','Burger','Sopa','Arroz'];

        setInterval(() => {

            this.setState(previousState => {
                var n = Math.floor(Math.random() * comidas.length);

                return {comida: comidas[n] };

            });

        }, 1000);

    }

    render() {
        return (
                <View>
                <Text style={{textAlign:'center', fontWeight:'bold', fontSize:20, color:'red'}}>Hoje você vai jantar:</Text>
                <Text style={{textAlign:'center', fontSize:20,}}>{this.state.comida}</Text>
                </View>
        );
    }
    }

    export default class PrimeiroProjeto extends Component {

    render() {

        return (
            <View style={{padding:20}}>

            <Janta comida='Bolacha' />

            </View>
        );

    }
    }

## Módulo 8 - Grupos de Styles

Formatação com estilos


    import React, { Component } from 'react';
    import { View, Text, StyleSheet } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    render() {

        return (
                <View style={styles.padrao}>
                <Text style={styles.azulGrande}>Este é o texto 1</Text>
                <Text style={styles.vermelho}>Este é o texto 2</Text>
                <Text style={[styles.azulGrande, styles.vermelho]}>Este é o texto 3</Text>
                <Text style={[styles.vermelho, styles.azulGrande]}>Este é o texto 4</Text>
                </View>
        );
    }
    }

    const styles = StyleSheet.create ({
    padrao: {
        paddingTop:20,
        backgroundColor: '#00FF00'
    },
    azulGrande: {
        color:'#0000FF',
        fontSize:30,
        textAlign:'center'
    },
    vermelho: {
        color:'#FF0000',
        fontSize:20,
    }
    });


## Módulo 8 - Tamanho Fixo e Dinâmico

Estruturação de Layouts


    import React, { Component } from 'react';
    import { View, Text } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    render() {

        return (
                <View style={{flex:1, backgroundColor:'green'}}>
                <View style={{flex:1, backgroundColor:'blue'}}></View>
                <View style={{flex:1, height:100, backgroundColor:'orange'}}></View>
                <View style={{flex:2, height:100, backgroundColor:'yellow'}}></View>
                <View style={{flex:3, height:200, backgroundColor:'black'}}></View>
                </View>
        );
    }
    }

## Módulo 8 - Flexbox e alinhamentos

Alinhamento de itens com flexbox

    import React, { Component } from 'react';
    import { View, Text } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    render() {

        return (
                <View style={{flex:1, flexDirection:'row', justifyContent:'center', alignItems:'center'}}>
                <View style={{width:200, height:100, backgroundColor:'blue'}}></View>
                </View>
        );
    }
    }

## Módulo 8 - Recebendo dados do usuário

Prenchendo o input com o nome e apresentando a mensagem abaixo Olá, Nome

    import React, { Component } from 'react';
    import { View, Text, TextInput, StyleSheet } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    constructor(props) {
        super(props);
        this.state = {texto:''}

        this.mudarTexto = this.mudarTexto.bind(this);
    }

    mudarTexto(t) {
        let s = this.state;
        if(t.length > 0) {
            s.texto = 'Olá, '+t;
        }else {
            s.texto = '';
        }
        this.setState(s);
    }

    render() {

        return (
            <View style={{paddingTop:30}}>

            <TextInput style={styles.input} placeholder="Qual seu nome?" onChangeText={this.mudarTexto} />

            <Text style={styles.texto}> {this.state.texto} </Text>

            </View>
        );
    }
    }

    const styles = StyleSheet.create ({
    input: {
        height:40,
        borderWidth:1,
        borderColor:'#000000',
        margin:10,
        padding:10
    },
    texto:{
        fontSize:20,
        textAlign: 'center'
    }
    });

## Módulo 8 - Lidando com botões e ações

Parte 1

    import React, { Component } from 'react';
    import { View, Text, Button, Alert, TextInput, StyleSheet } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    constructor(props) {
        super(props);
        this.state = {inputTexto:'',texto:''}

        this.apertouBotao = this.apertouBotao.bind(this);
    }

    apertouBotao() {
        let s = this.state;
        s.texto = "Olá, "+s.inputTexto;
        this.setState(s);
    }

    render() {

        return (
            <View style={{paddingTop:30}}>

                <TextInput style={styles.input} placeholder="Qual seu nome?" onChangeText={(inputTexto) => this.setState({inputTexto})} />

                <Button title="Aperte em mim" onPress={this.apertouBotao} />

                <Text style={styles.texto}>{this.state.texto}</Text>

            </View>
        );
    }
    }

    const styles = StyleSheet.create({
    input:{
        height:40,
        borderWidth: 1,
        borderColor: '#000000',
        margin:10,
        padding:10
    },
    texto: {
        fontSize:20,
        textAlign:'center'
    }
    })

Parte 2

    import React, { Component } from 'react';
    import { View, Text, Button, Alert, TextInput, StyleSheet } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    constructor(props) {
        super(props);
        this.state = {inputTexto:'',texto:''}

        this.apertouBotao = this.apertouBotao.bind(this);
    }

    apertouBotao() {
        let s = this.state;
        
        if(s.inputTexto == 'Bonieky') {
            s.texto = "Você acertou";
         } else {
                s.texto = "Você errou!";
        }

        this.setState(s);
    }

    render() {

        return (
            <View style={{paddingTop:30}}>

                <TextInput style={styles.input} placeholder="Advinhe meu nome" onChangeText={(inputTexto) => this.setState({inputTexto})} />

                <Button title="Aperte em mim" onPress={this.apertouBotao} />

                <Text style={styles.texto}>{this.state.texto}</Text>

            </View>
        );
    }
    }

    const styles = StyleSheet.create({
    input:{
        height:40,
        borderWidth: 1,
        borderColor: '#000000',
        margin:10,
        padding:10
    },
    texto: {
        fontSize:20,
        textAlign:'center'
    }
    })

## Módulo 8 - Projeto: App Criador de Memes

    import React, { Component } from 'react';
    import { View, StyleSheet, Text, TextInput, Image } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    constructor(props){
        super(props);
        this.state = {texto1:'Alguma Coisa', texto2:'Texto2'};

        this.escrever = this.escrever.bind(this);
    }

    mudarVogais(texto){
        let novoTexto = texto.toLowerCase();

        novoTexto = novoTexto.replace(/(a||i|o|u)/g, 'i');
        novoTexto = novoTexto.replace(/(á|à|ã|â)/g, 'i');
        novoTexto = novoTexto.replace(/(é|è|ê)/g, 'i');
        novoTexto = novoTexto.replace(/(í|ì|î)/g, 'i');
        novoTexto = novoTexto.replace(/(ó|ò|ô)/g, 'i');
        novoTexto = novoTexto.replace(/(ú|ù|û)/g, 'i');

        return novoTexto;
    }


    escrever(t){
        let s = this.state;
        s.texto1 = t;
        s.texto2 = this.mudarVogais(t);
        this.setState(s);
    }

    render() {

        return (
            <View style={styles.body}>

                <View>
                    <Text style={styles.titulo}>Criador de Mimimi</Text>
                </View>

                <View style={styles.inputArea}>
                    <TextInput style={styles.input} placeholder = "Digite seu mimimi" onChangeText={this.escrever} />
                </View>

                <View style={styles.area}>
                    <Text style={[styles.texto, styles.texto1]} >{this.state.texto1.toUpperCase()}</Text>
                    <Image style={styles.guri} source={require('./images/mimimi.jpg')} />
                    <Text style={[styles.texto, styles.texto2]} >{this.state.texto2.toUpperCase()}</Text>
                </View>

            </View>
        );
    }
    }

    const styles = StyleSheet.create({
        body:{
            backgroundColor:'#999999',
            paddingTop:30,
            flex:1,
            flexDirection:'column',
            alignItems: 'center'
        },
        titulo:{
            fontSize:30,
            color:'#FFFFFF'
        },
        inputArea:{
            alignSelf: 'stretch'
        },
        input:{
            borderWidth:1,
            borderColor:'#999999',
            backgroundColor: '#EEEEEE',
            color: '#000000',
            height:40,
            margin: 20,
            padding:10
        },
        area:{
            width:300,
            height:300,
            marginTop:10
        },
        guri:{
            width:300,
            height:300,
            marginTop:-70,
            zIndex:0
        },
        texto:{
            fontSize:25,
            color: '#FFFFFF',
            padding:10,
            backgroundColor: 'transparent',
            fontWeight: 'bold',
            textAlign: 'center',
            height: 70
        },
        texto1:{
            zIndex:1
        },
        texto2:{
            zIndex:1,
            marginTop:-70
        }
    });


## Módulo 8 - App Contador de Água


    import React, { Component } from 'react';
    import { View, StyleSheet, ImageBackground, Text, Button } from 'react-native';

    export default class PrimeiroProjeto extends Component {

    constructor(props) {
        super(props);
        this.state = {consumido:0, status:'Ruim', pct:0};

        this.addCopo = this.addCopo.bind(this);
        this.atualizar = this.atualizar.bind(this);
    }

    atualizar(){
        let s = this.state;
        s.pct = Math.floor ((s.consumido/2000)*100);

        if(s.pct >= 100){
            s.status = "Bom";
        } else {
            s.status = "Ruim";
        }
        
        this.setState(s);
        }

    addCopo() {
        let s = this.state;
        s.consumido += 200;
        this.setState(s);

        this.atualizar();

    }

    render() {
        return (
            <View style={styles.body}>
                <ImageBackground source={require('./images/waterbg.png')} style={styles.bgimage}>
                <View>
                    
                        <View style={styles.infoArea}>
							<View style={styles.area}>
								<Text style={styles.areaTitulo}>Meta</Text>
								<Text style={styles.areaDado}>2000ml</Text>
							</View>
							<View style={styles.area}>
								<Text style={styles.areaTitulo}>Consumido</Text>
								<Text style={styles.areaDado}>{this.state.consumido}ml</Text>
							</View>
							<View style={styles.area}>
								<Text style={styles.areaTitulo}>Status</Text>
								<Text style={styles.areaDado}>{this.state.status}</Text>
							</View>
						</View>

						<View style={styles.pctArea}>
							<Text style={styles.pctText}>{this.state.pct}%</Text>
						</View>

                        <View style={styles.btnArea}>
                            <Button title="Bebe 200ml" onPress={this.addCopo} />
                        </View>
                        
				</View>

            </ImageBackground>
        </View>
        );
    }        flexDirection:'row',
        marginTop:70

    }

    const styles = StyleSheet.create({
    body:{
        flex:1,
        paddingTop:20
    },
    bgimage:{
        flex:1,
        width:null
    },
    infoArea:{
        flex:1,
    },
    area:{
        flex:1,
        alignItems:'center'

    },
    areaTitulo:{
        color: '#45B2FC'
    },
    areaDado:{
        color: '#2b4274',
        fontSize:20,
        fontWeight: 'bold'
    },
    pctArea:{
        marginTop: 300,
        alignItems:'center'

    },
    pctText:{
        fontSize:50,
        color: '#000000',
        backgroundColor: 'transparent'
    },
    btnArea:{
        marginTop:30,
        alignItems:'center'
    }
    });