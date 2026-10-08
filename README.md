# 🎯 Targets — Gestão de Metas Financeiras

Aplicativo mobile de **gestão de metas financeiras**, desenvolvido como parte da formação em **React Native da Rocketseat**.

Com o Targets, é possível organizar objetivos financeiros, acompanhar quanto já foi guardado e registrar entradas e saídas de valores, com persistência local dos dados.

## 📱 Telas do aplicativo

<p align="center">
  <img src="screenshots/inicio.png" alt="Tela inicial com resumo financeiro e lista de metas" width="260" />
  <img src="screenshots/nova-meta.png" alt="Tela de cadastro de uma nova meta" width="260" />
  <img src="screenshots/transacoes.png" alt="Detalhes da meta com histórico de transações" width="260" />
</p>

## ✨ Funcionalidades

- Criação e edição de metas financeiras
- Listagem de metas e acompanhamento do progresso de cada objetivo
- Registro de transações de entrada e saída vinculadas às metas
- Histórico de transações com valor, data e observação
- Resumo financeiro de entradas, saídas e saldo
- Armazenamento local com SQLite
- Validação dos dados informados nos formulários

## 🛠️ Tecnologias

- **React Native** — desenvolvimento da interface mobile
- **Expo** — ferramentas e ambiente de desenvolvimento
- **TypeScript** — tipagem estática
- **Expo Router** — navegação entre telas
- **expo-sqlite** — banco de dados local
- **React Hooks** — gerenciamento de estado e efeitos

## 📚 Aprendizados

Este projeto permitiu praticar:

- Estruturação de um aplicativo React Native com componentes reutilizáveis
- Navegação e passagem de parâmetros com Expo Router
- Criação e acesso a tabelas SQLite
- Operações assíncronas e consultas ao banco de dados
- Desenvolvimento de hooks para acesso aos dados
- Formatação de valores monetários e validação de formulários
- Construção de uma interface para acompanhamento de metas

## 🚀 Como executar

**Pré-requisitos:** Node.js, npm e ambiente Expo configurados. Para executar a versão nativa no emulador Android, também é necessário configurar o Android Studio e o SDK Android.

```bash
# Instalar as dependências
npm install

# Iniciar o Expo
npx expo start
```

Para executar no Android (com emulador ou dispositivo configurado):

```bash
npx expo run:android
```

## 👨‍💻 Sobre o projeto

Desenvolvido durante minha jornada de aprofundamento em desenvolvimento mobile. Após mais de **16 anos de experiência em desenvolvimento de sistemas**, sigo ampliando meus conhecimentos com **React Native, Expo e TypeScript**.

> A experiência que construí até aqui não é o fim da jornada. É a base para o próximo nível.

**Desenvolvido por [NandoAmadoDev](https://github.com/NandoAmadoDev) como projeto de aprendizado na formação da Rocketseat.**
