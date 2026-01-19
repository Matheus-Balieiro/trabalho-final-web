## 📄 Documentação do Projeto

### 🎯 Objetivo
O **IdeaBytes** é uma plataforma colaborativa que permite aos usuários **trocar conhecimentos e habilidades sem o uso de dinheiro**. Inspirado no conceito de *skill-sharing*, o sistema conecta pessoas com base nas competências que oferecem e desejam aprender, promovendo uma rede de aprendizado mútuo.

---

### 🧩 Funcionalidades

#### Para Usuários:
- ✅ **Cadastro e login** (simulado com `localStorage`)
- ✅ **Edição de perfil**: nome, contato, foto (via Cloudinary)
- ✅ **Registro de habilidades** oferecidas e desejadas
- ✅ **Solicitação de matches** com outros usuários
- ✅ **Aceitar ou recusar** solicitações recebidas
- ️ **Visualização de contatos** após aceite de match

#### Para Administradores:
- 🔐 **Login administrativo** (`admin` / `admin`)
- 👥 **Listagem de todos os usuários**
- 🗑️ **Exclusão de usuários** (com confirmação)

---

### 🛠️ Tecnologias Utilizadas

| Camada | Tecnologia |
|-------|-----------|
| **Frontend** | HTML5, CSS3 (tema dark azul), JavaScript (ES6+) |
| **Backend** | Node.js, Express, PostgreSQL |
| **Banco de Dados** | Neon (PostgreSQL na nuvem) |
| **Armazenamento de Imagens** | Cloudinary |
| **Deploy** | Vercel (frontend e backend) |
| **Autenticação** | Simulada com `localStorage` (MVP) |

---

### 📁 Estrutura de Pastas

```
trabalho-final-web/
├── admin/
│   ├── login.html      # Login do administrador
│   └── index.html      # Painel de gerenciamento
├── css/
│   └── style.css       # Estilos globais + responsivo
├── images/
│   └── default-avatar.png
├── index.html          # Página inicial (lista de usuários)
├── login.html          # Login/cadastro de usuários
├── perfil.html         # Perfil público de um usuário
├── meu-perfil.html     # Edição do próprio perfil
└── matches.html        # Gerenciamento de matches
```

---

### 🚀 Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/trabalho-final-web.git
   cd trabalho-final-web
   ```

2. **Backend (em outro repositório):**
   - Certifique-se de que o backend esteja rodando (ou use a versão no Vercel)
   - Atualize a variável `API_URL` nos arquivos HTML se necessário

3. **Abra no navegador:**
   - Basta abrir `index.html` diretamente ou usar um servidor local:
     ```bash
     npx serve
     ```

> ⚠️ **Observação**: O projeto foi projetado para funcionar **diretamente no Vercel**, mas também roda localmente com limitações.

---

### 🔐 Credenciais de Acesso

| Tipo | Usuário | Senha |
|------|--------|-------|
| **Administrador** | `admin` | `admin` |
| **Usuário comum** | Qualquer e-mail | Qualquer senha (cadastro livre) |

> 💡 Em produção, o login seria feito com autenticação real e senhas criptografadas.

---

### 📸 Telas Principais

| Tela | Descrição |
|------|---------|
| **Página Inicial** | Lista de usuários com habilidades e foto |
| **Meu Perfil** | Edição de dados e gerenciamento de habilidades |
| **Matches** | Visualização de solicitações enviadas/recebidas |
| **Painel Admin** | Listagem e exclusão de usuários |

*(Inclua prints no README final se desejar)*

---

### 📝 Considerações Finais

Este projeto foi desenvolvido como **MVP (Minimum Viable Product)** para a disciplina de **Desenvolvimento Web**. Apesar de utilizar autenticação simulada e lógica simplificada, ele demonstra:

- Integração frontend/backend
- Boas práticas de UX/UI
- Responsividade
- Gerenciamento de estado com `localStorage`
- Deploy em nuvem

Futuras melhorias incluiriam:
- Autenticação JWT
- Notificações em tempo real
- Validação de formulários avançada
- Testes automatizados

---

### 👥 Integrantes

- Hebert Barbosa Ferreira – [GitHub](https://github.com/hbf109)
- Jamylli Gabrielle Pereira Soares – [GitHub](https://github.com/Jamylli25)
- Lunan Paulino Oliveira – [GitHub](https://github.com/Lunanxz)
- Matheus José Faustino Balieiro – [GitHub](https://github.com/Matheus-Balieiro)
- Tulio Ribeiro Nery – [GitHub](https://github.com/tulioribeiro864)
- Victor Lucas Almeida Pinheiro – [GitHub](https://github.com/VictorAlmeida09)
