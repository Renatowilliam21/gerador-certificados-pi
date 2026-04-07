# 🎓 Emissor de Certificados - IFCE Boa Viagem

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
![JS](https://img.shields.io/badge/Vanilla-JS-yellow.svg)

Sistema web leve e intuitivo para a geração de certificados individuais, desenvolvido para apoiar a disciplina de **Projeto Integrador** do **Instituto Federal do Ceará (IFCE) – Campus Boa Viagem**.

## 🎯 Objetivo

Facilitar a vida do docente na emissão de documentos comprobatórios, permitindo que professores gerem certificados personalizados de forma rápida, automática e padronizada para alunos participantes de projetos acadêmicos e técnicos.

---

## ✨ Funcionalidades

### 📝 Cadastro de Dados do Projeto
* **Nome do Sistema:** Título do software desenvolvido.
* **Orientador(a):** Nome do professor responsável.
* **Cliente Externo:** Empresa ou entidade beneficiada pelo projeto.
* **Semestre:** Identificação do período letivo (ex: 2025.2).

### 👥 Gestão de Discentes
* **Cadastro Dinâmico:** Adição ilimitada de alunos com nome e matrícula.
* **Geração Automática:** Criação de certificados individuais com preenchimento de campos dinâmicos.

### 🖨️ Impressão e Layout
* **Formato A4 Horizontal:** Layout otimizado para certificados profissionais.
* **Impressão Direta:** Integração com o comando de impressão do navegador (`Window.print()`).
* **Exportação:** Opção nativa para "Salvar como PDF".

---

## 🖥️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web puras (Vanilla), garantindo que funcione em qualquer computador sem necessidade de servidores complexos:

* **HTML5:** Estruturação semântica.
* **CSS3:** Estilização e suporte a `@media print` para layout de impressão.
* **JavaScript (Vanilla JS):** Lógica de manipulação do DOM e geração dinâmica dos certificados.

---

## 📂 Estrutura do Projeto

```text
certificados-ifce/
│
├── index.html       # Estrutura e Lógica (Single Page Application)
└── imagelogo.png    # Logotipo oficial do IFCE ou do Campus
