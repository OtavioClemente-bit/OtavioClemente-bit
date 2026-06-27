# SIGFUR WPF — Sistema Integrado de Gestão do Furriel

O **SIGFUR WPF** é o meu principal projeto de desenvolvimento: uma aplicação desktop criada para centralizar, organizar e automatizar rotinas administrativas complexas, substituindo planilhas, arquivos soltos e processos manuais por um sistema integrado.

A aplicação foi desenvolvida em **C# com WPF**, usando arquitetura orientada a serviços, persistência local, automações, geração documental e módulos específicos para gestão administrativa.

> Por envolver fluxos administrativos reais, este projeto está em preparação para publicação segura. A versão pública deve conter somente código limpo, dados fictícios e documentação técnica, sem informações pessoais, documentos internos, bancos reais ou arquivos sensíveis.

---

## Visão geral

O SIGFUR nasceu como uma solução prática para resolver problemas reais do dia a dia: controle de efetivo, conferência de documentos, organização de informações, geração de boletins, acompanhamento de pendências e automação de tarefas repetitivas.

A versão WPF representa a evolução do projeto original em Python/Tkinter para uma base mais robusta, visualmente mais profissional e com melhor separação de responsabilidades.

---

## Principais objetivos

- Reduzir retrabalho administrativo
- Organizar dados em uma interface única
- Automatizar rotinas repetitivas
- Melhorar conferência e rastreabilidade de informações
- Facilitar consulta rápida por militar, assunto, documento ou pendência
- Substituir planilhas e controles soltos por uma aplicação integrada
- Criar uma base evolutiva para novos módulos

---

## Tecnologias utilizadas

- **C#**
- **WPF**
- **.NET**
- **SQLite**
- **OpenXML**
- **Selenium WebDriver**
- **Manipulação de PDF**
- **Arquitetura em camadas**
- **Git e GitHub**

---

## Arquitetura observada

O projeto possui separação em camadas e componentes, incluindo:

```text
SIGFUR.Wpf/
├── Models/        # Modelos de domínio e estruturas de dados
├── Services/      # Regras de negócio, automações e persistência
├── ViewModels/    # Estado e comandos da interface
├── Views/         # Telas e janelas WPF
├── Controls/      # Componentes visuais reutilizáveis
├── Themes/        # Tokens visuais e estilos
├── Assets/        # Ícones e identidade visual
└── bridge/        # Integrações auxiliares com automações específicas
```

---

## Módulos e funcionalidades

### Gestão de efetivo

- Cadastro e consulta de militares
- Organização de dados por posto/graduação
- Carteira individual do militar
- Preferências e documentos vinculados
- Busca rápida e navegação por registros

### Boletins e documentação

- Boletim inteligente
- Boletim do furriel
- Parser de informações documentais
- Geração e formatação de textos administrativos
- Consulta e abertura de documentos relacionados
- Organização por assunto, data e vínculo

### Pagamento e conferência

- Conferência de contracheques
- Auditoria de rubricas
- Auxílio-transporte
- Auxílio-alimentação
- Gratificação
- Exercício anterior
- Pensão judicial
- Ajuste de contas

### Rotina administrativa

- Plano de férias
- Lembretes
- Aniversariantes
- Plano de chamada
- Medidas tomadas
- Licenciados e transferidos
- Controle de pendências

### Automação e produtividade

- Integrações com fluxos externos
- Automação de navegação com Selenium
- Leitura e processamento de documentos
- Geração de arquivos administrativos
- Persistência de estado da interface
- Backup e restauração

---

## Diferenciais do projeto

- Projeto criado para resolver uma necessidade real
- Interface desktop voltada para usuário operacional
- Muitos módulos integrados em uma única aplicação
- Uso de persistência local para funcionamento independente
- Preocupação com organização, rastreabilidade e produtividade
- Evolução de uma versão Python/Tkinter para C# WPF
- Base com potencial de virar produto interno ou case profissional

---

## Cuidados para publicação pública

Antes de abrir o código completo no GitHub, a versão pública deve passar por uma limpeza rigorosa:

- Remover bancos reais (`.db`, `.sqlite`, `.sqlite3`)
- Remover contracheques, boletins, PDFs, planilhas e documentos internos
- Remover pastas `bin/`, `obj/`, `PUBLICADO/`, `.venv/`, `__pycache__/`
- Remover caminhos locais de máquina
- Remover tokens, senhas, usuários e credenciais
- Substituir dados reais por dados fictícios
- Criar um `README.md` técnico e objetivo
- Criar `.gitignore` próprio para WPF/.NET
- Adicionar capturas de tela com dados fictícios

---

## Roadmap de portfólio

- [ ] Criar repositório público limpo do SIGFUR WPF
- [ ] Adicionar README profissional
- [ ] Subir apenas código e recursos seguros
- [ ] Criar prints com dados fictícios
- [ ] Documentar arquitetura e principais módulos
- [ ] Adicionar instruções de build
- [ ] Criar release demonstrativa sem dados sensíveis

---

## Resultado esperado

O SIGFUR WPF deve ser apresentado como meu principal case de portfólio: um sistema real, modular, com automações, interface desktop, persistência local e foco em resolver problema concreto.

Ele demonstra minha capacidade de sair de scripts simples e evoluir para uma aplicação maior, com arquitetura, interface, regras de negócio e preocupação com operação real.

---

## Autor

Desenvolvido por **Otavio Clemente**  
Estudante de Ciência da Computação e desenvolvedor em formação, com foco em C#, Python, automação e sistemas administrativos.

- GitHub: [@OtavioClemente-bit](https://github.com/OtavioClemente-bit)
- LinkedIn: [Otavio Clemente](https://www.linkedin.com/in/otavio-clemente-36056b2b5/)
