# Ficha Técnica – Atuador da Válvula EGR

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Controle de Emissões

---

## 1. Identificação
Atuador que comanda a abertura da válvula EGR (Exhaust Gas Recirculation), responsável por reintroduzir uma parte dos gases de escapamento na admissão para reduzir a formação de NOx.

---

## 2. Descrição Geral
A válvula EGR pode ser do tipo pneumática (atuada por vácuo), elétrica (com motor de passo ou solenoide), ou eletrônica com sensor de posição. A ECU comanda a válvula conforme a carga e a rotação do motor.

---

## 3. Características Construtivas
- Corpo metálico resistente a altas temperaturas;
- Passagem interna para os gases de escape;
- Atuador elétrico (motor de passo ou solenóide);
- Sensor de posição (em versões mais modernas);
- Conector elétrico de 4 a 6 pinos.

---

## 4. Funções
- Reduzir a temperatura de combustão para limitar emissão de óxidos de nitrogênio (NOx);
- Melhorar a eficiência térmica em regime de carga parcial;
- Reduzir picos de pressão e melhorar durabilidade do motor.

---

## 5. Interações Sistêmicas
- **ECU:** Controla a abertura da válvula de acordo com mapa de carga, rotação e temperatura;
- **Sensor MAP/MAF:** Usado para calcular a recirculação efetiva de gases;
- **Sensor de Temperatura dos Gases de Escape (EGT):** Auxilia na proteção térmica do sistema;
- **Sensor de Posição da Válvula EGR:** Feedback para controle preciso.

---

## 6. Defeitos Comuns
- Válvula travada aberta (marcha lenta irregular, engasgos);
- Válvula travada fechada (aumento de NOx);
- Acúmulo de fuligem ou carbonização dos dutos;
- Falha no motor de acionamento;
- Sensor de posição com leitura incorreta.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0400:** Fluxo de recirculação insuficiente;
- **P0401:** Fluxo insuficiente detectado;
- **P0402:** Fluxo excessivo detectado;
- **P0403:** Falha no circuito de controle da válvula EGR;
- **P0404:** Desempenho da válvula fora da faixa esperada;
- **P1406:** Sensor de posição da válvula EGR com falha.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal de controle PWM do atuador;
- Verificação da resposta do sensor de posição (forma de onda linear);
- Identificação de travamentos ou atraso na resposta.

### Multímetro
- Verificação de resistência da bobina ou motor de passo;
- Medição de tensão de alimentação e sinal de retorno;
- Continuidade do chicote.

### Scanner
- Leitura da posição da válvula EGR;
- Comando de atuadores (testar abertura/fechamento);
- Verificação de falhas DTC e parâmetros de recirculação em tempo real.

---

## 9. Procedimentos de Diagnóstico
1. Testar acionamento da válvula via scanner (modo atuador);
2. Observar os parâmetros de recirculação sob diferentes rotações;
3. Verificar a resistência ou impedância do motor/solenoide;
4. Realizar inspeção visual para detectar fuligem, entupimentos ou travamentos;
5. Comparar a posição real com a posição de comando (feedback).

---

## 10. Observações
- Sistemas modernos possuem válvula EGR refrigerada por líquido;
- A remoção da EGR (eliminação física) pode causar falhas no sistema de diagnóstico e aumento de emissões.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

