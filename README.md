# Programação Matemática (GCC118)
## Universidade Federal de Lavras (UFLA)
### Instituto de Ciências Exatas e Tecnológicas

Este repositório contém soluções para problemas de programação matemática desenvolvidos no curso de GCC118. Cada notebook aborda um problema distinto, com aplicações práticas de otimização.

---

## Problemas

### 1. `problema1.ipynb`: Otimização de Produção em uma Empresa de Relógios
**Descrição**: Este problema busca maximizar o lucro semanal de uma empresa que fabrica dois tipos de relógios: pedestal e parede. Cada sócio (João, Ana e Lídia) contribui com uma quantidade limitada de horas semanais, e o problema requer determinar a quantidade ideal de cada tipo de relógio a ser produzido.

- **Objetivo**: Maximizar o lucro total.
- **Restrições**:
  - Limitação de horas disponíveis para cada sócio.
  - Restrição de não negatividade nas quantidades produzidas.
- **Ferramenta utilizada**: `gurobipy` para resolver o modelo de programação linear.

---

### 2. `problema2.ipynb`: Maximização de Fluxo em uma Empresa Transportadora
**Descrição**: Este problema modela o transporte de óleo entre estações usando um grafo. A tarefa é maximizar o número de barris transportados por dia, considerando as capacidades máximas de cada trecho.

- **Objetivo**: Maximizar o fluxo de óleo da estação de origem ($A$) até a estação de destino ($B$).
- **Restrições**:
  - Limitações nas capacidades de transporte de cada trecho.
  - Conservação de fluxo em cada estação intermediária.
- **Ferramenta utilizada**: `gurobipy` para resolver o problema como um modelo de fluxo máximo.

---

### 3. `problema3.ipynb`: Otimização de Dieta
**Descrição**: Este problema modela a escolha de alimentos para compor uma dieta com custo mínimo, garantindo que todas as necessidades nutricionais sejam atendidas. Restrições adicionais limitam as quantidades mínimas e máximas permitidas para cada alimento.

- **Objetivo**: Minimizar o custo total da dieta.
- **Restrições**:
  - Cada nutriente deve atender ao valor diário recomendado (VDR).
  - As quantidades dos alimentos devem estar dentro dos limites permitidos.
- **Ferramenta utilizada**: `gurobipy` para resolver o problema como um modelo de programação linear.

---

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Navegue até o diretório:
   ```bash
   cd seu-repositorio
   ```
3. Abra os notebooks no Jupyter:
   ```bash
   jupyter notebook
   ```

---

## Requisitos

- Python 3.8 ou superior
- Jupyter Notebook
- Biblioteca necessária: `gurobipy` (instale com `pip install gurobipy`)

---

## Contribuidores

- **Ranulfo Mascari Neto**
- **Heitor Rodrigues Sabino**
