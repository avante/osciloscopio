# Ficha Técnica – Sensor de Temperatura do Combustível

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Alimentação e Combustível

---

## 1. Identificação
Sensor que mede a temperatura do combustível na linha de alimentação, geralmente instalado no rail ou junto ao módulo sensor de pressão, com influência direta na estratégia de injeção.

---

## 2. Descrição Geral
Trata-se de um sensor térmico, geralmente do tipo termistor NTC (Negative Temperature Coefficient), cuja resistência diminui à medida que a temperatura aumenta. A ECU interpreta esse sinal e aplica correções na mistura ar-combustível.

---

## 3. Características Construtivas
- Sensor encapsulado em corpo metálico ou plástico resistente a combustíveis;
- Elemento sensível: termistor NTC;
- Faixa de operação: -40 °C a +125 °C;
- Conector de 2 pinos (sinal e terra ou sinal e alimentação de 5 V);
- Pode estar embutido no sensor de pressão ou ser independente.

---

## 4. Funções
- Fornecer à ECU a temperatura real do combustível;
- Auxiliar na correção de densidade e tempo de injeção;
- Melhorar desempenho em condições de partida a frio;
- Atuar na prevenção de falhas por vaporização/cavitação do combustível.

---

## 5. Interações Sistêmicas
- **ECU:** Responsável por ajustar a estratégia de injeção com base na temperatura;
- **Sensor de Pressão do Combustível:** Atua em conjunto para evitar leituras erradas;
- **Bomba de Combustível:** Pode receber comandos de compensação térmica;
- **Sistema de partida a frio:** Em motores flex, pode usar esse sensor como referência.

---

## 6. Defeitos Comuns
- Sensor travado em um valor fixo;
- Curto circuito interno (resistência muito baixa);
- Circuito aberto (resistência infinita);
- Variação errática da leitura;
- Conector oxidado ou com mal contato.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0180:** Circuito do sensor de temperatura do combustível;
- **P0181:** Faixa/desempenho fora do esperado;
- **P0182:** Tensão baixa no circuito;
- **P0183:** Tensão alta no circuito.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Leitura analógica de variação suave conforme aquecimento;
- Permite observar oscilações anormais ou ruído elétrico;
- Tensão esperada: 0,5 V a 4,5 V (varia conforme resistência).

### Multímetro
- Medição de resistência do termistor (deve variar com temperatura);
- Valor típico: ~2,5 kΩ a 25 °C;
- Teste de continuidade no chicote e tensão de alimentação (5 V).

### Scanner
- Leitura em tempo real da temperatura do combustível;
- Comparar com temperatura ambiente e com a do motor em partida a frio;
- Leitura de DTCs e análise de coerência dos dados.

---

## 9. Procedimentos de Diagnóstico
1. Verificar no scanner a leitura do sensor com o motor frio (deve estar próxima da temperatura ambiente);
2. Aquecer o combustível (motor em funcionamento) e observar se a variação acompanha;
3. Medir a resistência do sensor e comparar com tabela do fabricante;
4. Verificar se há tensão de alimentação e integridade do chicote;
5. Observar sinais de contaminação, fissuras ou falhas no encapsulamento.

---

## 10. Observações
- Em motores flex, esse sensor tem papel importante na correção da injeção durante a transição de combustíveis;
- Falhas no sensor podem causar partidas difíceis, excesso de consumo ou falhas intermitentes em marcha lenta.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

