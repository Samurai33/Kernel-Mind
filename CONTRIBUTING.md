# 🤝 Guia de Contribuição - KernelMind

Obrigado pelo interesse em contribuir com o KernelMind! Este documento contém diretrizes para diferentes tipos de contribuição.

## 📋 Tipos de Contribuição

### 🎵 Produção Musical
- **Feedback sobre faixas**: Teste as faixas em sessões de coding e compartilhe sua experiência
- **Sugestões de melhorias**: Ajustes em BPM, frequências binaurais, estrutura
- **Novas faixas**: Propostas para expansões do álbum

### 💻 Desenvolvimento
- **Web App**: Frontend/backend para aplicativo interativo
- **IDE Extensions**: Plugins para VS Code, JetBrains, etc.
- **Bug fixes**: Correções em código existente
- **Features**: Implementação de novas funcionalidades

### 🔬 Pesquisa Científica
- **Estudos de caso**: Documentar efeitos das batidas binaurais
- **Revisão de literatura**: Atualizar base científica
- **Metodologia**: Melhorar protocolos de teste

### 📚 Documentação
- **Traduções**: i18n para outros idiomas
- **Tutoriais**: Como usar o KernelMind efetivamente
- **Exemplos**: Casos de uso específicos
- **FAQ**: Respostas a perguntas comuns

### 🎨 Design
- **Visual identity**: Refinamentos na identidade visual
- **UI/UX**: Melhorias na interface do aplicativo
- **Marketing materials**: Assets para divulgação

## 🚀 Como Começar

### 1. Fork do Repositório
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

# Para documentação
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
- `docs`: Documentação
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

## 🎵 Contribuições Musicais

### Processo de Review
1. **Demo Track**: Envie uma demo de 30-60 segundos
2. **Concept Doc**: Explique o conceito e técnicas usadas
3. **Technical Specs**: BPM, key, frequencies, structure
4. **Community Feedback**: Colete feedback da comunidade
5. **Final Production**: Produção final após aprovação

### Critérios de Qualidade
- **Frequências binaurais** implementadas corretamente
- **BPM** adequado para foco/produtividade
- **Duração** entre 4-7 minutos
- **Mixing/Mastering** profissional (-16 LUFS target)
- **Conceito** alinhado com metáforas de sistema operacional

## 💻 Contribuições de Código

### Estrutura do Projeto
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

### Padrões de Código
- **JavaScript/TypeScript**: ESLint + Prettier
- **Python**: PEP 8, Black formatter
- **Testing**: 80%+ coverage obrigatória
- **Documentation**: JSDoc/Sphinx para APIs

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
- [ ] Documentação atualizada
- [ ] Performance não degradada
- [ ] Breaking changes documentadas

## 🔬 Contribuições Científicas

### Research Guidelines
- **Methodology**: Use métodos peer-reviewed
- **Data**: Compartilhe datasets quando possível
- **Reproducibility**: Código e análises reproduzíveis
- **Ethics**: Siga diretrizes éticas para pesquisa com humanos

### Tipos de Estudos Aceitos
- **EEG Studies**: Validação de entrainment neural
- **Productivity Studies**: Impacto na performance de coding
- **User Experience**: Surveys e estudos qualitativos
- **Meta-analyses**: Revisões sistemáticas

## 📚 Contribuições de Documentação

### Padrões de Escrita
- **Tom**: Técnico mas acessível
- **Estrutura**: Use headers e listas para clareza
- **Exemplos**: Inclua code samples e screenshots
- **Links**: Referencie documentação oficial

### Traduções
- **Idiomas prioritários**: ES, FR, DE, JA, PT-BR
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
Este projeto segue nosso [Code of Conduct](CODE_OF_CONDUCT.md). Ao participar, você concorda em manter um ambiente respeitoso e inclusivo.

### Office Hours
- **Weekly Community Call**: Segundas, 19:00 UTC
- **Music Review Sessions**: Quintas, 20:00 UTC
- **Development Sync**: Sextas, 15:00 UTC

---

## 🙏 Obrigado!

Sua contribuição ajuda a tornar o KernelMind melhor para toda a comunidade de desenvolvedores. Seja bem-vindo(a) à nossa família de contributors!

---

*Para dúvidas sobre este guia, abra uma issue ou entre em contato via [Discord](discord-link)*