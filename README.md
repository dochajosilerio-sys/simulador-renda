# 📊 Simulador de Renda e Direitos Sociais v2.0

Este projeto é uma ferramenta de **Engenharia de Dados e Back-End** desenvolvida para fornecer clareza financeira e jurídica. O software calcula elegibilidade a benefícios sociais brasileiros e métricas de investimento imobiliário.

## 🛠️ Tecnologias e Ambiente
- **Linguagem:** Python 3.x
- **Ambiente de Desenvolvimento:** Termux (Android)
- **Versionamento:** Git & GitHub

## ⚖️ Regras de Negócio Implementadas
O software automatiza lógicas complexas baseadas na legislação vigente:
1. **BPC/LOAS:** Avalia a elegibilidade baseada na idade (65+), deficiência e no critério de renda per capita (1/4 do salário mínimo).
2. **Isenções Sociais:** Identifica o direito à isenção em taxas de concursos públicos para beneficiários do CadÚnico/Bolsa Família.
3. **Métrica de Investimento (ROI):** Calcula o Retorno sobre Investimento anual para projetos de construção e aluguel, auxiliando na tomada de decisão patrimonial.

## 🚀 Como Executar
No terminal (Linux/Termux/Windows):
```bash
python simulador_renda.py

