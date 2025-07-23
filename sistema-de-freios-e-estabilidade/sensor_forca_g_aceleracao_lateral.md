# Ficha Técnica – Sensor de Força G / Aceleração Lateral

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Estabilidade / Dinâmica Veicular

---

## 1. Identificação
O sensor de força G ou de aceleração lateral mede as forças de aceleração que atuam sobre o veículo nas curvas ou em mudanças bruscas de trajetória. É fundamental para o funcionamento do controle eletrônico de estabilidade (ESP).

---

## 2. Descrição Geral
Este sensor detecta aceleração lateral (e em alguns casos longitudinal e vertical) com base em elementos piezoelétricos, capacitivos ou MEMS (sistemas microeletromecânicos). Normalmente está instalado no centro de gravidade do veículo, embaixo do console ou do banco do motorista.

---

## 3. Características Construtivas
- Carcaça compacta e blindada contra vibrações e umidade;
- Elementos sensoriais de alta sensibilidade (MEMS);
- Comunicação via LIN, CAN ou PWM;
- Conector de 3 a 5 vias, dependendo da quantidade de eixos medidos;
- Fixação rígida ao chassi para precisão.

---

## 4. Funções
- Medir aceleração lateral do veículo durante curvas;
- Permitir a comparação entre trajetória desejada (ângulo do volante) e real;
- Atuar no controle do ESP, ABS e direção adaptativa;
- Suportar estratégias de assistência à condução (ADAS);
- Atuar no corte de torque do motor ou frenagem seletiva.

---

## 5. Interações Sistêmicas
- **Módulo ESP:** Utiliza o valor de força G para calcular o risco de derrapagem;
- **Sensor de ângulo do volante e velocidade da roda:** Correlacionam trajetória e comportamento do veículo;
- **ECU:** Pode reduzir torque do motor;
- **Sistemas ADAS:** Usam os dados para intervenções em curvas e frenagens.

---

## 6. Defeitos Comuns
- Leituras imprecisas por afrouxamento da fixação;
- Falha interna por umidade ou vibração excessiva;
- Erro de calibração após colisão ou substituição;
- Falha de comunicação com o módulo ESP;
- Ruído elétrico interferindo na leitura.

---

## 7. Códigos DTC Associados (OBD-II)
- **C0077 / C0176:** Falha no sensor de aceleração lateral;
- **U0121:** Perda de comunicação com o módulo de estabilidade;
- **C1A96 / C1A97:** Falhas específicas do sensor de força G;
- Demais códigos dependem do fabricante.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise de variação do sinal com movimento lateral simulado;
- Verificação de ruídos ou falhas de resposta.

### Multímetro
- Medição de tensão de alimentação e sinal em repouso;
- Continuidade dos terminais de comunicação e terra.

### Scanner
- Leitura do valor de aceleração lateral em tempo real;
- Verificação de plausibilidade com manobras controladas;
- Reset/calibração do sensor quando necessário.

---

## 9. Procedimentos de Diagnóstico
1. Verificar fixação correta do sensor ao chassi;
2. Medir alimentação e sinal com multímetro;
3. Simular curva e comparar variação com dados do scanner;
4. Observar resposta do veículo no ESP com sensor desconectado;
5. Substituir sensor se apresentar dados imprecisos ou ruído constante.

---

## 10. Observações
- Em muitos casos o sensor é combinado com giroscópio (sensor de yaw rate);
- A calibração do sensor é essencial após reparos na suspensão ou colisão.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

