# 🌌 Eldritch Game

Um projeto independente de jogo de investigação e **horror cósmico**, inspirado em *Eldritch Horror* e desenvolvido como projeto de estudo e experimentação em **HTML, CSS e JavaScript**.

O projeto começou como um protótipo em HTML e está sendo gradualmente reorganizado em uma arquitetura modular, com o objetivo de transformar suas mecânicas em sistemas independentes, organizados e fáceis de expandir.

> ⚠️ **Aviso:** Este é um projeto independente, criado para fins de estudo e desenvolvimento. Não é um produto oficial e não possui vínculo com os detentores dos direitos de *Eldritch Horror*.

---

## 🎮 Sobre o projeto

A proposta é desenvolver uma experiência digital própria baseada em conceitos de jogos de investigação cooperativa e horror cósmico.

Os jogadores assumem o papel de **investigadores** que precisam explorar o mundo, enfrentar monstros, resolver mistérios e lidar com acontecimentos sobrenaturais enquanto tentam impedir o avanço de uma ameaça ancestral.

### Principais sistemas planejados

- 🕵️ Investigadores
- 👁️ Anciões
- 🗺️ Mapa e locais de viagem
- 🚂 Movimento e transporte
- 💰 Recursos
- 🔮 Artefatos
- ✨ Feitiços
- ⚠️ Condições
- 👹 Monstros
- 🌀 Portais
- 🔍 Pistas
- 📜 Cartas de Mythos
- 🧩 Mistérios
- 📖 Cartas de Pesquisa
- ⚔️ Combate
- 🎴 Encontros
- 🔄 Turnos e fases
- 🏆 Condições de vitória e derrota

---

## 🧪 Status do projeto

> **🚧 Em desenvolvimento**

O projeto possui atualmente um **protótipo funcional**, que serve como referência para a reconstrução da versão modular.

### Protótipo

O protótipo inicial concentra grande parte da lógica em um único arquivo HTML e foi criado para testar rapidamente as mecânicas e a estrutura geral do jogo.

Ele continuará no repositório como uma versão de referência.

### Versão modular

A próxima etapa é dividir o projeto em diferentes módulos:

```text
src/
├── index.html
├── css/
│   ├── style.css
│   ├── board.css
│   ├── cards.css
│   └── investigators.css
│
└── js/
    ├── main.js
    ├── game.js
    ├── setup.js
    ├── map.js
    ├── movement.js
    ├── combat.js
    ├── encounters.js
    ├── mythos.js
    │
    └── data/
        ├── investigators.js
        ├── ancients.js
        ├── resources.js
        ├── artifacts.js
        ├── spells.js
        ├── conditions.js
        ├── monsters.js
        ├── mythos-cards.js
        ├── mysteries.js
        └── research.js
```

A ideia principal é separar:

**dados do jogo** → `data/`

**lógica e sistemas** → `js/`

Isso permitirá adicionar novos investigadores, cartas, monstros e outros conteúdos sem precisar modificar os sistemas principais.

---

## 🛠️ Tecnologias

O projeto utiliza atualmente:

- **HTML5**
- **CSS3**
- **JavaScript**
- **SVG** para elementos gráficos do mapa
- **Git**
- **GitHub**

A primeira versão está sendo desenvolvida sem frameworks, com o objetivo de facilitar o aprendizado dos fundamentos de JavaScript e desenvolvimento web.

---

## 🗺️ Roadmap

### 🏗️ Estrutura

- [x] Criar protótipo funcional
- [ ] Separar HTML, CSS e JavaScript
- [ ] Criar arquitetura modular
- [ ] Separar dados dos sistemas
- [ ] Criar gerenciamento do estado do jogo
- [ ] Criar sistema de salvamento

### 🕵️ Investigadores

- [ ] Implementar todos os investigadores
- [ ] Implementar atributos
- [ ] Implementar habilidades ativas
- [ ] Implementar habilidades passivas
- [ ] Implementar seleção de 1–8 jogadores
- [ ] Implementar estados dos investigadores

### 🗺️ Mapa

- [ ] Implementar mapa completo
- [ ] Implementar todos os locais de viagem
- [ ] Implementar rotas
- [ ] Implementar viagens
- [ ] Implementar transporte
- [ ] Implementar portais
- [ ] Implementar pistas
- [ ] Implementar movimentação de monstros

### 🎴 Cartas

- [ ] Recursos
- [ ] Artefatos
- [ ] Feitiços
- [ ] Condições
- [ ] Monstros
- [ ] Mythos
- [ ] Mistérios
- [ ] Pesquisa

### ⚙️ Sistemas

- [ ] Sistema de turnos
- [ ] Sistema de ações
- [ ] Sistema de encontros
- [ ] Sistema de combate
- [ ] Sistema de testes
- [ ] Sistema de efeitos
- [ ] Sistema de Mythos
- [ ] Sistema de Mistérios
- [ ] Condições de vitória
- [ ] Condições de derrota

### 🎨 Interface

- [ ] Interface principal
- [ ] Exibição das cartas
- [ ] Fichas dos investigadores
- [ ] Informações do Ancião
- [ ] Indicadores de jogo
- [ ] Melhorias de acessibilidade
- [ ] Interface responsiva

---

## 📚 Objetivo educacional

Além do desenvolvimento do jogo, este projeto também funciona como um **projeto de aprendizado de programação**.

Durante seu desenvolvimento serão praticados conceitos como:

- JavaScript
- HTML
- CSS
- Funções
- Objetos e arrays
- Programação orientada a objetos
- Modularização
- Manipulação do DOM
- Gerenciamento de estado
- Git
- GitHub
- Testes
- Arquitetura de software
- Desenvolvimento de jogos

O objetivo não é apenas fazer o jogo funcionar, mas também **compreender como cada sistema funciona e como organizar um projeto de maior escala**.

---

## 📁 Estrutura do repositório

```text
eldritch-game/
│
├── prototype/       # Protótipo original
│
├── src/             # Versão principal do jogo
│   ├── css/         # Estilos
│   └── js/          # Sistemas e lógica
│       └── data/    # Dados do jogo
│
├── assets/          # Imagens, ícones e outros recursos
│
├── docs/            # Documentação
│
└── tests/           # Testes
```

---

## 🚧 Desenvolvimento

O projeto está em constante evolução.

A estrutura, os sistemas e a organização do código podem mudar conforme o desenvolvimento avança e novos conhecimentos são adquiridos.

O protótipo existente **não representa necessariamente a arquitetura final** do projeto.

---

## 📜 Licença

Este projeto é independente e destinado principalmente a fins educacionais e de desenvolvimento pessoal.

*Eldritch Horror* e seus elementos pertencentes à propriedade intelectual original são de seus respectivos detentores. Este projeto não reivindica propriedade sobre materiais protegidos pertencentes a terceiros.
```
