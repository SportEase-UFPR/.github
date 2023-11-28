# SportEase UFPR
## 🔗Acessar a versão hospedada

Caso deseje, nosso sistema também está hospedado para utilização sem necessidade de instalação local

> **OBS:** Para logar como administrador use os seguintes dados de login:
> 	 - e-mail: adm@gmail.com
>   - senha: 123456

|Aplicação| Link |
|--|--|
|Aplicativo mobile | [app](https://expo.dev/@nathansr6/mobile-sport-ease?serviceType=classic&distribution=expo-go) |
|Website cliente | [site](https://sportease-client.netlify.app/login) |
|Website administrador | [site](https://sportease-manager.netlify.app/login) |


## Acessar a versão local

### 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você deve ter instalado as seguintes linguagens e frameworks:
	1.  [Angular](https://v16.angular.io/guide/setup-local)
	2. [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
	3. [Maven](https://maven.apache.org/download.cgi)
	4. [MySQL](https://www.mysql.com/downloads/)
	5. [Node.js](https://nodejs.org/en)
	6. [React Native](https://www.npmjs.com/package/react-native)
	7. [TypeScript](https://www.typescriptlang.org/download)
	8. [Expo CLI](https://www.npmjs.com/package/expo-cli)
	9. [Git](https://git-scm.com/downloads)

### 🚀 Instalando e usando o SportEase UFPR

Para instalar o SportEase UFPR, siga estas etapas:

- **Instalar API Gateway e Microsserviços**
Clone os repositórios correspondentes e para cada um deles acesse a pasta e repita os comando abaixo
```sh
mvn clean install
```
```sh
mvn spring-boot:run
```

- **Instalar aplicação mobile**

 1. Clone localmente esse repositório através do comando abaixo:
	```shell 
	git clone https://github.com/SportEase-UFPR/mobile-sport-ease.git
	```

2. Acesse o repositório local baixado em seu computador e dentro do terminal utilize o seguinte comando:

	```shell 
	npm install
	```
3. Após a instalação, execute a aplicação através do comando abaixo:
	```shell 
	npx expo start	
	```

- **Instalar aplicação web (cliente e administrador)**
Clone os repositórios correspondentes e para cada um deles acesse a pasta e repita os comando abaixo

```sh
npm install
```
```sh
ng s -o
```

### Utilizando localmente pela primeira vez

 - Ao iniciar a aplicação pela primeira vez, um administrador é criado automaticamente. Os dados de login são: 
	 - e-mail: adm@gmail.com
	 - senha: 123456
