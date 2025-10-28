# 💱 Aplicação de Conversão de Moedas

Um conversor de moedas desenvolvido em Java que permite a conversão entre Dólar Americano (USD) e as moedas latino-americanas: Real Brasileiro (BRL), Peso Argentino (ARS) e Peso Colombiano (COP).

## ✨ Características do Projeto

- **🎯 Interface Console Interativa**: Menu intuitivo para seleção de opções de conversão
- **🔄 Conversões Bidirecionais**: Suporte a conversões de ida e volta entre USD e moedas latinas
- **🏗️ Arquitetura Modular**: Estrutura organizada com separação de responsabilidades
- **🔌 Pronto para API Externa**: Estrutura preparada para integração com APIs de câmbio reais

## 🛠️ Tecnologias Utilizadas

- **Java** - Linguagem de programação
- **POO** - Programação Orientada a Objetos
- **Interfaces** - Para abstração do conversor
- **Scanner** - Para entrada de dados do usuário

## 📋 Funcionalidades Atuais

| Conversão | Descrição |
|-----------|-----------|
| USD → ARS | Dólar para Peso Argentino |
| ARS → USD | Peso Argentino para Dólar |
| USD → BRL | Dólar para Real Brasileiro |
| BRL → USD | Real Brasileiro para Dólar |
| USD → COP | Dólar para Peso Colombiano |
| COP → USD | Peso Colombiano para Dólar |

## 🚀 Estrutura do Projeto

```
src/
├── application/
│   └── Program.java          # Classe principal com menu interativo
├── model/
│   ├── entities/
│   │   └── ConversorAPIFinanceira.java  # Implementação do conversor
│   └── interfaces/
│       └── Conversor.java    # Interface para abstração
```

## 🔮 Próximos Passos

O projeto está preparado para evoluir com:
- ✅ Integração com API real de cotações (ExchangeRate-API, Fixer.io, etc.)
- ✅ Atualizações automáticas das taxas de câmbio
- ✅ Histórico de conversões
- ✅ Interface gráfica (JavaFX/Swing)

## 💡 Como Executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/currency-converter.git

# Compile e execute
javac Program.java
java Program
```

---

*Projeto educacional desenvolvido para demonstrar conceitos de Java, consumo de APIs externas e boas práticas de programação orientada a objetos.*
