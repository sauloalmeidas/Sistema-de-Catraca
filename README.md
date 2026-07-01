# 🔐 Sistema de Catraca com QR Code

Sistema simples de controle de acesso usando QR Code no navegador.  
O projeto simula uma catraca digital onde usuários são cadastrados, recebem um código QR e podem ser validados na entrada.

---

## 🚀 Funcionalidades

- Cadastro de usuários (nome e idade)
- Geração automática de ID único
- Criação de QR Code para cada usuário
- Leitura de QR Code via câmera (web)
- Validação de acesso em tempo real
- Armazenamento local usando `localStorage`
- Listagem de usuários em tabela
- Remoção de usuários

---

## 🧠 Como funciona

1. O usuário é cadastrado no sistema
2. Um ID único é gerado automaticamente
3. Esse ID é convertido em um QR Code
4. Na tela de entrada, o QR Code é escaneado
5. O sistema verifica o ID no `localStorage`
6. Se existir, o acesso é liberado e o nome é exibido

---

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- [html5-qrcode](https://github.com/mebjas/html5-qrcode)
- [qrcodejs](https://github.com/davidshimjs/qrcodejs)

---

## 📁 Estrutura do projeto
/projeto-catraca
│
├── index.html # Cadastro e geração de QR Code
├── entrada.html # Scanner de QR Code (catraca)

---

## 💾 Armazenamento

O sistema utiliza `localStorage` do navegador para armazenar os dados:

```js
{
  nome: "João",
  Idade: 20,
  ID: "A1B2C3D4E5"
}

## ⚠️ Observações

- Este projeto é uma simulação e não utiliza banco de dados real
- Funciona apenas no navegador (front-end puro)
- Pode ser expandido futuramente para uma API real
- Os dados são armazenados localmente usando `localStorage`

## 📌 Melhorias futuras

- Armazenamento de QR Codes em memória
- Análise de status do usuário em vez de apenas ID
- Interface estilo painel de controle

👨‍💻 Projeto

Projeto desenvolvido para estudo de JavaScript, QR Code e lógica de sistemas de acesso.