## Sobre o Electron
Electron é uma biblioteca de código aberto desenvolvida pelo GitHub para o desenvolvimento de aplicativos desktop multiplataforma usando HTML, CSS e JavaScript. O Electron consegue isso combinando Chromium e Node.js em um único ambiente de execução. Aplicativos Electron podem ser empacotados para Mac, Windows e Linux.

Electron começou em 2013, como um framewok que seria utilizado para construir o Atom, o editor de texto hackeável do GitHub. Os dois foram disponibilizados na primavera de 2014, com seu código fonte aberto.

Desde então, ele se tornou uma ferramenta popular usada por desenvolvedores de código aberto, startups e empresas estabelecidas no mercado.

## Processos Principal e de Renderização
No Electron, o processo que executa o script main do package.json é chamado de processo principal. O script que roda no processo principal pode apresentar uma interface gráfica através da criação de páginas web. Um aplicativo Electron sempre tem um processo principal, mas nunca mais de um.

Como o Electron usa o Chromium para a apresentação de páginas web, a arquitetura de multiprocessos do Chromium também é utilizada. Cada página web no Electron é executada em seu próprio processo, que é chamado de processo de renderização.

Em navegadores normais, as páginas web geralmente rodam em um ambiente de área restrita e não têm a permissão de acessar recursos nativos. Usuários do Electron, por outro lado, têm o poder de usar as APIs do Node.js em páginas web, permitindo interações de baixo nível com o sistema operacional.

[Escrevendo Seu Primeiro Aplicativo com Electron
](https://electronjs.org/docs/tutorial/first-app)

## Electronjs com React

https://github.com/electron-react-boilerplate/electron-react-boilerplate <br>
https://getstream.io/blog/takeaways-on-building-a-react-based-app-with-electron/ <br>
https://medium.freecodecamp.org/building-an-electron-application-with-create-react-app-97945861647c <br>

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/electron/electron-quick-start
# Go into the repository
cd electron-quick-start
# Install dependencies
npm install
# Run the app
npm start
```

Note: If you're using Linux Bash for Windows, [see this guide](https://www.howtogeek.com/261575/how-to-run-graphical-linux-desktop-applications-from-windows-10s-bash-shell/) or use `node` from the command prompt.

## Resources for Learning Electron

- [electronjs.org/docs](https://electronjs.org/docs) - all of Electron's documentation
- [electronjs.org/community#boilerplates](https://electronjs.org/community#boilerplates) - sample starter apps created by the community
- [electron/electron-quick-start](https://github.com/electron/electron-quick-start) - a very basic starter Electron app
- [electron/simple-samples](https://github.com/electron/simple-samples) - small applications with ideas for taking them further
- [electron/electron-api-demos](https://github.com/electron/electron-api-demos) - an Electron app that teaches you how to use Electron
- [hokein/electron-sample-apps](https://github.com/hokein/electron-sample-apps) - small demo apps for the various Electron APIs

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
