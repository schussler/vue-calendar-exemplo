# Projeto Vue.js com Calendário

Este projeto utiliza Vue.js para implementar um calendário com suporte a ícones MDI e estilização com Bulma.

## Dependências Necessárias

Para começar, instale as seguintes dependências:

### Fontes MDI

```bash
npm install @mdi/font
```

### Biblioteca de Calendário

```bash
npm install vue-cal
```

### Pacote Bulma (Opcional)

Se desejar usar Bulma para estilização, instale o pacote:

```bash
npm install bulma
```

## Configuração do Projeto

No arquivo `main.js`, importe as dependências necessárias:

### Importar Ícones MDI

```javascript
import "@mdi/font/css/materialdesignicons.css";
```

### Importar Bulma (Opcional)

Se estiver usando Bulma, importe o CSS:

```javascript
import "bulma/css/bulma.css";
```

## Uso do Componente de Calendário

Basta copiar o arquivo do componente de calendário `.vue` e colocá-lo no seu projeto. Certifique-se de ajustar os caminhos e dependências conforme necessário no seu ambiente.

## Exemplo de Configuração Completa

### Estrutura de Arquivos

```plaintext
.
├── src
│   ├── components
│   │   └── CalendarComponent.vue
│   └── main.js
├── package.json
└── README.md
```

### Conteúdo do `main.js`

```javascript
import Vue from "vue";
import App from "./App.vue";

import "@mdi/font/css/materialdesignicons.css"; // Importar os ícones MDI
import "bulma/css/bulma.css"; // Importar Bulma, se desejar

new Vue({
  render: (h) => h(App),
}).$mount("#app");
```

### Exemplo de Uso no Componente

No seu componente `CalendarComponent.vue`, você pode usar a biblioteca de calendário conforme a documentação do `vue-cal`.

## Conclusão

Com estas configurações, seu projeto Vue.js estará pronto para utilizar um calendário estilizado com ícones MDI e, opcionalmente, com Bulma. Sinta-se à vontade para personalizar conforme necessário.

Para mais informações sobre cada biblioteca, consulte a documentação oficial:

- [MDI Icons](https://materialdesignicons.com/)
- [Vue Cal](https://antoniandre.github.io/vue-cal/)
- [Bulma](https://bulma.io/)
