# Rosa Oliveira Advocacia - Website Institucional

Este é o repositório do site institucional do **Escritório de Advocacia Rosa Oliveira**, desenvolvido com **React** (Vite), **TypeScript** e **Tailwind CSS**.

O projeto é uma Single Page Application (SPA) moderna, responsiva e focada na experiência do usuário, apresentando informações sobre o escritório, áreas de atuação, blog e contato.

## 🚀 Tecnologias Utilizadas

- **React 19**: Biblioteca UI.
- **Vite**: Build tool e servidor de desenvolvimento.
- **TypeScript**: Tipagem estática.
- **Tailwind CSS v4**: Estilização.
- **TanStack Router**: Gerenciamento de rotas.
- **Lucide React**: Ícones.
- **Biome**: Linting e formatação.

## 🛠️ Instalação e Execução Local

Siga os passos abaixo para rodar o projeto em sua máquina:

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/GuilhermeATavares/ro-escritorio-adv.git
   cd ro-escritorio-adv
   ```

2. **Instale as dependências:**
   Este projeto utiliza o gerenciador de pacotes `pnpm`.
   ```bash
   pnpm install
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   pnpm dev
   ```
   Acesse o site em: `http://localhost:5173/ro-escritorio-adv/` (ou a porta indicada).

## 📦 Deploy (GitHub Pages)

O deploy é automatizado via **GitHub Actions**.

### Como funciona:
1. O arquivo de workflow está em `.github/workflows/deploy.yml`.
2. Ao fazer um push para a branch `main`, a action é disparada.
3. O build é gerado e publicado na branch `gh-pages`.

### URL de Acesso:
O site está publicado em:  
🔗 **https://GuilhermeATavares.github.io/ro-escritorio-adv/**

## 📝 Estrutura de Pastas

```
src/
├── components/     # Componentes da UI (Hero, Navbar, Contact, etc.)
├── routes/         # Definição de rotas (TanStack Router)
├── assets/         # Imagens e arquivos estáticos
└── main.tsx        # Ponto de entrada da aplicação
```

---
Desenvolvido por Guilherme Tavares.
