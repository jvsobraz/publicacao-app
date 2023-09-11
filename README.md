# React Native - Publicando APP

## Hybrid Mobile App Development

## Publicando APP

Lojas de aplicativos:

Como criamos nosso app em react native, temos o poder de publicar agora apps tanto
para android quanto para iOs, mas antes de iniciar com a publicação de nosso app
temos primeiro que entender aonde vamos publicar, para isso temos que entender que
temos 2 principais lojas, sendo elas a google play para android e a apple store para iOs.

![Screenshot 2023-09-11 111658](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/d0a6bbd9-3045-4d8b-be19-5746b84c6ad8) ![Screenshot 2023-09-11 111727](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/3e87973f-cb3f-407f-820b-8e4110dd2ec4)

*Observação*: 

Temos algumas lojas não oficiais, principalmente para o android, mas o nosso foco
será sempre para as lojas oficiais.

*Consoles*:

Para conseguirmos publicar nosso app temos que ter contas de desenvolvedor em cada loja
para que assim consigamos publicar. Na google play temos o console da google play:

![Screenshot 2023-09-11 111854](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/f94d4f4f-6dfe-4f32-b1e1-6b385c494031)

E acessando o console temos a opção de Criar conta podemos criar uma nova conta ou até
usar nossa própria conta pessoal e transformá-la em desenvolvedora:

![Screenshot 2023-09-11 111942](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/d908bf22-3b7b-4404-a529-5c567d31aee7)

E na apple temos a developer apple:

![Screenshot 2023-09-11 112015](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/909c10da-df31-4877-b1e8-d5cbe5d8d877)

Que também é necessário criar uma conta de desenvolvedor:

![Screenshot 2023-09-11 112044](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/10735210-381c-4b09-9286-01f8a9fc0c0e)

*Preço*:

Mas nada disso é gratuito, hoje cada loja cobra um valor por esse serviço que utilizamos
para fazer a publicação e gestão dos nossos apps, sendo eles:

● Android - No android temos um pagamento único de 25 dólares para concluir o registro
e assim continuar usando pra um número ilimitado de apps.

● Apple - Na Apple já temos uma taxa de 99 dólares por ano, não é único como no
android se tornando assim um serviço mais caro, se essa taxa não for renovada todo
ano, pode acontecer de você ter o seu app fora do ar.

*Dica de cloud*:

Tomem cuidado, para que possamos publicar nosso app na apple store, precisamos ter um
macbook, no caso de não ter um macbook e quiser utilizar um windows ou algo do tipo,
temos algumas opções pra fazer isso, sendo uma delas o macincloud. Eles tem vários preços, tipos de
computadores em nuvem para que possamos utilizar com essa finalidade, com isso em mente, podemos partir agora para a publicação do app de fato.

## Iniciando as configurações:

Para essa publicação irei pegar um repositório em react native CLI para mostrar como faremos no android e iOs. Primeiro vamos abrir o projeto no Android Studio. Para isso vamos clicar em Open Logo depois devemos selecionar a nossa pasta android:

![Screenshot 2023-09-11 112327](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/f40d6261-05c0-4968-8f86-70b64f30e3e5)

Devemos ter o projeto da seguinte forma, rodando alguns processos em background, vamos
esperar tudo rodar e aparecer nosso projeto na esquerda:

![Screenshot 2023-09-11 112412](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/6b85c0c4-f42f-411c-bd3b-ae8f816ce8e0)

Com o projeto aberto ali, e depois de rodar nosso
projeto no vscode normal, devemos ter o nosso
app com esse ícone e com o nome do nosso app:

![Screenshot 2023-09-11 112440](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/d0083e34-3be4-4fcd-99ec-2391440d01d4)

## Configurando Ícone e Título

No nosso caso do slide anterior, temos o aplicativo
mobile, com o ícone padrão do android, o que vamos
fazer agora é mudar esse ícone e esse nome, para isso
vamos no nosso projeto no android studio que já está
aberto, clicamos com o lado direito em app dentro do
android, clicamos em new e depois em Image Asset:

![Screenshot 2023-09-11 112512](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/a8259391-88f2-45db-8ec1-4b4aa0c77fb1)

Image asset é uma ferramenta padrão do android para geração de ícones, clicando nela
devemos ter a seguinte tela:

![Screenshot 2023-09-11 112619](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/51cc80cd-675e-4e44-9896-d25f108e008e)

Então, deixamos por padrão o que
está marcado e vamos mexer em uma
coisa que é o “Path”e procuraremos a
nossa logotipo, que no meu caso é um
logo da FIAP.

No meu caso dessa logo podemos ver que não se encaixa dentro do circulo, e temos que ter
essa logo dentro do circulo para rodar bem, por isso clicamos em “Yes” no Trim:

![Screenshot 2023-09-11 112710](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/7ae9c954-f5f4-4037-ae77-ae994b861ae6)

Isso vai fazer com que nossa
imagem fique dentro do circulo, se
acontecer de não ficar, podemos
mexer no resize também.

