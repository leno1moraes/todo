![image](https://github.com/user-attachments/assets/a6cf2f3e-9c8f-4071-b353-b0c53ff6868d)


# Projeto To DO

Bem-vindo ao **To Do**, um projeto desenvolvido em React TypeScript utilizando Vite como ferramenta de build. Este aplicativo simples e eficiente permite que você cadastre tarefas com um título e um nível de dificuldade, ajudando a organizar suas atividades de forma prática e intuitiva.

Explore as funcionalidades e veja como ele pode facilitar o seu dia a dia. Além disso, você pode conferir uma demonstração ao vivo diretamente **https://leno1moraes.github.io/todo/**.

------------------------------------------------------------------

## How to UP!


### Requisitos
1 - Node 18 (nvm)
2 - NPM


### Comando
```
npm run dev
```

------------------------------------------------------------------

## Configurar GitPages


### 1. executar comandos:
```
npm i gh-pages --save-dev
```
	
### 2. acrescentar no 'package.jon'_-_scripts essas:
```
"predeploy": "npm run build",
```
```
"deploy": "gh-pages -d dist"
```
	
### 3. acrescentar no 'package.jon':
```
"homepage": <url_do_projeto_no_github>	
```
	
### 4. acrescentar no 'vite.config.ts'_-_export default:
```
base: "/<nome_do_projeto_no_github>",
```
	
### 5. fazer o git push das modificações até aqui
```
git add .
```
```
git commit -m [message]
```
```
git push
```

### 6. executar comandos:
```
npm run deploy
```

------------------------------------------------------------------

## Demos 

![image](https://github.com/user-attachments/assets/8d4e9370-83fa-43d4-ae77-6816a22faabd)

![image](https://github.com/user-attachments/assets/857eabbb-f3c4-41d7-b5ea-6d65e1d0fbca)

![image](https://github.com/user-attachments/assets/055fb6e5-ca27-41a7-bc89-75cc8c2c76e9)

Projeto baseado no curso: https://www.udemy.com/course/react-do-zero-a-maestria-c-hooks-router-api-projetos/

