# Ficha Técnica – Eletroventilador do Radiador

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Arrefecimento / Controle de Temperatura do Motor

---

## 1. Identificação
Dispositivo responsável por forçar o fluxo de ar através do radiador, promovendo a troca térmica do líquido de arrefecimento, principalmente em baixa velocidade ou com o veículo parado.

---

## 2. Descrição Geral
O eletroventilador é composto por um motor elétrico (geralmente de 12 V), hélice plástica de alta resistência e estrutura de fixação. Pode operar em velocidade única ou múltipla (via resistores ou PWM), sendo acionado pela ECU com base na leitura do sensor ECT.

---

## 3. Características Construtivas
- Motor elétrico DC escovado ou brushless;
- Hélice de 5 a 11 pás, geralmente de material termoplástico;
- Chicote com relé, fusível e, em alguns casos, resistor de 1ª velocidade;
- Conector de 2 a 4 vias (alimentação, comando e terra);
- Montado em estrutura plástica junto ao radiador (shroud).

---

## 4. Funções
- Aumentar a eficiência do arrefecimento do motor;
- Reduzir a temperatura do líquido de arrefecimento;
- Atuar em conjunto com o ar-condicionado para troca térmica do condensador;
- Evitar superaquecimento em trânsito urbano e paradas prolongadas.

---

## 5. Interações Sistêmicas
- **Sensor ECT:** Fornece referência térmica para acionamento;
- **ECU:** Controla o relé ou módulo PWM do eletroventilador;
- **Sistema de Ar-condicionado:** Pode acionar o ventilador em baixa rotação;
- **Relés e resistores:** Controlam as diferentes velocidades.

---

## 6. Defeitos Comuns
- Motor travado por desgaste de escovas ou rolamentos;
- Fusível queimado ou relé com defeito;
- Mau contato nos terminais do conector;
- Resistor de 1ª velocidade aberto;
- Eletroventilador operando continuamente (sensor ECT com falha ou curto).

---

## 7. Códigos DTC Associados (OBD-II)
- **P0480 a P0485:** Falhas no circuito de controle do ventilador;
- **P0486:** Sinal incorreto de retorno do ventilador (em sistemas com feedback);
- **P0117 / P0118:** Falhas indiretas associadas ao sensor ECT.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal PWM em ventiladores de velocidade variável;
- Avaliação do acionamento por relé (forma de onda de comutação);
- Verificação de flutuação de tensão durante operação.

### Multímetro
- Medição da tensão no conector do ventilador;
- Teste de continuidade no motor, resistor e relé;
- Verificação de consumo de corrente (curto ou sobrecarga).

### Scanner
- Monitoramento da temperatura do motor;
- Verificação do comando de acionamento do ventilador;
- Teste de atuador (acionamento forçado).

---

## 9. Procedimentos de Diagnóstico
1. Observar se o ventilador é acionado ao atingir ~95 °C;
2. Verificar tensão no conector durante acionamento via scanner;
3. Testar o relé e fusíveis com multímetro;
4. Medir resistência do motor e continuidade do resistor de 1ª velocidade;
5. Avaliar o tempo de funcionamento pós-desligamento do motor (normal em alguns sistemas).

---

## 10. Observações
- A falha do eletroventilador é uma das principais causas de superaquecimento urbano;
- Em veículos com dois ventiladores, um pode atuar para o ar-condicionado e outro para o motor.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

