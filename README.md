# 🏥 ClinAgenda - Backend

Este projeto foi desenvolvido para o **BootCamp Curso Intensivo de Desenvolvimento Web FullStack com ASP.NET Core & Vue🚀**, uma parceria entre o **PECEGE** e o **DEVPIRA**.

Com aulas ministradas por Decio Stenico e Maira Scomparim, a proposta do projeto é construir uma aplicação completa para uso em uma clínica médica, com funcionalidades voltadas à gestão de profissionais, pacientes e agendamentos.

Este repositório contém **o frontend da aplicação**, desenvolvido em **Vue 3**

---

## 🛠️ Tecnologias Utilizadas

- **Vue 3**
- **Vuetify**
- **Pinia**
- **TypeScript**

---

## 🚀 Como Executar o Projeto

Se esta for sua primeira vez, execute o seguinte comando:

```bash
yarn
```

Depois disso, sempre que quiser rodar o projeto com recarregamento automático, use:

```bash
yarn dev
```

O servidor estará disponível em http://localhost:3000

# Rodando com mock de backend

> ⚠️ Algumas funcionalidades podem não estar 100% cobertas pelo mock

No arquivo `.env.development` sete a variável _VITE_USE_MOCK=true_ ou rode o seguinte comando:

```bash
yarn dev:mock
```

Ao abrir o sistema, deverá ter um alerta no topo da tela indicando que o mock está ativo.

# Gerando o build para produção

Para gerar uma versão do projeto pronta para produção, utilize:

```
yarn build
```
