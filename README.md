# Alocação Ótima de Tarefas em Equipes Scrum

Este repositório contém a implementação do modelo de **Programação Linear Inteira** para otimizar a alocação de tarefas em equipes **Scrum**.

## Sobre o Projeto

O modelo considera simultaneamente:
- Capacidades individuais dos membros da equipe
- Durações das tarefas  
- Dependências entre tarefas
- Penalidades por alocação a não-especialistas

## Tecnologias

- **Python 3**
- **Gurobi 12.0.2** (via API gurobipy)

## Instalação

```bash
pip install gurobipy
```

> **Nota:** É necessário ter uma licença válida do Gurobi.

## Experimentos

O projeto inclui três experimentos principais:

1. **Capacidade Limitada** - Avalia priorização quando há escassez de recursos
2. **Especialização vs Capacidade** - Testa otimização com recursos abundantes  
3. **Restrições de Dependência** - Analisa impacto das dependências entre tarefas

## Autores

- André Prado Procopio
- Ana Amantea Leal Marques Afonso  
- Lucas Ribeiro da Silva
- Milena Terra Lopes
- Lucas S. Batista

**Universidade Federal de Minas Gerais (UFMG)**
