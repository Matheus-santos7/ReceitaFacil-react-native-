# Bem-vindo ao Receita Fácil!
<h1 align="center">
    <img height="200" src="https://ik.imagekit.io/lcf9dsx9t/App_Receita_F%C3%A1cil__1__page-0002.jpg?updatedAt=1681151638742">
    <img height="200" src="https://ik.imagekit.io/lcf9dsx9t/App_Receita_F%C3%A1cil__1__page-0003.jpg?updatedAt=1681151638644">
    <img height="200" src="https://ik.imagekit.io/lcf9dsx9t/App_Receita_F%C3%A1cil__1__page-0004.jpg?updatedAt=1681151638387">
    <img height="200" src="https://ik.imagekit.io/lcf9dsx9t/App_Receita_F%C3%A1cil__1__page-0006.jpg?updatedAt=1681151638355">
    <img height="200" src="https://ik.imagekit.io/lcf9dsx9t/App_Receita_F%C3%A1cil__1__page-0005.jpg?updatedAt=1681151637820">
    <img height="200" src="https://ik.imagekit.io/lcf9dsx9t/App_Receita_F%C3%A1cil__1__page-0007.jpg?updatedAt=1681151633001">
</h1>
O Receita Fácil é um aplicativo de compartilhamento de receitas de comida desenvolvido em React Native. O aplicativo é compatível com dispositivos iOS e Android e faz uso do Axios para fazer chamadas HTTP para um servidor JSON. É necessário rodar um servidor local JSON com a ferramenta JSON Server para utilizar o aplicativo. O aplicativo foi desenvolvido pelo canal Sujeito programador em um workshop para mostrar como cria um aplicativo do zero.

## Instalação

Para instalar o aplicativo em um dispositivo móvel, siga as seguintes etapas:

1. Certifique-se de ter o Node.js instalado em sua máquina.
2. Clone o repositório do Receita Fácil para sua máquina local usando o Git.
3. No diretório raiz do projeto, execute o seguinte comando para instalar as dependências:

npm install

4. Certifique-se de ter o expo-cli instalado. Se não tiver, instale com o seguinte comando:

npm install -g expo-cli

5. Para iniciar o aplicativo, execute o seguinte comando:

npx expo start

Isso abrirá o console do Expo no seu navegador. Use-o para escanear o QR code e iniciar o aplicativo no dispositivo móvel.

## Configuração do Servidor JSON

Para configurar o servidor JSON e permitir a conexão com o aplicativo Receita Fácil, siga as seguintes etapas:

1. Certifique-se de que o arquivo db.json está presente no diretório raiz do projeto.
2. Execute o seguinte comando no diretório raiz do projeto para rodar o servidor JSON:

json-server -w -d 180 --host IP db.json


Substitua IP pelo endereço IP da sua rede local. Certifique-se de que a porta 3000 está livre para uso.

3. Na pasta do projeto, navegue até a pasta services.
4. Abra o arquivo api.js em um editor de código.
5. Na linha `baseURL`, substitua o endereço IP `192.168.0.2` pelo endereço IP correspondente da sua rede local. Certifique-se de que o servidor JSON está sendo executado na mesma rede local e que o endereço IP é correto.
6. Salve as alterações no arquivo api.js.

Com essas configurações, o aplicativo Receita Fácil poderá fazer chamadas HTTP para o servidor JSON local e acessar as informações necessárias para exibir as receitas aos usuários.

## Utilização

O aplicativo Receita Fácil permite que os usuários encontrem e compartilhem receitas de comida. Para usar o aplicativo, siga as seguintes etapas:

1. Na tela inicial do aplicativo, você pode escolher entre procurar por receitas ou compartilhar suas próprias receitas.
2. Se você escolher a opção de busca, poderá procurar por receitas usando palavras-chave.
3. Se você escolher a opção de compartilhamento, poderá criar e compartilhar sua própria receita com outros usuários.

## Desenvolvodo por Matheus Santos 🧑🏾‍💻
