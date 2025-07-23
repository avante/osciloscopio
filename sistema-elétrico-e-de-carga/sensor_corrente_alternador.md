# Ficha Técnica – Sensor de Corrente do Alternador

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Carga / Monitoramento de Corrente

---

## 1. Identificação
O sensor de corrente do alternador mede a intensidade da corrente elétrica fornecida pelo alternador ao sistema elétrico do veículo e/ou à bateria, possibilitando o controle fino da carga e o diagnóstico de falhas.

---

## 2. Descrição Geral
Esse sensor pode ser do tipo resistivo (shunt) ou baseado em efeito Hall. Ele fornece um sinal proporcional à corrente que está sendo fornecida pelo alternador. A ECU usa esse dado para gerenciar o campo do alternador e proteger os componentes elétricos do veículo.

---

## 3. Características Construtivas
- Elemento resistivo (shunt) ou sensor de efeito Hall;
- Montagem sobre o cabo de alimentação do alternador (linha B+);
- Sinal de saída analógico ou digital (CAN/LIN);
- Conector com 3 vias típicas (alimentação, terra, sinal);
- Corpo plástico ou metálico com fixação por parafusos ou presilhas.

---

## 4. Funções
- Medir a corrente de carga fornecida pelo alternador;
- Detectar sobrecarga ou falhas de fornecimento;
- Permitir gerenciamento inteligente do sistema de carga;
- Auxiliar em estratégias de economia de combustível (via desativação do alternador);
- Suporte ao sistema start-stop.

---

## 5. Interações Sistêmicas
- **ECU / BCM:** Processam o sinal e ajustam o campo do alternador;
- **Regulador de tensão:** Atua conforme a demanda medida;
- **Sistema de gerenciamento térmico e elétrico:** Balanceamento de carga;
- **Painel de instrumentos:** Sinaliza falhas no sistema de carga.

---

## 6. Defeitos Comuns
- Falta de sinal por cabo rompido ou sensor queimado;
- Leituras erradas por mau contato ou interferência eletromagnética;
- Curto-circuito interno no sensor;
- Sensor deslocado da posição correta;
- Comunicação falha via LIN/CAN.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0620 a P0622:** Falhas no controle do alternador;
- **P2503:** Corrente de carga insuficiente;
- **U0121 / U0140:** Perda de comunicação com módulo de carga;
- **Códigos específicos de fabricante podem existir.**

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação do padrão de corrente alternada/contínua do sinal;
- Monitoramento de variações sob diferentes cargas elétricas.

### Multímetro
- Comparação entre leitura do scanner e corrente real medida com alicate amperímetro;
- Teste de alimentação e terra no conector do sensor;
- Continuidade dos cabos.

### Scanner
- Leitura da corrente de carga em tempo real;
- Análise de dados sob diferentes regimes de consumo;
- Presença de falhas no sistema de carga.

---

## 9. Procedimentos de Diagnóstico
1. Verificar conexão física e integridade do sensor;
2. Comparar dados de corrente entre scanner e alicate amperímetro;
3. Medir sinal de saída e alimentação com multímetro;
4. Avaliar atuação do regulador conforme a carga lida;
5. Substituir o sensor se os dados estiverem imprecisos ou ausentes.

---

## 10. Observações
- O sensor de corrente é essencial para eficiência energética em veículos modernos;
- Pode estar integrado ao conjunto de monitoramento da bateria em alguns modelos.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

