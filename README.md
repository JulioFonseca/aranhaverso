![Cover (2)](https://github.com/micheleambrosio/dio-spiderverse/assets/55519539/2247f062-26e9-4881-a9c8-0fcb17206daa)

# Projeto Spider-Verse

Este é o repositório do projeto Spider-Verse, desenvolvido durante uma live no Youtube em parceria com a [DIO](https://dio.me). O projeto consiste em uma aplicação interativa inspirada no universo do Homem-Aranha, usando as principais stacks front-end: React, Next.js 13, a biblioteca Framer Motion, Sass e TypeScript para criar um projeto visual incrível e de alta performance.

[Demonstração do projeto.webm](https://github.com/micheleambrosio/aranhaverso/assets/55519539/6ea3a467-ca98-4b3d-aa16-855db8a5fdb0)

## 💻 Tecnologias utilizadas no projeto

- [React.js](https://reactjs.org) (v18)
- [Next.js](https://nextjs.org) (v13)
- [TypeScript](https://www.typescriptlang.org) (v5)
- [ESLint](https://eslint.org)
- [Framer Motion](https://www.framer.com/api/motion)
- [SASS](https://sass-lang.com)

## 📚 Materiais

- [Assets](https://drive.google.com/drive/folders/150O6eEhs8oGaHMMss7_CYG2jnI7yMugO?usp=sharing) (arquivos de imagens e efeitos sonoros)

## 🌿 Branches

- `main` projeto finalizado com todas as features implementadas durante a live;
- `template` estrutura inicial para que você possa iniciar o projeto, contendo todos os assets, bibliotecas, estrutura de pastas e configurações de ESLint;
- `live` parte do projeto já iniciado para o code-review em live, pronto para implementar as interações e animações do usuário com o projeto.

## 🎨 Protótipo do projeto

[Clique aqui](https://www.figma.com/file/tdCIzlGKVdZJmKSaV99iDU/Landpage---SpiderVerse?type=design&node-id=0%3A1&t=rZMG8Ic2KXC3Dwfn-1) para ir ao protótipo do projeto no Figma.

## 🗄️ Estrutura de pastas

O projeto está estruturado da seguinte forma:

- 📁 `public`
  - 📁 `icons`
  - 📁 `songs`
  - 📁 `spiders`
- 📁 `src`
  - 📁 `app`
    - 📁 `api`
      - 📁 `heroes`
    - 📁 `hero`
      - 📁 `[id]`
  - 📁 `components`
    - 📁 `Carousel`
    - 📁 `HeroDetails`
    - 📁 `HeroesList`
    - 📁 `HeroPicture`
  - 📁 `fonts`
  - 📁 `interfaces`


## 🛠️ Instruções de execução

Siga as instruções abaixo para rodar o projeto em seu ambiente local:

1. Certifique-se de ter o Node.js instalado em seu computador. Você pode baixar a versão mais recente do Node.js em https://nodejs.org.

2. Clone este repositório em seu computador ou faça o download do código fonte.

3. Abra o terminal e navegue até o diretório raiz do projeto.

4. Instale as dependências do projeto executando o seguinte comando:

```bash
  npm install
```

5. Após a conclusão da instalação das dependências, inicie o servidor de desenvolvimento local com o comando:

```bash
  npm run dev
```

6. O servidor local será iniciado e você poderá acessar o projeto no seu navegador através do seguinte endereço:

```bash
  http://localhost:3000
```

Caso a porta 3000 estiver em uso, automaticamente o Next.js irá subir na próxima porta livre da máquina.

Se deseja alterar a porta padrão na qual a aplicação tentará subir, você pode modificar a porta no arquivo `next.config.js`.

Agora você está pronto para explorar o projeto em seu ambiente local!

---
