# Teste QA Dasa

Inicie o teste clonando este repositorio:

```bash
git clone git@github.com:QADASA/qa_test_ui.git
```

Crie um repositorio no seu github e adicione as seguintes pessoas como reviewers:

- [@Francllin](https://github.com/Francllin)


## Setup do projeto

Se quiser enteder melhor o projeto pode dar uma olhada no [Vue.js](https://cli.vuejs.org/config/).

### Usando Docker

Você pode iniciar a aplicação usando o docker:

```bash
docker build -t test-qa . && docker run test-qa -p 8080
```

Se tudo ocorrer como esperado pode conferir nesta porta [http://localhost:8080/](http://localhost:8080/)

### Ou se prefir utilizando Node.js instalado

```bash
npm install
```

#### Compila e provém [http://localhost:8080/](http://localhost:8080/)

```bash
npm run serve
```

#### Para roda os testes e2e usando [cypress](https://www.cypress.io/)

```bash
npm run test:e2e
```

## Obrigado por realizar os teste

Caso sinta-se confortavel [avaliações são sempre bem-vindas este teste por aqui](https://forms.gle/qKEf7thRgnjvG2nXA)
