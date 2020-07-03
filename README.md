#COMO RODAR O PROJETO BAIXADO

###SEQUENCIA EXECUTADAS E BIBLIOTECAS INSTALADAS DURANTE A SEMANA DE IMERSÃO &nbsp;

Criar o arquivo package.json
```npm init```

Instalar o react e o next [https://nextjs.org/docs/getting-started](https://nextjs.org/docs/getting-started)
``` npm install next react react-dom```

Abra o package.json e adicione o seguinte script:
```
"scripts": {
  "dev": "next",
  "build": "next build",
  "start": "next start"
}
```

Criar uma pasta chamada pages e dentro dela um arquivo index.js com a seguinte informação:
```
function HomePage() {
    return <div>Welcome to Next.js!</div>
  }
  
  export default HomePage
```

Roda o projeto
```npm run dev```

Abrir o projeto no endereço padrão
[ttp://localhost:3000](ttp://localhost:3000)


Instalar o Bootstrap
```npm install --save bootstrap```

Instalar o Reactstrap
```npm install --save reactstrap```

Importar o boostrap na index 
import 'bootstrap/dist/css/bootstrap.min.css';

Instalar a biblioteca para inserir o CSS diretamente no HTML. [https://github.com/vercel/next-plugins/tree/master/packages/next-css](https://github.com/vercel/next-plugins/tree/master/packages/next-css)
```npm install --save @zeit/next-css```

Instalar os icones [https://www.npmjs.com/package/@fortawesome/react-fontawesome#typescript](https://www.npmjs.com/package/@fortawesome/react-fontawesome#typescript)
```npm i --save @fortawesome/fontawesome-svg-core  @fortawesome/free-solid-svg-icons @fortawesome/react-fontawesome```
