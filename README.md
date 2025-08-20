# 📚 GitBook Reader

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/oArthurCandido/bookdown?style=for-the-badge)](https://github.com/oArthurCandido/bookdown/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/oArthurCandido/bookdown?style=for-the-badge)](https://github.com/oArthurCandido/bookdown/network)
[![GitHub license](https://img.shields.io/github/license/oArthurCandido/bookdown?style=for-the-badge)](https://github.com/oArthurCandido/bookdown/blob/main/LICENSE)

_Um leitor de livros e documentos Markdown elegante e intuitivo para repositórios do GitHub_

[🚀 Demo ao Vivo](https://oarthurcandido.github.io/bookdown) • [📖 Documentação](https://github.com/oArthurCandido/bookdown/wiki) • [🐛 Reportar Bug](https://github.com/oArthurCandido/bookdown/issues) • [💡 Sugerir Feature](https://github.com/oArthurCandido/bookdown/discussions)

</div>

## ✨ O que é o GitBook Reader?

O GitBook Reader é uma aplicação web moderna que transforma repositórios GitHub contendo documentação Markdown em uma experiência de leitura semelhante ao Kindle. Com design inspirado em papel e funcionalidades avançadas de navegação, torna o consumo de conteúdo técnico mais agradável e eficiente.

### 🎯 **Por que usar o GitBook Reader?**

- 📱 **Design Responsivo**: Otimizado para desktop, tablet e mobile
- 🌙 **Tema Papel**: Interface inspirada no Kindle com cores suaves para leitura prolongada
- 📖 **Sumário Interativo**: TOC automático com navegação suave entre seções
- 💾 **Progresso Persistente**: Salva automaticamente sua posição de leitura
- 🔖 **Sistema de Capítulos**: Marque capítulos como lidos e acompanhe seu progresso
- 🏠 **Biblioteca Pessoal**: Histórico visual com capas de livros extraídas automaticamente

## 🚀 Funcionalidades Principais

### 📚 **Experiência de Leitura**

- Interface clean e minimalista focada no conteúdo
- Modo de leitura mobile com navbar oculta para imersão total
- Barra de progresso de leitura em tempo real
- Navegação fluida entre capítulos

### 📊 **Gerenciamento de Progresso**

- Marcação automática de capítulos completos baseada no scroll
- Toggle manual para marcar/desmarcar capítulos como lidos
- Restauração automática da posição de leitura
- Histórico persistente no navegador

### 🎨 **Interface Moderna**

- Design em grid para biblioteca de livros
- Cards visuais com capas extraídas automaticamente
- Sumário expansível com TOC interno
- Animações suaves e transições elegantes

### 📱 **Mobile-First**

- Menu hamburger intuitivo
- Controles otimizados para toque
- Navbar que some/aparece baseada no scroll
- Layout adaptativo para diferentes tamanhos de tela

## 🛠️ Como Usar

### 1. **Acesse a Aplicação**

Visite [GitBook Reader](https://oarthurcandido.github.io/bookdown) no seu navegador

### 2. **Adicione um Livro**

```
Cole a URL de um README.md ou documento principal do GitHub:
https://github.com/user/repo/blob/main/README.md
```

### 3. **Navegue e Leia**

- Use a sidebar para navegar entre capítulos
- Clique nos links do TOC para pular seções
- Marque capítulos como lidos conforme avança
- Seu progresso é salvo automaticamente

### 📖 **Exemplos de URLs Suportadas**

```
✅ https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/get-started/README.md
✅ https://github.com/getify/You-Dont-Know-JS/blob/2nd-ed/scope-closures/README.md
```

## 🏗️ Arquitetura Técnica

### **Frontend Puro**

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Variáveis CSS, Grid Layout, Flexbox
- **JavaScript ES6+**: Módulos, async/await, APIs modernas

### **Funcionalidades Core**

- **Marked.js**: Parser Markdown para HTML
- **Intersection Observer**: Tracking de progresso de leitura
- **LocalStorage**: Persistência de dados no navegador
- **Fetch API**: Carregamento de conteúdo do GitHub

### **Recursos Avançados**

- Regex para extração de metadados
- DOM parsing para criação de TOC
- Event delegation para performance
- Responsive design com media queries

## 🤝 Como Contribuir

Adoramos contribuições da comunidade! Aqui estão várias maneiras de ajudar:

### 🐛 **Reportar Bugs**

Encontrou um problema? [Abra uma issue](https://github.com/oArthurCandido/bookdown/issues/new?template=bug_report.md) com:

- Descrição detalhada do problema
- Passos para reproduzir
- Screenshots/gifs se aplicável
- Informações do navegador/device

### 💡 **Sugerir Features**

Tem uma ideia genial? [Inicie uma discussão](https://github.com/oArthurCandido/bookdown/discussions) ou [crie uma issue](https://github.com/oArthurCandido/bookdown/issues/new?template=feature_request.md)

### 👩‍💻 **Contribuir com Código**

1. **Fork** o repositório
2. **Clone** seu fork: `git clone https://github.com/oArthurCandido/bookdown.git`
3. **Crie** uma branch: `git checkout -b feature/minha-funcionalidade`
4. **Desenvolva** suas alterações
5. **Teste** localmente abrindo `index.html` no navegador
6. **Commit**: `git commit -m "feat: adiciona funcionalidade X"`
7. **Push**: `git push origin feature/minha-funcionalidade`
8. **Abra** um Pull Request

### 🎨 **Áreas para Contribuição**

#### 🔥 **Funcionalidades Prioritárias**

- [ ] Modo escuro/claro toggle
- [ ] Busca full-text no conteúdo
- [ ] Exportar progresso (JSON/CSV)
- [ ] Suporte a múltiplos idiomas
- [ ] PWA com cache offline

#### 🚀 **Melhorias Técnicas**

- [ ] Testes automatizados (Jest/Cypress)
- [ ] Build process (Vite/Webpack)
- [ ] TypeScript migration
- [ ] Performance optimizations
- [ ] Accessibility improvements (ARIA, screen readers)

#### 🎯 **Novas Funcionalidades**

- [ ] Anotações e highlights
- [ ] Sincronização entre dispositivos
- [ ] Suporte a GitLab/Bitbucket
- [ ] Plugin system
- [ ] API REST para integração

### 📋 **Guidelines de Contribuição**

#### **Padrões de Código**

- Use `const`/`let` ao invés de `var`
- Prefira arrow functions para callbacks
- Mantenha funções pequenas e focadas
- Comente código complexo em português
- Use nomes descritivos para variáveis

#### **Padrões de Commit**

```
feat: adiciona nova funcionalidade
fix: corrige bug específico
docs: atualiza documentação
style: mudanças de formatação
refactor: refatora código existente
test: adiciona ou corrige testes
chore: mudanças em build/configuração
```

#### **Pull Requests**

- Descreva claramente as mudanças
- Inclua screenshots para mudanças visuais
- Teste em múltiplos navegadores
- Mantenha commits organizados
- Responda feedback constructivamente

## 🌟 Roadmap

### **v2.0 - Experiência Aprimorada**

- [ ] Interface completamente redesenhada
- [ ] Modo escuro nativo
- [ ] Busca avançada e filtros
- [ ] Sistema de tags e categorias

### **v2.1 - Social & Colaborativo**

- [ ] Compartilhamento de listas de leitura
- [ ] Comentários e discussões
- [ ] Sistema de avaliações
- [ ] Perfis de usuário

### **v3.0 - Plataforma Completa**

- [ ] Backend com banco de dados
- [ ] Sincronização multi-dispositivo
- [ ] API REST pública
- [ ] Aplicativo mobile nativo

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE) - veja o arquivo LICENSE para detalhes.

## 🙏 Agradecimentos

- [Marked.js](https://marked.js.org/) - Parser Markdown fantástico
- [GitHub](https://github.com) - Por hospedar milhões de documentos incríveis
- [MDN Web Docs](https://developer.mozilla.org/) - Referência técnica essencial
- Comunidade open source - Por inspirar projetos como este

## 📞 Contato & Suporte

- 🐛 **Issues**: [GitHub Issues](https://github.com/oArthurCandido/bookdown/issues)
- 💬 **Discussões**: [GitHub Discussions](https://github.com/oArthurCandido/bookdown/discussions)
- 📧 **Email**: [oarthurcandido@gmail.com](mailto:oarthurcandido@gmail.com)
- 🐦 **Instagram**: [@oArthurCandido](https://www.instagram.com/oArthurCandido/)

## ⭐ Apoie o Projeto

Se o GitBook Reader te ajudou, considere:

- ⭐ Dar uma estrela no repositório
- 🐦 Compartilhar nas redes sociais
- 📝 Escrever um review/blog post
- 💝 Contribuir com código ou documentação

---

<div align="center">

**Feito com ❤️ por [Arthur Candido](https://github.com/oArthurCandido)**

_Transformando documentação em conhecimento, um README por vez_

[![GitHub followers](https://img.shields.io/github/followers/oArthurCandido?style=social)](https://github.com/oArthurCandido)

</div>
