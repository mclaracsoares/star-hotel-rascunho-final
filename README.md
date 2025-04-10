# Star Hotel

Um site moderno para o Star Hotel, localizado em Limoeiro-PE, desenvolvido com React e Tailwind CSS.

## 🚀 Funcionalidades

- Design responsivo e moderno
- Sistema de reservas integrado com Back4App
- Widget de clima em tempo real
- Painel administrativo para gerenciamento de reservas
- Páginas informativas sobre o hotel e seus serviços

## 🛠️ Tecnologias Utilizadas

- React
- Tailwind CSS
- Back4App (Backend as a Service)
- OpenWeather API
- React Router
- Vite
- ESLint
- Prettier

## 📋 Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/star-hotel.git
cd star-hotel
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
```

3. Configure as variáveis de ambiente:
- Crie um arquivo `.env` na raiz do projeto
- Adicione suas chaves de API:

VITE_BACK4APP_APP_ID=sua_app_id
VITE_BACK4APP_JS_KEY=sua_js_key
VITE_WEATHER_API_KEY=sua_chave_api


4. Inicie o servidor de desenvolvimento:
```bash
npm run dev
# ou
yarn dev
```


### Diretórios Principais

- **public/**: Contém arquivos estáticos que serão servidos diretamente, como o `index.html`.

- **src/**: Diretório principal do código-fonte do projeto.

  - **assets/**: Armazena recursos estáticos como imagens, fontes e outros arquivos.

  - **components/**: Contém componentes reutilizáveis do React utilizados em várias partes do projeto.

  - **config/**: Arquivos de configuração, incluindo a integração com Back4App.

  - **pages/**: Componentes que representam páginas inteiras do site.

  - **services/**: Módulos que lidam com chamadas a APIs e outras funcionalidades externas.

  - **styles/**: Arquivos de estilo globais e configurações do Tailwind CSS.

  - **utils/**: Funções utilitárias e helpers usados em todo o projeto.

### Arquivos Principais

- **.env.\***: Arquivos de ambiente para configurar variáveis sensíveis para diferentes ambientes (desenvolvimento, produção, etc.).

- **.eslintrc.cjs**: Configuração do ESLint para manter a qualidade e consistência do código.

- **.gitignore**: Especifica quais arquivos e diretórios devem ser ignorados pelo Git.

- **.prettierrc**: Configuração do Prettier para formatação automática do código.

- **CONTRIBUTING.md**: Guia para contribuidores, explicando como colaborar com o projeto.

- **LICENSE**: Licença MIT que define os termos sob os quais o projeto pode ser usado e distribuído.

- **README.md**: Este arquivo, fornecendo uma visão geral do projeto.

- **index.html**: Arquivo HTML principal que serve como ponto de entrada para o aplicativo React.

- **package-lock.json**: Arquivo gerado automaticamente que descreve as dependências exatas do projeto.

- **package.json**: Contém informações sobre o projeto e suas dependências.

- **postcss.config.js**: Configuração do PostCSS, utilizado em conjunto com o Tailwind CSS.

- **tailwind.config.js**: Configuração personalizada do Tailwind CSS.

- **vite.config.js**: Configuração do Vite, o bundler utilizado para o desenvolvimento do projeto.


## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✨ Contribuição

Contribuições são sempre bem-vindas! Por favor, leia as [diretrizes de contribuição](CONTRIBUTING.md) antes de enviar um pull request.

## 📞 Contato

Para mais informações, entre em contato através do e-mail: contato@starhotel.com.br
