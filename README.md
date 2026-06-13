# 📚 Aula Proj2 - Variáveis e Operadores

Projeto educativo do curso de **JavaScript** da [DIO](https://www.dio.me/) focado em conceitos fundamentais de variáveis e operadores.

## 📋 Descrição

Este projeto contém exercícios e exemplos práticos sobre:
- ✅ Declaração e escopo de variáveis (`var`, `let`, `const`)
- ✅ Tipos de dados em JavaScript
- ✅ Operadores aritméticos, lógicos e de comparação
- ✅ Operadores de atribuição
- ✅ Operadores ternários

## 🚀 Como Executar o Projeto

### Pré-requisitos

Você precisará ter instalado em sua máquina:
- **Node.js** (versão 14 ou superior) - [Download aqui](https://nodejs.org/)
- **npm** (geralmente vem com Node.js) ou **yarn**
- **Git** - [Download aqui](https://git-scm.com/)

Verifique a instalação com:
```bash
node --version
npm --version
```

### Passo 1: Clonar o Repositório

```bash
git clone https://github.com/Rodney-78/aula-proj2-variaveis-operadores.git
cd aula-proj2-variaveis-operadores
```

### Passo 2: Instalar Dependências (se houver)

```bash
npm install
```

### Passo 3: Executar o Projeto

#### Opção A: Executar diretamente com Node.js
```bash
node index.js
```

#### Opção B: Se for um arquivo HTML, abra no navegador
```bash
# No Windows
start index.html

# No macOS
open index.html

# No Linux
xdg-open index.html
```

#### Opção C: Usar um servidor local
```bash
# Com http-server (instale com: npm install -g http-server)
http-server

# Com Python 3
python -m http.server 8000
```

## 📁 Estrutura do Projeto

```
aula-proj2-variaveis-operadores/
├── index.js          # Arquivo principal com os exercícios
├── README.md         # Este arquivo
└── package.json      # Dependências do projeto (se houver)
```

## 🛠️ Tecnologias Utilizadas

- **JavaScript (ES6+)** - Linguagem principal
- **Node.js** - Runtime para executar JavaScript
- **npm** - Gerenciador de pacotes

## 📖 Conceitos Cobertos

### Variáveis
```javascript
var nome = "João";           // escopo global ou de função
let idade = 25;              // escopo de bloco
const cidade = "São Paulo";  // escopo de bloco, imutável
```

### Operadores
```javascript
// Aritméticos
10 + 5    // Adição
10 - 5    // Subtração
10 * 5    // Multiplicação
10 / 5    // Divisão
10 % 3    // Módulo (resto)
2 ** 3    // Exponenciação

// Comparação
5 == "5"     // Comparação de valor
5 === "5"    // Comparação de valor e tipo
5 != 5       // Diferente
5 > 3        // Maior que

// Lógicos
true && false   // E (AND)
true || false   // OU (OR)
!true           // NÃO (NOT)

// Ternário
idade >= 18 ? "Maior de idade" : "Menor de idade"
```

## 💡 Dicas

- Use `console.log()` para exibir valores no console
- Abra o Developer Tools do navegador (F12) para ver outputs
- Teste seus códigos passo a passo
- Leia a documentação do [MDN Web Docs](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

## 📚 Recursos Úteis

- [MDN - JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
- [DIO - Trilha JavaScript](https://www.dio.me/)
- [JavaScript.info](https://javascript.info/)

## 👤 Autor

- **Rodney-78** - [GitHub Profile](https://github.com/Rodney-78)

## 📝 Licença

Este projeto é fornecido como material educativo pela DIO.

---

**Dúvidas?** Abra uma [issue](https://github.com/Rodney-78/aula-proj2-variaveis-operadores/issues) ou entre em contato! 🤝
