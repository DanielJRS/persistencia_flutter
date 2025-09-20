# Projeto de Persistência com Flutter

Este projeto foi desenvolvido como parte dos estudos em **Análise e Desenvolvimento de Sistemas** e tem como objetivo praticar o uso do **Flutter** com persistência de dados.
A ideia principal é criar um aplicativo simples que mostra na prática como salvar, recuperar e manipular informações, utilizando os recursos que o Flutter oferece.


## Tecnologias utilizadas

- **Dart** → linguagem de programação usada pelo Flutter.  
- **Flutter** → framework para desenvolvimento de aplicativos multiplataforma (Android, iOS, Web, Desktop).  
- **Persistência de Dados** → conceitos aplicados para guardar informações localmente.  

Além disso, o projeto também contém **diagramas UML** para representar a estrutura do código.

## Estrutura do Projeto

```
persistencia_flutter/
│── android/         → Arquivos para rodar no Android
│── ios/             → Arquivos para rodar no iOS
│── lib/             → Código principal do app (Dart)
│   │── main.dart           → Ponto de entrada do aplicativo
│   │── models/             → Modelos de dados usados na persistência
│   │── repositories/       → Classes responsáveis por salvar, carregar e manipular dados
│   │── screens/            → Telas da aplicação (UI)
│   │── widgets/            → Componentes reutilizáveis da interface
│   │── utils/              → Funções auxiliares e constantes
│── linux/           → Arquivos para Linux
│── macos/           → Arquivos para MacOS
│── web/             → Arquivos para Web
│── test/            → Testes automatizados
│── pubspec.yaml     → Configurações e dependências do Flutter
│── uml.svg          → Diagrama UML
│── uml2.svg         → Diagrama UML
```

---

## Como rodar o projeto

Para executar este projeto na sua máquina, siga os passos abaixo:

1. Instale o [Flutter](https://docs.flutter.dev/get-started/install) e configure o ambiente.  
2. Faça o clone ou download deste repositório.  
3. Abra a pasta `persistencia_flutter` no seu editor (ex.: VS Code ou Android Studio).  
4. No terminal, rode o comando:

```bash
flutter pub get
```

Isso vai baixar as dependências do projeto.  

5. Em seguida, execute o app com:

```bash
flutter run
```

Você pode escolher rodar em **Android**, **iOS** (se tiver Mac), **Web** ou **Desktop**.

---

## O que você vai encontrar neste projeto

- Exemplos de **persistência de dados**.  
- Estrutura de pastas organizada.  
- **Diagramas UML** mostrando como as classes e funções se relacionam.  
- Código comentado e simples de entender.

---

## Observação

Este projeto foi refatorado com a intenção e objetivo de adotar as melhores práticas de desenvolvimento atuais.

