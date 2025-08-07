# 🌍 Agência de Viagens - Aplicação Web

Esta aplicação web foi desenvolvida para facilitar a busca, reserva e gerenciamento de pacotes de viagem por clientes e administradores. Com frontend e backend integrados, oferece uma experiência completa e responsiva.

## 🧑‍💼 Área do Cliente

### 🏠 Página Inicial (`/`)
- Listagem de pacotes em cards
- Filtros e busca por destino
- Informações de preço e disponibilidade
- Navegação para detalhes

### 📦 Detalhes do Pacote (`/pacotes/:packageId`)
- Galeria de imagens
- Roteiro detalhado
- Sistema de avaliações
- Modal de reserva integrado

### 🔐 Login (`/login`)
- Autenticação via email/senha
- Validação de campos
- Recuperação de senha

### 📝 Minhas Reservas (`/reservas`) *(Rota Protegida)*
- Listagem e status das reservas
- Detalhes e histórico de viagens

### ⭐ Avaliar Pacote (`/avaliar/:packageId`) *(Rota Protegida)*
- Avaliação com estrelas e comentários
- Validação de avaliação única

### 👤 Perfil (`/perfil`) *(Rota Protegida)*
- Visualização e histórico de reservas

### 🔧 Recuperação de Senha
- Envio de código de verificação
- Redefinição via token (`/reset-password/:token`)

## 🛠️ Área Administrativa

### 🔐 Login Admin (`/admin/login`)
- Autenticação dedicada para administradores

### 📋 Lista de Pacotes (`/admin/pacotes`)
- Tabela com filtros e ações rápidas

### ➕ Adicionar Pacote (`/admin/pacotes/add`)
- Cadastro completo com imagens e roteiro

### ✏️ Editar Pacote (`/admin/pacotes/editar/:id`)
- Formulário pré-preenchido para edição

### 📊 Lista de Reservas (`/admin/reservas`)
- Dashboard com filtros e ações em massa

### 🔍 Detalhes da Reserva (`/admin/reservas/visualizar/:id`)
- Informações completas do cliente e status

### 💬 Moderação de Avaliações (`/admin/avaliacoes`)
- Filtros, respostas e moderação de comentários

### 📈 Métricas e Relatórios (`/admin/metricas`)
- Gráficos de vendas, satisfação e performance

## 🚀 Componentes Especiais

- **🔒 PrivateRoute**: Proteção de rotas por autenticação
- **🎨 Layout Principal**: Header, footer, menu responsivo e notificações
- **🎛️ AdminLayout**: Interface dedicada com sidebar e dashboard
- **📱 Sistema de Notificações**: React Toastify com auto-dismiss
- **🛡️ Segurança**: Validação de formulários e controle por roles
- **📱 Responsividade**: Design mobile-first e otimizado

## 🧪 Tecnologias Utilizadas
- React
- React Router
- CSS Modules
- React Toastify

## 👨‍💻 Desenvolvedores
- Leonardo dos Santos
- Eduardo Takashi
- Felipe Luis
- José Ruan
- Ana Leticia
- Julia Melo
