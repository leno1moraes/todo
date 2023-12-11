# projeto_todo_react_typescript
Projeto TO DO com React TypeScript


------------------------------------------------------------------


1. executar comandos:
	
	npm i gh-pages --save-dev

	
2. acrescentar no 'package.jon'_-_scripts essas:

	"predeploy": "npm run build",

	"deploy": "gh-pages -d dist"

	
3. acrescentar no 'package.jon':

	"homepage": <url_do_projeto_no_github>	

	
4. acrescentar no 'vite.config.ts'_-_export default:
	
	base: "/<nome_do_projeto_no_github>",

	
5. fazer o git push das modificações até aqui


6. executar comandos:
	
	npm run deploy