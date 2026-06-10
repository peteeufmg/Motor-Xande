# ⚙️ Motor DC – Protótipo Didático

Este protótipo de motor DC de corrente contínua faz parte da proposta de projeto calouros e visa o enriquecimento e melhoria do acervo no âmbito da iniciativa **PETEE Protótipos (UFMG)**. Como proposta inicial, será desenvolvido um protótipo voltado à experimentação em Máquinas Elétricas, aplicável em disciplinas e oficinas de extensão. O modelo consiste em um motor DC funcional, permitindo estudar os princípios fundamentais de eletromagnetismo, conversão eletromecânica de energia e controle de velocidade.

---

## 📌 Objetivo do Protótipo e Documentação

- Demonstrar uma documentação **didática, funcional, completa e de fácil edição**.
- Evidenciar a importância em separar documentação técnica e relatório científico.
- Produzir um protótipo acessível para estudantes e que diversifique o acervo do PETEE.
- Apoiar atividades de ensino e extensão com um material prático e interativo.
- Permitir experimentação com conceitos de torque, velocidade, rendimento e controle de motor.

---

## ⚡ Especificações – Motor DC

| Categoria | Especificação |
|-----------|--------------|
| **Tensão nominal (Vcc)** | 3 V a 12 V (típico 6 V / 9 V / 12 V) |
| **Corrente nominal** | 0.5 A a 2.0 A (dependendo da carga) |
| **Potência máxima** | ~15 W (em 12 V) |
| **RPM (sem carga)** | ~3000 – 7000 RPM (dependendo da tensão) |
| **Torque máximo** | ~0.3 – 0.5 N·m |
| **Tipo de escova** | Carbono (grafite) |
| **Tipo de rotor** | Bobinado (armadura) |
| **Temperatura de operação** | –10 °C a +60 °C |
| **Peso** | ~50 – 100 g |

### Características Elétricas

| Parâmetro | Especificação |
|-----------|--------------|
| **Resistência da armadura** | ~10 – 30 Ω |
| **Constante de velocidade (Kv)** | ~500 – 1000 RPM/V |
| **Constante de torque (Kt)** | ~0.01 – 0.05 N·m/A |
| **Eficiência nominal** | ~60 – 75% |

### Consumo de Corrente

| Condição | Corrente |
|----------|----------|
| **Sem carga** | ~0.1 – 0.3 A |
| **Carga nominal** | ~0.5 – 1.5 A |
| **Carga máxima** | ~2.0 A |

---

## 🧰 Materiais Usados

| Referência | Quantidade | Valor / Modelo | Descrição | Datasheet |
|-----------|-----------|----------------|-----------|-----------|
| MOT01 | 1 | Motor DC 12V | Motor DC com escova de carbono | [PDF](#) |
| CML01 | 1 | Comutador de 2/3 segmentos | Sistema de comutação com escovas | [PDF](#) |
| RET01 | 2 | Rolamento radial 6mm | Suporte do eixo do rotor | [PDF](#) |
| ARD01 | 1 | Arduino UNO / Microcontrolador | Controle de PWM | [PDF](#) |
| DRV01 | 1 | L298N / Ponte-H | Driver de potência | [PDF](#) |
| BT01 | 1 | Bateria 12V / 1500mAh | Alimentação principal | [PDF](#) |
| POT01 | 1 | Potenciômetro 10kΩ | Controle de velocidade | [PDF](#) |
| LED01 | 2 | LED 5mm | Indicadores de estado | [PDF](#) |
| RES01 | 4 | Resistor 220Ω / 10kΩ | Circuito de proteção | [PDF](#) |
| CONC01 | 1 | Conjunto de conectores | Ligações rápidas | [PDF](#) |

---

## 📐 Esquemáticos

- **Esquemático Principal** – Ligação do motor com driver e microcontrolador
- **Esquemático de Potência** – Circuito de alimentação e proteção
- **Footprint e Layout** – PCB com dimensões otimizadas

---

## 🖼️ Modelos 3D

### Estrutura Mecânica

- 📂 [Arquivos de suporte e acoplamento (STL/STEP)](./3d_models)
- **Suporte do motor** – Fixação e alinhamento
- **Acoplamento do eixo** – Adaptadores e polias
- **Base da estrutura** – Suporte estrutural

### Montagem Visual

- **Modelo Frontal** – Vista frontal da montagem
- **Modelo de Fundo** – Vista traseira e detalhes de conexão
- **Modelo Explodido** – Visualização das peças e assemblagem

---

## 🎥 Mídia

- **Vídeo 1 – Visão Geral da Montagem** – [Link](#)
- **Vídeo 2 – Motor em Funcionamento** – [Link](#)
- **Vídeo 3 – Teste de Controle PWM** – [Link](#)
- **Vídeo 4 – Análise de Velocidade e Torque** – [Link](#)

---

## 🛠️ Processo de Produção

1. **Definição de requisitos** (tensão, potência, velocidade, aplicações).
2. **Seleção de componentes** e especificações do motor DC.
3. **Projeto do circuito de controle** (driver, PWM, proteção).
4. **Design da estrutura mecânica** (suportes, acoplamentos).
5. **Prototipagem e montagem** em breadboard / PCB.
6. **Testes de desempenho** (velocidade, torque, consumo, eficiência).
7. **Calibração e validação** dos controles.
8. **Documentação e publicação** no GitHub.

---

## 📚 Referências

- **Chapman, S. J.** – *Máquinas Elétricas* (Electric Machinery Fundamentals).
- **Fitzgerald, A. E. et al.** – *Máquinas Elétricas com Introdução à Eletrônica de Potência*.
- **Arduino Official Documentation** – PWM, Analog I/O, Serial Communication.
- **L298N Motor Driver Datasheet** – Especificações e aplicações.
- **Tutoriais RF** – AllAboutCircuits, EEVBlog, Arduino Official Tutorials.
- **Documentação interna PETEE** – Padrões de documentação e protótipos anteriores.

---

## 👥 Equipe

- **Instituição:** PETEE – UFMG (Programa de Educação Tutorial em Engenharia Elétrica)
- **Petiano Responsável:** *[Nome do Responsável]*
- **Tutor:** *[Nome do Professor Tutor]*
- **Data de Início:** Junho/2026

---

## 📝 Documentação Complementar

- **Relatório Técnico** – [Link para documento]
- **Manual de Uso** – [Link para guia prático]
- **Guia de Manutenção** – [Link para manutenção]

---

## 📢 Licença

Projeto aberto para fins didáticos e educacionais. Cite **PETEE – UFMG** ao utilizar este protótipo ou sua documentação.

---

**Última atualização:** Junho 2026  
**Status do Projeto:** Em desenvolvimento ⚙️