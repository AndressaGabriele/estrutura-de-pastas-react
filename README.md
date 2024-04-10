# Organização de Projeto em React ⚛️

Aqui está um modelo de organização de arquivos em um projeto React:


## Dir Principais
```
📂 project_root
├──📁 public - Contém recursos estáticos públicos que são servidos pela aplicação.
├──📁 src - Pasta raiz do código-fonte da aplicação.
│   ├──📁 assets - Armazena recursos estáticos como imagens, arquivos de fonte, etc.
│   ├──📁 components - Reúne componentes reutilizáveis do React usados na interface.
│   ├──📁 config - Armazena arquivos de configuração, plugins, extensões, constantes globais (por exemplo, Reactotron).
│   ├──📁 hooks - Local para armazenar hooks personalizados.
│   ├──📁 pages - Contém componentes que representam páginas da aplicação.
│   │   ├──📁 Base - Componente principal que organiza a estrutura da aplicação.
│   │   │   ├──📄 index.tsx
│   │   │   └──📄 styles.ts
│   │   ├──📁 Error
│   │   │   ├──📄 index.tsx
│   │   │   └──📄 styles.ts
│   │   └──📁 Login
│   │       ├──📁 ForgotModal - Componente específico de Login
│   │       │   ├──📄 index.tsx
│   │       │   └──📄 styles.ts
│   │       ├──📄 index.tsx
│   │       └──📄 styles.ts
│   ├──📁 services - Fornece serviços externos (por exemplo, APIs).
│   │   └──📄 Api.ts
│   ├──📁 store - Pode conter configurações relacionadas ao estado global (por exemplo, Redux).
│   ├──📁 styles - Contém estilos globais e temas.
│   │   ├──📄 GlobalStyles.ts - Estilos globais da aplicação.
│   │   └──📁 themes - Temas de estilo, como light e dark.
│   │       ├──📄 Dark.ts
│   │       ├──📄 Light.ts
│   │       └──📄 index.ts - Centraliza as importações dos temas.
│   ├──📁 utils - Funções que serão reaproveitadas e utilizadas em várias partes dos códigos.
│   ├──📄 main.tsx - Ponto de entrada principal da aplicação.
│   ├──📄 routes.tsx - Configuração das rotas da aplicação.
│   └──📄 vite-env.d.ts
├──📄 .gitignore
├──📄 index.html
├──📄 package.json
├──📄 package-lock.json
├──📄 README.md
└──📄 vite.config.ts
```

##  🖌️ **Personalização e Flexibilidade**

Lembre-se de que esta estrutura de pastas é apenas um modelo sugerido. Você é livre para adaptá-la e personalizá-la conforme necessário para atender às especificidades do seu projeto. A organização eficiente de arquivos torna a manutenção mais fácil e a colaboração mais suave.
