# Ficha Técnica – Sensor de Fluxo de Ar (MAF)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Admissão de Ar / Controle de Mistura

---

## 1. Identificação
Sensor responsável por medir diretamente a massa de ar que entra no motor, permitindo que a ECU calcule a quantidade exata de combustível a ser injetada para manter a mistura ar-combustível ideal.

---

## 2. Descrição Geral
O sensor MAF (Mass Air Flow) utiliza elementos sensores de filme quente (hot wire) ou filme frio, que aquecem um fio resistivo e medem a variação de corrente necessária para manter sua temperatura constante, proporcional ao fluxo de ar que passa por ele.

---

## 3. Características Construtivas
- Corpo plástico com canal de medição de fluxo;
- Elemento sensor (hot wire ou hot film) encapsulado;
- Tela ou grade de fluxo para laminar a passagem do ar;
- Conector de 3 a 5 vias (alimentação, sinal, terra, sensor de temperatura IAT incorporado em alguns casos);
- Montagem entre o filtro de ar e o corpo de borboleta.

---

## 4. Funções
- Medir a massa de ar que entra no motor em tempo real;
- Auxiliar no cálculo da carga do motor;
- Ajustar o tempo e quantidade de injeção de combustível;
- Corrigir a mistura com base em altitude, temperatura e condições ambientais.

---

## 5. Interações Sistêmicas
- **ECU:** Utiliza o sinal do MAF para controlar injeção e ignição;
- **Sensor IAT:** Em alguns sistemas, é integrado ao MAF;
- **Sensor de O2 (Sonda Lambda):** Corrige a mistura baseada na leitura do MAF;
- **Sistema EGR:** Pode ajustar recirculação conforme fluxo de ar medido.

---

## 6. Defeitos Comuns
- Contaminação do fio sensor (óleo, sujeira, poeira);
- Leitura incorreta por dano no sensor ou entrada falsa de ar;
- Curto ou circuito aberto no chicote;
- Leitura congelada (valor fixo);
- Sensor do tipo hot wire com elemento rompido.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0100:** Circuito do sensor MAF;
- **P0101:** Faixa/desempenho fora do esperado;
- **P0102:** Tensão baixa (fluxo de ar insuficiente);
- **P0103:** Tensão alta (fluxo de ar excessivo);
- **P0104:** Intermitência no sinal.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal de saída (geralmente analógico ou frequência PWM);
- Verificação de resposta sob diferentes rotações e cargas;
- Forma de onda contínua, estável e progressiva.

### Multímetro
- Verificação da alimentação (geralmente 5 V ou 12 V);
- Medição da tensão de sinal (0,5 a 4,5 V típica);
- Teste de continuidade e resistência do chicote.

### Scanner
- Leitura do fluxo de ar em g/s (gramas por segundo);
- Comparação com valores esperados por rotação;
- Teste de correlação com MAP e TPS (em sistemas redundantes);
- Leitura de falhas DTC relacionadas.

---

## 9. Procedimentos de Diagnóstico
1. Observar se a leitura varia com aceleração no scanner;
2. Comparar fluxo com curvas padrão do fabricante;
3. Limpar o elemento sensor com spray apropriado (sem tocar fisicamente);
4. Medir tensão de alimentação e sinal em tempo real;
5. Verificar presença de ar falso (falsas entradas após o sensor).

---

## 10. Observações
- A limpeza inadequada pode danificar permanentemente o sensor;
- Em alguns sistemas, a ausência do MAF pode levar ao uso de estratégia fallback com base no MAP e TPS (modo de emergência).

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

