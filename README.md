<div align="center">

#  Ficha de Inscrição  Curso EAD

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jsPDF](https://img.shields.io/badge/jsPDF-2.5-EC5990?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=githubpages&logoColor=white)

**Formulário de inscrição profissional para cursos de Educação a Distância com envio automático via WhatsApp e geração de comprovante PDF.**

[Ver Demonstração](https://jovemegidio.github.io/form-ead)  [Reportar Bug](https://github.com/jovemegidio/form-ead/issues)

</div>

---

##  Funcionalidades

| Funcionalidade | Descrição |
|---|---|
|  **Design Profissional** | Interface moderna com fonte Inter, cards com sombra e gradientes institucionais |
|  **Barra de Progresso** | Indicador visual de 3 etapas que acompanha o scroll do formulário |
|  **Máscaras de Input** | Formatação automática para CPF, CEP, Telefone e WhatsApp |
|  **Validação de CPF** | Verificação em tempo real com feedback visual (toast) ao sair do campo |
|  **Envio via WhatsApp** | Dados formatados enviados automaticamente para o número institucional |
|  **Comprovante PDF** | PDF estilizado com cabeçalho verde, campos em negrito e rodapé com data |
|  **WhatsApp FAB** | Botão flutuante com tooltip para contato rápido |
|  **100% Responsivo** | Layout adaptável para desktop, tablet e celular |
|  **Animações Suaves** | Transições CSS e efeito fade-up nas seções do formulário |
|  **Toast Notifications** | Alertas visuais elegantes para sucesso e erros |

---

##  Stack Tecnológica

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica e acessível |
| **CSS3** | CSS Variables, Grid, Flexbox, Backdrop-filter, Animations |
| **JavaScript** | Máscaras, validação, IntersectionObserver, PDF |
| **jsPDF 2.5** | Geração de comprovante PDF no navegador |
| **Google Fonts** | Tipografia Inter (300800) |

---

##  Design

- **Paleta:** Verde institucional `#00703c` com variações light/dark
- **Tipografia:** Inter  peso 300 a 800
- **Layout:** Seções em cards com `border-radius: 12px`
- **Hero:** Gradiente 135° com padrão SVG sutil
- **Formulário:** Grid responsivo `minmax(220px, 1fr)`
- **Botão:** Gradiente + sombra com efeito hover elevado

---

##  Estrutura

```
form-ead/
 index.html            # Página principal (formulário completo)
 favicon.png           # Ícone da aba
 Icone.png             # Ícone do botão WhatsApp
 logo-panel.jpg        # Logo esquerda (header)
 logo-central.png      # Logo central (header)
 logo-secundaria.png   # Logo direita (header)
 README.md             # Documentação
```

---

##  Campos do Formulário

### 1 Dados Pessoais
Nome Completo  Data de Nascimento  Estado Civil  Gênero  Nacionalidade  Naturalidade  RG  Órgão Emissor  UF (RG)  CPF

### 2 Endereço
Endereço Completo  Bairro  Cidade  UF  CEP  Telefone  WhatsApp  Email

### 3 Escolaridade
Nível de escolaridade (Fundamental a Pós-Graduação)

---

##  Fluxo de Funcionamento

```
Usuário preenche formulário
         
         
  Validação de CPF  Toast de erro + foco no campo
         
         
         
  Loading spinner (800ms)
         
         
  
                
WhatsApp      PDF gerado
(nova aba)    (download)
                
  
         
  Toast de sucesso 
```

---

##  Autor

<div align="center">

Desenvolvido por **@jovemegidio**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jovemegidio)

</div>
