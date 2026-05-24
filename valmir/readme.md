# 📇 LinkEDESP - Cartão de Visitas Digital Interativo

O **LinkEDESP** é uma solução de networking digital desenvolvida para facilitar o compartilhamento de contatos institucionais. Através de um QR Code personalizado, o usuário acessa uma página interativa (Mobile-First) onde pode salvar os dados diretamente na agenda do celular via arquivo vCard (.vcf).

---

## 🚀 Funcionalidades

* **vCard Automático:** Gera um arquivo de contato compatível com Android e iOS, incluindo Nome, Sobrenome, Cargo, Empresa, WhatsApp, Telefone Fixo, E-mail e Site.
* **QR Code Dinâmico:** Gera automaticamente um código QR baseado na URL atual da página.
* **Identidade Visual:** QR Code personalizado com o logo da **EDESP** (Escola de Desenvolvimento Social do Estado de São Paulo).
* **Design Responsivo:** Otimizado para visualização em smartphones.
* **Suporte UTF-8:** Tratamento de caracteres especiais e acentos para garantir a integridade dos dados.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação do conteúdo.
* **CSS3:** Estilização moderna e layout mobile-first.
* **JavaScript (Vanilla):** Lógica de geração de vCard e manipulação de DOM.
* **QRCode.js:** Biblioteca para geração do código QR.
* **Font Awesome:** Ícones interativos.

---

## 📂 Estrutura de Arquivos

```text
/
├── index.html          # Cartão de visitas principal (Valmir)
├── assets/             # Pasta de recursos visuais
│   ├── valmir.png      # Foto de perfil
│   └── logo_edesp.png  # Logo institucional para o QR Code
└── README.md           # Documentação do projeto

