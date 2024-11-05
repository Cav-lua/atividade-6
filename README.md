# **App de Compras Simples**

> Um aplicativo Android simples para selecionar produtos e calcular o valor total da compra.

## 📱 Descrição

O **App de Compras Simples** permite ao usuário selecionar produtos de uma lista e calcular o valor total dos itens selecionados. 
A interface é minimalista, com checkboxes para cada produto e um botão para realizar o cálculo do total.

## 🔧 Funcionalidades

- [x] Seleção de produtos com preços específicos utilizando checkboxes
- [x] Cálculo automático do valor total dos produtos selecionados
- [x] Exibição do valor total da compra em um `TextView` após o cálculo

## 🎨 Design e Prototipagem

A interface foi criada com ConstraintLayout para uma organização responsiva e centralizada. O layout utiliza um fundo branco com textos em preto para garantir uma visualização clara dos produtos e valores.
Cada item possui um checkbox para seleção, e um botão de cálculo é utilizado para exibir o total.

## 🖥️ Telas do Aplicativo

### Tela Principal

A tela principal exibe o título "APP De Compras" e uma lista de produtos com checkboxes ao lado. 
O usuário pode selecionar os produtos desejados, e ao clicar no botão "Calcular", o valor total dos itens selecionados é exibido.

![Captura de tela 2024-11-05 013448](https://github.com/user-attachments/assets/ad77d393-7150-4929-b1fc-faaaf8505f62)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Koala | 2024.1.2)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para estrutura da interface
- [x] **CheckBox** para permitir a seleção de produtos
- [x] **Button** para acionar o cálculo do valor total
- [x] **TextView** para exibir o resultado final

## 👨‍💻 Desenvolvedores

Cav-lua - Desenvolvedor - [GitHub](https://github.com/Cav-lua)

## 📄 Licença

Este projeto está licenciado sob os termos da licença MIT.

## 🛠️ Como Rodar o Projeto

Para executar este projeto em seu ambiente de desenvolvimento local, siga os passos abaixo:

1. Clone o repositório:

    ```bash
    git clone https://github.com/Cav-lua/app-compras-simples.git
    ```

2. Abra o projeto no Android Studio.
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

```bash
├── app
│   ├── src
│   │   ├── main
│   │   │   ├── java/com/example/myapplication
│   │   │   │   ├── MainActivity.java       # Classe para a Tela Principal
│   │   │   │   
│   │   │   └── res
│   │   │       ├── layout
│   │   │       │   ├── activity_main.xml   # Layout da Tela Principal
│   │   │       │   
│   │   │       ├── values
│   │   │           ├── strings.xml         # Strings usadas no app
│   │   │           ├── colors.xml          # Cores definidas no projeto
│   └── build.gradle                        # Configuração do Gradle
└── README.md                               # Este arquivo
