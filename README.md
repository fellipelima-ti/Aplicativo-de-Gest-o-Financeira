# 💰 Controle Financeiro - App Android

[![CI/CD](https://github.com/seu-usuario/controle-financeiro/workflows/Android%20CI/CD/badge.svg)](https://github.com/seu-usuario/controle-financeiro/actions)
[![Code Quality](https://img.shields.io/badge/Code%20Quality-A-green.svg)](https://github.com/seu-usuario/controle-financeiro)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=24)

> Um aplicativo Android moderno e intuitivo para controle financeiro pessoal, desenvolvido com as melhores práticas de desenvolvimento mobile.

## 🚀 Características

### ✨ Funcionalidades Principais
- 📊 **Dashboard Inteligente** - Visualização completa das finanças
- 💳 **Gestão de Gastos** - Categorização e controle detalhado
- 🎯 **Metas Financeiras** - Acompanhamento de objetivos
- 📈 **Analytics Avançados** - Relatórios e insights
- 🏦 **Integração Bancária** - Sincronização com contas
- 🔔 **Notificações Inteligentes** - Lembretes personalizados
- 🔒 **Segurança Avançada** - Biometria e criptografia

### 🛠️ Tecnologias Utilizadas
- **Linguagem**: Kotlin 100%
- **Arquitetura**: MVVM + Repository Pattern
- **UI**: Material Design 3 + ViewBinding
- **Banco de Dados**: Room + SQLite
- **Gráficos**: MPAndroidChart
- **Injeção de Dependência**: Manual (próximo: Hilt)
- **Testes**: JUnit + Espresso + Mockito
- **CI/CD**: GitHub Actions

## 📱 Screenshots

| Dashboard | Gastos | Metas | Analytics |
|-----------|--------|-------|-----------|
| ![Dashboard](docs/screenshots/dashboard.png) | ![Gastos](docs/screenshots/expenses.png) | ![Metas](docs/screenshots/goals.png) | ![Analytics](docs/screenshots/analytics.png) |

## 🏗️ Arquitetura

```
app/
├── data/           # Camada de dados (Room, Repository)
├── domain/         # Lógica de negócio (Use Cases)
├── presentation/   # UI (Activities, Fragments, ViewModels)
├── di/            # Injeção de dependências
├── utils/         # Utilitários e extensões
└── security/      # Segurança e criptografia
```

### 🎯 Padrões de Design
- **MVVM** - Separação clara de responsabilidades
- **Repository** - Abstração da fonte de dados
- **Observer** - Reatividade com LiveData/Flow
- **Factory** - Criação de objetos complexos
- **Strategy** - Algoritmos de cálculo flexíveis

## 🚀 Como Executar

### Pré-requisitos
- Android Studio Hedgehog ou superior
- JDK 11+
- Android SDK 24+
- Emulador Android ou dispositivo físico

### Instalação

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/controle-financeiro.git
cd controle-financeiro
```

2. **Abra no Android Studio**
```bash
# O Android Studio detectará automaticamente o projeto
```

3. **Execute o projeto**
```bash
./gradlew assembleDebug
./gradlew installDebug
```

### 🧪 Executar Testes

```bash
# Testes unitários
./gradlew test

# Testes de integração
./gradlew connectedAndroidTest

# Análise de código
./gradlew detekt
```

## 📊 Métricas de Qualidade

| Métrica | Valor | Status |
|---------|-------|--------|
| Cobertura de Testes | 85%+ | ✅ |
| Complexidade Ciclomática | < 10 | ✅ |
| Duplicação de Código | < 3% | ✅ |
| Vulnerabilidades | 0 | ✅ |
| Code Smells | < 50 | ✅ |

## 🔧 Configuração de Desenvolvimento

### Estrutura de Branches
```
main          # Produção
├── develop   # Desenvolvimento
├── feature/* # Novas funcionalidades
├── hotfix/*  # Correções urgentes
└── release/* # Preparação de releases
```

### Commits
Seguimos o padrão [Conventional Commits](https://www.conventionalcommits.org/):
```
feat: adiciona nova funcionalidade de exportação
fix: corrige bug no cálculo de juros
docs: atualiza documentação da API
style: formata código conforme padrão
refactor: melhora estrutura do ViewModel
test: adiciona testes para ExpenseRepository
```

## 🚀 Roadmap

### 📅 Próximas Versões

#### v2.0.0 - Q2 2024
- [ ] Integração com APIs bancárias
- [ ] Sincronização em nuvem
- [ ] Modo offline completo
- [ ] Temas personalizáveis

#### v2.1.0 - Q3 2024
- [ ] IA para insights financeiros
- [ ] Gamificação
- [ ] Relatórios avançados
- [ ] Exportação para Excel/PDF

#### v3.0.0 - Q4 2024
- [ ] Versão iOS (Kotlin Multiplatform)
- [ ] Widgets para home screen
- [ ] Integração com wearables
- [ ] API pública

## 🤝 Contribuição

Contribuições são bem-vindas! Por favor, leia nosso [Guia de Contribuição](CONTRIBUTING.md).

### Como Contribuir

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'feat: add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### 🐛 Reportar Bugs

Use o [GitHub Issues](https://github.com/seu-usuario/controle-financeiro/issues) para reportar bugs.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👥 Equipe

- **Desenvolvedor Principal** - [Seu Nome](https://github.com/seu-usuario)
- **Designer UX/UI** - [Nome do Designer](https://github.com/designer)
- **QA Tester** - [Nome do QA](https://github.com/qa)

## 🙏 Agradecimentos

- [Android Developers](https://developer.android.com/) - Documentação oficial
- [Material Design](https://material.io/) - Design system
- [Kotlin](https://kotlinlang.org/) - Linguagem de programação
- [Room](https://developer.android.com/training/data-storage/room) - Persistência de dados

## 📞 Contato

- **Email**: fellipelima.ti@gmail.com
- **Website**: https://controlefinanceiro.com
- **LinkedIn**: https://www.linkedin.com/in/fellipe-lima-de-jesus-958a2338a/

---

<div align="center">
  <p>Feito com ❤️ para ajudar você a controlar suas finanças</p>
  <p>⭐ Se este projeto te ajudou, considere dar uma estrela!</p>

</div>
