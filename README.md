<div align="center">
  <h1>🌍 AfroEduca</h1>
  <h3>Conectando saberes, celebrando a diversidade.</h3>

  <p>
    Uma plataforma educacional interativa voltada para a <strong>Educação Étnico-Racial</strong>,<br>
    valorizando a história e cultura Africana, Afro-Brasileira e Indígena.
  </p>

  <p>
    <a href="#-sobre">Sobre</a> •
    <a href="#-funcionalidades">Funcionalidades</a> •
    <a href="#-tecnologias">Tecnologias</a> •
    <a href="#-como-acessar">Como Acessar</a> •
    <a href="#-autor">Autor</a>
  </p>

  ![Badge em Desenvolvimento](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
  ![Badge License](https://img.shields.io/badge/License-MIT-green)
</div>

---

## 📜 Sobre o Projeto

O **AfroEduca** é uma solução digital desenvolvida para apoiar a aplicação das Leis **10.639/03** e **11.645/08** na educação básica. O objetivo é fornecer aos professores ferramentas práticas para o ensino da história e cultura afro-brasileira e indígena, e aos alunos uma experiência de aprendizado imersiva e gamificada.

A plataforma foca na **Bahia** como ponto de partida para explorar territórios ancestrais, quilombos e aldeias, conectando geografia, história e tecnologia.

---

## ✨ Funcionalidades

### 🎓 Para Estudantes (Visão do Aluno)
* **Mapa Interativo:** Exploração visual de territórios indígenas e quilombolas na Bahia.
* **Ambiente de Aprendizagem (LMS):** Cursos estruturados com:
    * 🎬 Vídeo-aulas com capas personalizadas.
    * 📖 Textos de apoio e leitura histórica.
    * 📂 Materiais complementares (PDFs, Links externos).
    * ✅ Quizzes interativos com feedback imediato.
* **Comentários:** Área para tirar dúvidas e interagir (simulado).

### 🍎 Para Educadores (Visão do Professor)
* **Painel Administrativo:** Dashboard para gerenciar cursos criados.
* **Criador de Cursos Visual:** Ferramenta para clicar no mapa e definir coordenadas geográficas (Lat/Long simuladas) para novos territórios.
* **Editor de Conteúdo:** Formulário completo para adicionar vídeos, textos e materiais didáticos.

### ⚙️ Gerais
* **Autenticação Simulada:** Sistema de Login e Cadastro funcional via `localStorage`.
* **Acessibilidade:** Botão de **Modo Noturno (Dark Mode)** persistente.
* **Responsividade:** Layout adaptável para Desktop e Mobile.

---


## 🚀 Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias web padrão, focado em performance e sem dependência de frameworks pesados para esta versão de protótipo.

* **HTML5** (Semântico)
* **CSS3** (Flexbox, Grid, Animações, Variáveis CSS)
* **JavaScript** (ES6+, DOM Manipulation, LocalStorage)
* **FontAwesome** (Ícones)
* **Google Fonts** (Tipografia: Poppins & Lato)

---

## 💻 Como Executar o Projeto

Como o projeto é estático (Front-end puro), não é necessária instalação de dependências ou servidores backend.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/afroeduca.git](https://github.com/seu-usuario/afroeduca.git)
    ```
2.  **Acesse a pasta:**
    ```bash
    cd afroeduca
    ```
3.  **Abra o projeto:**
    * Basta abrir o arquivo `index.html` no seu navegador preferido.
    * Ou use uma extensão como *Live Server* no VS Code para uma melhor experiência.

---

## 🔐 Contas de Teste

Para testar as diferentes visões da plataforma sem precisar criar contas novas, utilize as credenciais padrão pré-configuradas:

| Perfil | Email | Senha | Funcionalidade Principal |
| :--- | :--- | :--- | :--- |
| **Professor** | `prof@teste.com` | `123` | Acesso ao Painel de Criação e Edição |
| **Aluno** | `aluno@teste.com` | `123` | Acesso aos Cursos e Quiz |

> **Nota:** Todos os dados criados (novos usuários, cursos ou comentários) são salvos no **LocalStorage** do seu navegador. Se você limpar o cache, os dados retornarão ao padrão inicial.

---

## 🚧 Próximos Passos (Roadmap)

* [ ] Integração com Backend Real (Firebase ou Node.js).
* [ ] Upload real de arquivos (PDFs e Imagens).
* [ ] Expansão do mapa para outros estados do Brasil.
* [ ] Implementação de Libras e leitor de tela aprimorado.

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você tem alguma ideia para melhorar a educação étnico-racial através da tecnologia:

1.  Faça um **Fork** do projeto.
2.  Crie uma Branch para sua Feature (`git checkout -b feature/IncrívelFeature`).
3.  Faça o Commit (`git commit -m 'Add some IncrívelFeature'`).
4.  Faça o Push (`git push origin feature/IncrívelFeature`).
5.  Abra um **Pull Request**.

---

<div align="center">
  Feito por <strong>CauãLSM</strong> durante o desenvolvimento do projeto AfroEduca.
</div>