Depois de selecionar o Trim teremos o fundo verde em algumas imagens, isso porque também
temos um background que pode se de qualquer cor:

![Screenshot 2023-09-11 112746](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/2c2aa59f-90c0-43bc-a0b6-cd4a5a9cf5a9)

Por isso podemos clicar em Background Layer e mudar nosso Asset Type para color, como
podemos ver nosso background está verde e não desejamos essa cor, e como a cor de fundo
do nosso ícone é branco, podemos apenas colocar na caixa de cor o branco:

![Screenshot 2023-09-11 112813](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/3272d6d5-85df-467a-b0bb-0fd6b1b5e803)

Com isso pronto podemos dar Next e
veremos na próxima tela o que está
sendo inserido e em qual nível de pasta.

Podemos dar o finish e Add na próxima página e devemos ter tudo configurado, podemos voltar
para o vscode e rodar nosso projeto novamente para vermos o resultado da alteração.

![Screenshot 2023-09-11 112852](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/256f8428-56fa-4732-9e6b-a57e7d8bae22)

Como vemos, mudamos o ícone e agora vamos
para o nome:

![Screenshot 2023-09-11 112927](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/8c27bc0e-494d-4365-9419-7b6c9359ee4f)

Vamos em android > src > main > res > values >
strings.xml:

![Screenshot 2023-09-11 113003](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/43fa1d08-bd9d-4a1b-a526-08ffd2094e1f)

Abrindo esse arquivo teremos o nosso nome antigo mobile e substituiremos para FIAP:

![Screenshot 2023-09-11 113034](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/e8c23b63-4410-4332-959a-74f0bc5cad21)

Com isso podemos rodar novamente e já
deve estar completo com o logo e texto
mudados:

![Screenshot 2023-09-11 113100](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/780e0f25-75a6-4725-92ee-1b67168e8075)

## Gerando bundle:

Agora vamos gerar o bundle para subir para as lojas, o bundle é um pacote com todas as
informações do nosso aplicativo que serão reconhecidos pela loja e gerado nosso app,
para fazer isso podemos seguir a doc https://reactnative.dev/docs/signed-apk-android.

Mas vamos seguir passo a passo juntos.

Para iniciar precisamos gerar uma chave de acesso para nosso app, no windows
precisamos entrar dentro do path do JDK e gerar lá dentro, e no mac e linux temos isso de
forma global podendo gerar essa chave de qualquer lugar, então vamos pegar o código que
a doc nos disponibiliza e usar no console do vscode, no meu caso estou usando o console
do projeto mesmo.

Usando o código a seguir nós conseguiremos gerar uma chave:

![Screenshot 2023-09-11 113237](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/4eeb2dc3-9b44-43f9-b719-fcf4b9f81a89)

Nós podemos fazer algumas alterações, onde temos “my-upload-key.keystore” vou alterar
para “fiap.keystore” e o "my-key-alias” vou mudar para "fiap-key-alias” isso vai me fazer
identificar melhor nossas chaves, dando enter vai nos ser feito uma série de pergunta, como
senha para nossa chave, nome, empresa, país e etc, guarde sempre essa informação.

![Screenshot 2023-09-11 113311](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/33c2a8e3-a83f-492b-9a12-0537eaf972fb)

Informações geradas da chave:

![Screenshot 2023-09-11 113346](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/9393dbb0-b621-4dae-82d2-86e347507f8c)

Como eu dei o comando dentro da pasta android, o nosso arquivo de chave já está criado ali
dentro:

![Screenshot 2023-09-11 113409](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/3f688cf6-e47c-4062-9d60-7dd7d58153c7)

Agora temos que definir quais são as variáveis para nosso certificado da google play, para
isso podemos editar nosso gradle.properties para entrar la teremos que apenas ir em android
> gradle.properties, e colocar nossas variáveis que serão da seguinte maneira no nosso caso:

![Screenshot 2023-09-11 113442](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/cffd39c5-0995-4417-87d4-d95f58c176e2)

![Screenshot 2023-09-11 113503](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/0453890c-eba8-4c92-9d39-61ba36cbb89f)

Com isso configurado podemos agora adicionar nossa configuração pro app, indo em
android > app > build.gradle, e procuramos por signingConfigs e adicionamos o seguinte
código dentro dela:

![Screenshot 2023-09-11 113525](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/4e166dae-437d-455b-93c0-e93bb2cd70a1)

esse trecho de código vai conferir se
há as informações de chave de
release e puxar essas informações,
devendo ficar assim:

![Screenshot 2023-09-11 113554](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/3c163846-6bd3-4d71-a5f7-b60f7989c16a)

E logo abaixo em release temos essa config do signingConfig que traz o
signingConfigs.debug como default, devemos trocar ele para release para que funcione tudo
certo:

![Screenshot 2023-09-11 113616](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/0034b2ad-126e-4a0c-8513-26f453e67023)

