# 🚀 Landing Page Responsiva com Formulário de Contato PHP/AJAX

Este projeto é um site de front-end no formato "one-page", com um back-end funcional em **PHP** para o processamento de formulário de contato. A aplicação foi desenvolvida para ser uma solução completa e profissional para sites institucionais, utilizando **jQuery** para interatividade e a biblioteca **PHPMailer** para um envio de e-mails seguro e robusto.

---

### **🎬 Demonstração**

![danki](https://github.com/YanzinhoCaue/PROJETO-SITE-DANKI-CODE/assets/127339610/891429fc-1515-45b8-97a7-c42361d873fe)

---

### **✨ Funcionalidades e Features Técnicas**

* **Formulário de Contato Funcional (Back-end em PHP)**:
    * O site possui um formulário de contato que envia os dados para um script **PHP** no servidor.
    * O envio de e-mails é feito de forma segura utilizando a biblioteca **PHPMailer**, configurada para autenticação via SMTP, o que garante uma alta taxa de entrega.

* **Submissão de Formulário com AJAX**:
    * A experiência do usuário é aprimorada com o uso de **AJAX** (via plugin jQuery Ajax Form) para enviar o formulário. Isso significa que o usuário recebe uma confirmação de envio **sem que a página precise ser recarregada**.

* **JavaScript Interativo com jQuery**:
    * **Scroll Suave**: A navegação entre as seções da página única é feita com uma animação de rolagem suave.
    * **Menu Responsivo**: Um script dedicado garante que o menu de navegação se adapte perfeitamente a dispositivos móveis.
    * **Slider de Equipe**: Uma seção da página contém um slider/carrossel para apresentar membros da equipe ou outros conteúdos.

---

### **🛠️ Tecnologias Utilizadas**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![PHPMailer](https://img.shields.io/badge/PHPMailer-D43A2A?style=for-the-badge&logo=php&logoColor=white)

---

### **▶️ Como Executar o Projeto**

Para testar todas as funcionalidades (incluindo o envio de e-mail), é necessário um ambiente de servidor local.

**Pré-requisitos:** Um ambiente como XAMPP, WAMP ou MAMP (que inclua Apache, MySQL e PHP).

**1️⃣ Clone o repositório**
Clone o projeto para dentro da pasta raiz do seu servidor local (ex: `htdocs` no XAMPP).
```bash
git clone [https://github.com/YanzinhoCaue/nome-do-repositorio.git](https://github.com/YanzinhoCaue/nome-do-repositorio.git)

2️⃣ Configure o PHPMailer
 * Se a pasta vendor não estiver presente dentro de classes/phpmailer, navegue até essa pasta via terminal e execute composer install.
 * Abra o arquivo classes/Mail.class.php.
 * Altere as credenciais de SMTP nas linhas indicadas (seu e-mail, senha e servidor SMTP da sua hospedagem).
3️⃣ Acesse a Aplicação
Abra seu navegador e acesse o projeto através do seu servidor local (ex: http://localhost/nome-do-repositorio).
💬 Contato
Yan Cauê
LinkedIn: linkedin.com/in/yancaue
GitHub: github.com/YanzinhoCaue

