# 🤝 Contributing Guide — KernelMind

Thank you for your interest in contributing to KernelMind! This document contains guidelines for different types of contributions.

## 📋 Types of Contribution

### 🎵 Music Production
- **Track feedback**: Test tracks during coding sessions and share your experience
- **Improvement suggestions**: BPM adjustments, binaural frequencies, structure
- **New tracks**: Proposals for album expansions

### 💻 Desenvolvimento
- **Web App**: Frontend/backend para aplicativo interativo
- **IDE Extensions**: Plugins para VS Code, JetBrains, etc.
- **Bug fixes**: Correções em código existente
- **Features**: Implementação de novas funcionalidades

### 🔬 Pesquisa Científica
- **Estudos de caso**: Documentar efeitos das batidas binaurais
- **Revisão de literatura**: Atualizar base científica
- **Metodologia**: Melhorar protocolos de teste

### 📚 Documentation
- **Traduções**: i18n para outros idiomas
- **Tutoriais**: Como usar o KernelMind efetivamente
- **Exemplos**: Casos de uso específicos
- **FAQ**: Respostas a perguntas comuns

### 🎨 Design
- **Visual identity**: Refinamentos na identidade visual
- **UI/UX**: Melhorias na interface do aplicativo
- **Marketing materials**: Assets para divulgação

## 🚀 Getting Started

### 1. Fork the repository
```bash
# Clone seu fork
git clone https://github.com/SEU_USERNAME/KernelMind.git
cd KernelMind

# Configure o remote upstream
git remote add upstream https://github.com/KernelMind/KernelMind.git
```

### 2. Configure o Ambiente
```bash
# Instale dependências (Node.js)
npm install

# Ou Python (se contribuindo com research)
pip install -r requirements.txt
```

### 3. Crie uma Branch
```bash
# Para features
git checkout -b feature/nome-da-feature

# Para bug fixes  
git checkout -b fix/descricao-do-bug

# For documentation
git checkout -b docs/topico
```

## 📝 Padrões de Commit

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): description

[optional body]

[optional footer]
```

### Tipos
- `feat`: Nova funcionalidade
- `fix`: Correção de bug
- `docs`: Documentation
- `style`: Formatação, lint
- `refactor`: Refatoração de código
- `test`: Testes
- `chore`: Tarefas de manutenção

### Exemplos
```bash
feat(app): add keyboard monitoring for BPM adaptation
fix(audio): resolve binaural beat phase issues
docs(readme): update installation instructions
style(css): improve responsive design
refactor(player): optimize audio processing pipeline
test(integration): add IDE extension tests
chore(deps): update dependencies
```

### 🎵 Music Contributions

### Review Process
1. **Demo Track**: Submit a 30-60 second demo
2. **Concept Doc**: Explain the concept and techniques used
3. **Technical Specs**: BPM, key, frequencies, structure
4. **Community Feedback**: Collect community feedback
5. **Final Production**: Final production after approval

### Quality Criteria
- **Binaural frequencies** implemented correctly
- **BPM** suitable for focus/productivity
- **Duration** between 4-7 minutes
- **Mixing/Mastering** professional (-16 LUFS target)
- **Concept** aligned with operating-system metaphors

## 💻 Contribuições de Código

### Project Structure
```
KernelMind/
├── src/
│   ├── app/           # Web application
│   ├── extensions/    # IDE extensions
│   ├── audio/         # Audio processing
│   └── research/      # Scientific analysis
├── docs/             # Documentation
├── assets/           # Audio files, images
└── tests/            # Test suite
```

### Coding Standards
- **JavaScript/TypeScript**: ESLint + Prettier
- **Python**: PEP 8, Black formatter
- **Testing**: 80%+ coverage required
- **Documentation**: JSDoc/Sphinx for APIs

### Pull Request Process
1. **Issue First**: Crie issue descrevendo a proposta
2. **Discussion**: Aguarde feedback da comunidade
3. **Development**: Implemente seguindo os padrões
4. **Tests**: Adicione testes apropriados
5. **Documentation**: Atualize docs relevantes
6. **PR**: Crie PR linkando à issue original

### Review Checklist
- [ ] Código segue padrões estabelecidos
- [ ] Testes passam (CI/CD)
- [ ] Coverage mantém 80%+
- [ ] Documentation updated
- [ ] Performance não degradada
- [ ] Breaking changes documentadas

## 🔬 Contribuições Científicas

### Research Guidelines
- **Methodology**: Use métodos peer-reviewed
- **Data**: Compartilhe datasets quando possível
- **Reproducibility**: Reproducible code and analyses
- **Ethics**: Siga diretrizes éticas para pesquisa com humanos

### Tipos de Estudos Aceitos
- **EEG Studies**: Validação de entrainment neural
- **Productivity Studies**: Impacto na performance de coding
- **User Experience**: Surveys e estudos qualitativos
- **Meta-analyses**: Revisões sistemáticas

## 📚 Documentation Contributions

### Padrões de Escrita
- **Tom**: Técnico mas acessível
- **Estrutura**: Use headers e listas para clareza
- **Exemplos**: Inclua code samples e screenshots
- **Links**: Reference official documentation

### Traduções
- **Priority languages**: ES, FR, DE, JA
- **Consistência**: Use glossário de termos técnicos
- **Review**: Traduções passam por review nativo

## 🎨 Contribuições de Design

### Brand Guidelines
- Siga [Visual Identity Guide](VISUAL_IDENTITY_GUIDE.md)
- Mantenha consistência com paleta de cores
- Use tipografia monoespaçada quando apropriado

### Assets Requirements
- **Vector formats**: SVG preferível
- **High resolution**: Mínimo 2x para displays retina
- **Accessibility**: Contrast ratio WCAG AA

## 🏆 Reconhecimento

### Contributors Wall
Todos os contributors são reconhecidos em:
- README.md principal
- About page do aplicativo
- Créditos do álbum (para contribuições musicais)

### Levels of Contribution
- **🎵 Music Producer**: Contribuições musicais aprovadas
- **💻 Core Developer**: 5+ PRs de código aceitos
- **🔬 Researcher**: Estudos científicos validados
- **📚 Documentation**: Melhorias significativas em docs
- **🎨 Designer**: Contribuições visuais implementadas
- **🌟 Maintainer**: Contributors com acesso de escrita

## 📞 Comunidade

### Onde Encontrar Ajuda
- **Discord**: [KernelMind Community Server]
- **GitHub Discussions**: Para discussões longas
- **Issues**: Para bugs e feature requests
- **Email**: contributors@kernelmind.audio

### Code of Conduct
This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to maintain a respectful and inclusive environment.

### Office Hours
- **Weekly Community Call**: Mondays, 19:00 UTC
- **Music Review Sessions**: Thursdays, 20:00 UTC
- **Development Sync**: Fridays, 15:00 UTC

---

## 🙏 Thank you!

Your contribution helps make KernelMind better for the entire developer community. Welcome to our contributor community!

---

*For questions about this guide, open an issue or reach out via [Discord](discord-link)*