Com tudo isso pronto agora podemos gerar nosso bundle para a loja, então no console
entramos na pasta android e damos o seguinte comando:

![Screenshot 2023-09-11 113636](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/5971ade2-1df6-4113-bfe0-0132e50553bc)

Com o código dando certo devemos ter a seguinte mensagem:

![Screenshot 2023-09-11 113701](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/7e6df7b7-d31a-4e77-b43c-5d14edeedaa0)

Agora podemos achar nosso bundle em app > build > outputs > bundle > release

![Screenshot 2023-09-11 113725](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/31be7301-457c-4502-b1fa-b32fb75fcd7b)

## Subindo para a google play

Com esse arquivo em mãos podemos agora distribuir nosso app, para isso podemos entrar
no console da google e clicar em criar app:

![image](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/8ce94c2a-faa0-4bfa-86fc-0fe29d3d91d2)

Depois de ir em criar app teremos algumas
informações sendo elas:

● Nome do app

● Idioma padrão

● Se é um app ou jogo

● Se é gratuito ou Pago

● E um aceite das politicas de
privacidade que o app atende

![Screenshot 2023-09-11 113917](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/4e3b20db-4eda-4e8c-bc58-94bd334e4060)

Feito isso podemos clicar em criar app e nosso aplicativo já estará criado no console e
iremos direto para o Painel dele:

![Screenshot 2023-09-11 113938](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/0c3dc809-c197-4547-a3c4-6a4a3968f27d)

E nesse painel teremos todas
as infos que precisamos
preencher para que o app seja
publicado, inclusive um lugar
para importar o nosso bundle,
depois de tudo preenchido
podemos mandar para teste
interno, fechado, aberto e
produção.

Feito isso podemos clicar em criar app e nosso aplicativo já estará criado no console e
iremos direto para o Painel dele:

![Screenshot 2023-09-11 114008](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/871a8d58-60b8-4247-8d06-31b201846b47)

## Configurando Ícone e Título

Agora vamos para o iOs, e vamos fazer o mesmo processo pra ele, para isso vamos abrir o
xcode e abrir nosso projeto, mas no caso agora nós entraremos no ios, e abriremos o projeto
que tem como extensão o .xcworkspace, normalmente é o arquivo que utilizamos para editar
informações direto no xcode e não termos problemas:

![Screenshot 2023-09-11 114042](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/a3adb526-96de-4009-83e4-887a27ce874d)

Com o projeto aberto
podemos dar um play:

![Screenshot 2023-09-11 114104](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/796be6e7-dc18-4adc-a1d2-96435cae7e57)

Depois de rodar devemos ter o
mesmo projeto que tínhamos no
android, sem ícone e com um
nome diferente:

![Screenshot 2023-09-11 114126](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/8c29e477-3002-435b-8945-3daf95aeffcf)

Vamos começar resolvendo primeiramente nosso ícone, para isso vamos no nosso diretório do
projeto e seguir o caminho mobile > mobile > Images e depois clicar em AppIcon que é a nossa
raiz de ícones, que como podemos ver não tem nada:

![Screenshot 2023-09-11 114146](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/21625c5a-8098-4fa0-89b6-6d995f6b2d3f)

Para isso podemos utilizar um template disponibilizado pela rocket seat para modelos de
ícones no seguinte site:

![Screenshot 2023-09-11 114209](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/879ec0dd-0dac-4b68-8398-e2182a1b9609)

Teremos essa tela, e vamos duplicar para podermos editar:

![Screenshot 2023-09-11 114231](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/56f8fda3-a408-413e-a3c5-f377a6f29b49)

Editando esse logo 1 podemos substituir e assim ter o logo, depois de substituído, podemos
clicar em File > Export

![Screenshot 2023-09-11 114254](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/5bf4398b-fa3b-4c00-ba56-27df7172f237)

Depois de clicar vai aparecer do lado direito os nossos logos para exportar:

![Screenshot 2023-09-11 114313](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/b5aae7f6-7724-4768-b39d-9be00e6c02ec)

Depois de exportado nós arrastamos todos os ícones para dentro do nosso AppIcon ficando
da seguinte forma:

![Screenshot 2023-09-11 114333](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/9f24048d-7a03-41ac-b3c8-4f115812e4fc)

Com isso já temos todos os nossos ícones configurado para todo tipo de iphone, e para mudar
o nome é bem mais simples, clicamos no nome do nosso projeto em mobile:

![Screenshot 2023-09-11 114350](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/3f1e5e5f-07f9-4022-afe4-740670f412f9)

E alteramos o Display Name para o nome que queremos:

![Screenshot 2023-09-11 114411](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/fdd7eae3-a96c-4ab9-b663-4d6cfcf1449b)

Com isso já temos tudo mudado:

![Screenshot 2023-09-11 114432](https://github.com/jvsobraz/publicacao-app-FIAP/assets/100175547/566c5fea-b438-4e37-a4d7-8b355042e761)

