# 📝 Formulário de Inscrição — Curso EAD

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Formulário web de inscrição para cursos EAD do ITB, com envio automático via WhatsApp e geração de PDF.**

[Ver Demo](#-como-usar) · [Reportar Bug](https://github.com/jovemegidio/form-ead/issues)

</div>

---

## 📸 Sobre o Projeto

Sistema de ficha de inscrição digital para cursos de Educação a Distância (EAD). O formulário coleta dados pessoais, endereço e escolaridade do candidato, enviando automaticamente as informações via WhatsApp e gerando um PDF para download.

> Desenvolvido como solução prática para digitalizar o processo de matrícula, eliminando formulários em papel.

---

## ✨ Funcionalidades

| Recurso | Descrição |
|---------|-----------|
| 📋 **Formulário completo** | Dados pessoais, endereço e escolaridade |
| ✅ **Validação de CPF** | Algoritmo completo de verificação dos dígitos |
| 📱 **Envio via WhatsApp** | Dados formatados enviados direto pelo WhatsApp Web |
| 📄 **Geração de PDF** | Download automático da ficha em PDF com jsPDF |
| 🔒 **Validação de campos** | Campos obrigatórios com padrões (RG, CPF, CEP, telefone) |
| 💬 **Botão flutuante** | Atalho para WhatsApp fixo no canto da tela |
| 🖥️ **Header fixo** | Barra superior com logos que acompanha o scroll |
| 📱 **Layout responsivo** | Formulário adaptável com Flexbox |

---

## 📋 Campos do Formulário

### Dados Pessoais
- Nome Completo
- Data de Nascimento
- Estado Civil (Solteiro, Casado, Divorciado, Viúvo, União Estável)
- Gênero (Masculino, Feminino)
- Nacionalidade / Naturalidade
- RG, Órgão Emissor e UF
- CPF (com validação)

### Endereço
- Endereço Completo, Bairro, Cidade, UF, CEP
- Telefone, WhatsApp, E-mail

### Escolaridade
- Ensino Fundamental (Incompleto/Completo)
- Ensino Médio (Incompleto/Completo)
- Superior (Incompleto/Completo)
- Pós-Graduação

---

## 🛠️ Tecnologias

- **HTML5** — Estrutura semântica do formulário
- **CSS3** — Layout responsivo com Flexbox, estilização e efeitos visuais
- **JavaScript (ES6)** — Validação de CPF, envio via WhatsApp API e geração de PDF
- **[jsPDF](https://github.com/parallax/jsPDF)** — Biblioteca para geração de documentos PDF no navegador

---

## 📁 Estrutura do Projeto

```
form-ead/
├── form-ead.html        # Página principal (HTML + CSS + JS embutidos)
├── Icone.png            # Ícone do botão flutuante do WhatsApp
├── favicon.png          # Favicon do site
├── logo-central.png     # Logo central do header
├── logo-panel.jpg       # Logo esquerda do header
├── logo-secundaria.png  # Logo direita do header
└── README.md            # Documentação
```

---

## 🚀 Como Usar

### Opção 1 — Abrir diretamente

1. Clone o repositório:
   ```bash
   git clone https://github.com/jovemegidio/form-ead.git
   ```
2. Abra o arquivo `form-ead.html` no navegador.

### Opção 2 — Com Live Server (VS Code)

1. Instale a extensão **Live Server** no VS Code.
2. Clique com o botão direito em `form-ead.html` → **Open with Live Server**.

---

## ⚙️ Como Funciona

1. O usuário preenche todos os campos do formulário.
2. Ao clicar em **Enviar**, o sistema:
   - **Valida o CPF** com algoritmo de dígitos verificadores.
   - **Formata os dados** em uma mensagem organizada.
   - **Abre o WhatsApp Web** com a mensagem pronta para envio.
   - **Gera e baixa um PDF** com todos os dados preenchidos.

---

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar.

---

<div align="center">

Feito com ❤️ por [jovemegidio](https://github.com/jovemegidio)

</div>
