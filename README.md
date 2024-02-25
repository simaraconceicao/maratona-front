# Maratona | Seu Projeto no Ar - Front-end 🚀 

![image](https://media2.giphy.com/media/D567hs4Dex0GEnAKOY/giphy.gif)
<aside>
⚠️ Este repositório é um template feito para ensinar fundamentos de desenvolvimento web para pessoas iniciantes.
</aside>

<br>

## `Como usar este template:`

- Com o link do template aberto no navegador, clique na setinha ao lado do botão verde "USE THIS TEMPLATE" e escolha a opção "Create a new repository";

- Após isso vá para o repositório criado no seu perfil do github, clique na setinha ao lado do botão verde "CODE" e copie o código;

- Agora vá até o terminal no seu computador e use o código: git clone 'link copiado'

- Com seu repositório baixado na sua máquina, execute o comando ``npm install`` na pasta dentro projeto clonado para instalar todas as dependências.

- Agora rode o projeto com o comando ``npm run dev`` 

## `Apresentação`

✓		[Slides](https://www.canva.com/design/DAF91GMXJqk/7JD35oioymzZsDEICh_0MA/edit?utm_content=DAF91GMXJqk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)


## ReactJS para Iniciantes - Guia Rápido

### O que é ReactJS?
ReactJS é uma biblioteca JavaScript para construir interfaces da pessoa usuária. Ele foi desenvolvido pelo Facebook e é mantido pela comunidade de software livre.

**Pra facilitar o entendimento:**

Imagine que você está construindo uma casa e o ReactJS é como o arquiteto que facilita a construção e a organização dos diferentes componentes da sua casa, permitindo que eles interajam de maneira eficiente.

#### Quem Usa ReactJS?

Grandes empresas como Facebook, Instagram, Airbnb, Tiktok, Twitter, Netflix e muitas outras, utilizam ReactJS em suas aplicações devido à sua eficiência e facilidade de desenvolvimento.

#### Hello World / Olá Mundo
Vamos começar com o básico, o "Hello World" no ReactJS.

**Pra facilitar o entendimento:**

Seria como ligar a luz na sua casa pela primeira vez, apenas para ter certeza de que tudo está funcionando corretamente.

```jsx
function App() {
  return <h1>Hello, World!</h1>;
}

export default App;
```

#### O que é jsx


JSX (JavaScript XML) é uma extensão de sintaxe para JavaScript, frequentemente associada ao desenvolvimento de interfaces de pessoa  usuária usando a biblioteca React.

Isso permite que você utilize todo o poder do JavaScript para lógica de renderização e manipulação de dados enquanto constrói interfaces de pessoa  usuária declarativas e componentizadas.

#### Rodando Código com Vite

Vite é uma ferramenta de desenvolvimento rápida para o ecossistema JavaScript. Para rodar o código ReactJS com Vite, você pode usar os seguintes comandos:

```bash
// após clonar o projeto, instale as dependências:

npm install

// após pode rodar o projeto e abrir o localhost no navegador:

npm run dev
```


#### O que é Localhost

Em termos simples, quando você acessa "localhost" em um navegador da web, está se referindo ao seu próprio computador.

Em termos técnicos, quando você acessa "localhost" no seu navegador ou em algum aplicativo, está pedindo ao seu próprio dispositivo para fornecer os dados ou serviços, sem sair do seu computador.

#### Como funcionam os arquivos dentro do ReactJS

**App.jsx:** Este é um componente funcional React que representa a estrutura principal da aplicação. Ele exporta esse componente para ser usado em outros arquivos.

**main.jsx:** Este arquivo serve como o ponto de entrada da aplicação. Ele importa o componente App e renderiza dentro do elemento com o ID 'root'. O uso de ReactDOM.createRoot é uma abordagem moderna para renderização assíncrona.

**index.html:** Este é o arquivo HTML principal da aplicação. Ele possui uma <div> com o ID 'root' onde o conteúdo React será renderizado. O script no final do arquivo (main.jsx) é o ponto de entrada do aplicativo.

**package.json:** Arquivo de configuração do Node.js e npm. Ele lista as dependências do projeto, scripts de desenvolvimento e outros. As dependências incluem o React, ReactDOM, e outras ferramentas relacionadas ao desenvolvimento.

#### Qual o papel do CSS num projeto ReactJS?

O CSS (Cascading Style Sheets) desempenha um papel crucial no ReactJS, assim como em qualquer aplicação web. No contexto do React, o CSS é usado para estilizar os componentes e garantir uma apresentação visual atraente e coesa. Aqui estão algumas das principais funções do CSS no desenvolvimento React:

* Estilização de Componentes:

O CSS é fundamental para a estilização de elementos HTML renderizados pelos componentes React. Ele define a aparência, cores, tamanhos e outros aspectos visuais.

* Reutilização de Estilos:

Ao modularizar o CSS e aplicar classes apropriadas, é possível reutilizar estilos em diferentes componentes. Isso promove consistência visual e facilita a manutenção.

* Responsividade:

O CSS é utilizado para tornar a aplicação responsiva, garantindo que os componentes se ajustem e exibam corretamente em diferentes dispositivos e tamanhos de tela.

#### O que é estado e o que é o hook useState

Em React, o "estado" refere-se a um conceito que descreve a condição atual de um componente. O estado é uma forma de armazenar dados no componente que podem mudar ao longo do tempo, influenciando a renderização do componente. Ele representa a "memória" do componente e permite que ele reaja a eventos e atualize dinamicamente sua aparência ou comportamento.

O hook useState é uma funcionalidade do React que permite aos componentes funcionais terem estado. A introdução dos Hooks no React foi na versão 16.8.

```jsx
import React, { useState } from 'react';

function Contador() {
  // O useState retorna um array com duas posições: a variável de estado e uma função para atualizá-la.
  const [contador, setContador] = useState(0);

  return (
    <div>
      <p>Você clicou {contador} vezes.</p>
      <button onClick={() => setContador(contador + 1)}>
        Clique aqui
      </button>
    </div>
  );
}

export default Contador;

```

#### O que é e qual a importancia do *Key* quando iteramos uma lista em react

A propriedade key é um atributo especial em React usado ao renderizar listas de elementos. Ela ajuda o React a identificar de maneira única cada elemento da lista, permitindo uma renderização eficiente e evitando problemas de desempenho. A key é uma informação que deve ser única entre os irmãos em uma lista.

```jsx

const listaDeItens = [
  { id: 1, nome: 'Item 1' },
  { id: 2, nome: 'Item 2' },
  { id: 3, nome: 'Item 3' },
];

const elementosDaLista = listaDeItens.map(item => (
  <li key={item.id}>{item.nome}</li>
));

return <ul>{elementosDaLista}</ul>;

```

-----
_Vai ser incrível compartilhar essa jornada com você! Qualquer dúvida ou sugestão, chama no contatinho!_

 <img src="https://media.giphy.com/media/efhcZv18NpQDyRsaYa/giphy.gif" alt="Gif Yeah" width="200"> 

# Simara Conceição
✓	Desenvolvedora na Thoughtworks

✓	Criadora do Quero Ser Dev, projeto que inspira e ajuda pessoas diversas na migração de carreira pra área de tecnologia.

### Vamos nos conectar!

- [youtube](https://www.youtube.com/queroserdev)
- [instagram](https://www.instagram.com/simara_conceicao)
- [linkedin](https://www.linkedin.com/in/simaraconceicao/)
- [github](https://github.com/simaraconceicao)
- [spotify](https://open.spotify.com/show/59vCz4TY6tPHXW26qJknh3)
- [quero ser dev](https://queroserdev.com)

<br>
Feito com 💜 por Simara Conceição | Quero Ser Dev