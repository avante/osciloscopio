# Ficha Técnica – Sensor de Rotação de Entrada/Saída da Transmissão

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Transmissão / Controle Eletrônico de Trocas

---

## 1. Identificação
Sensores responsáveis por medir a rotação do eixo de entrada e do eixo de saída da transmissão, permitindo à ECU calcular a relação de marchas, controlar trocas e gerenciar o funcionamento do conversor de torque.

---

## 2. Descrição Geral
Esses sensores operam com base nos princípios do efeito Hall (ativo) ou indutivo (passivo), detectando a passagem de dentes em um disco reluctor acoplado ao eixo. A rotação de entrada é usada para medir a velocidade de rotação do motor no ponto de acoplamento com a transmissão. A de saída indica a velocidade da roda ou do eixo de saída.

---

## 3. Características Construtivas
- Sensor indutivo: bobina e ímã interno;
- Sensor Hall: circuito eletrônico alimentado com 5 ou 12 V;
- Conector de 2 ou 3 vias (sinal, alimentação e terra);
- Montagem na carcaça da transmissão próxima aos eixos;
- Corpo metálico ou plástico com resistência a óleo e temperatura.

---

## 4. Funções
- Determinar a relação de marchas utilizada;
- Controlar o momento e a firmeza da troca de marchas;
- Acionar e gerenciar o conversor de torque;
- Alimentar o sistema de controle de cruzeiro (piloto automático);
- Fornecer sinal de velocidade para o velocímetro (em alguns sistemas).

---

## 5. Interações Sistêmicas
- **TCM / ECU:** Usa os sinais para calcular torque, slip e trocas de marcha;
- **Solenoides da Transmissão:** Atuam com base nas rotações lidas;
- **Conversor de Torque:** Desacoplado ou bloqueado com base nas rotações;
- **Painel de Instrumentos:** Pode usar a rotação de saída para indicar velocidade;
- **Sistema ABS:** Comparações de velocidade de roda e de saída.

---

## 6. Defeitos Comuns
- Sensor sem sinal (aberto, curto ou danificado);
- Leitura intermitente ou errática;
- Encaixe incorreto ou folga entre sensor e reluctor;
- Acúmulo de limalha no sensor;
- Diferença incorreta entre entrada e saída (indica patinação).

---

## 7. Códigos DTC Associados (OBD-II)
- **P0715:** Sensor de rotação de entrada com falha;
- **P0720:** Sensor de rotação de saída com falha;
- **P0722:** Ausência de sinal do sensor de saída;
- **P0723:** Sinal intermitente do sensor de saída.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Forma de onda senoidal (sensor indutivo) ou digital (sensor Hall);
- Verificação da estabilidade e simetria dos pulsos;
- Comparação entre sensores de entrada e saída.

### Multímetro
- Medição de resistência (sensor indutivo);
- Medição de alimentação e retorno de sinal (sensor ativo);
- Verificação de continuidade do chicote.

### Scanner
- Leitura da rotação de entrada e saída em tempo real;
- Detecção de falhas de leitura ou incoerência entre sinais;
- Monitoramento da estratégia de troca de marchas.

---

## 9. Procedimentos de Diagnóstico
1. Identificar tipo de sensor (ativo ou passivo);
2. Verificar chicote, conectores e aterramentos;
3. Testar sensor com multímetro e/ou osciloscópio;
4. Monitorar sinais com scanner em aceleração e desaceleração;
5. Comparar leitura dos sensores com velocidade real do veículo.

---

## 10. Observações
- A falha nesses sensores pode causar troca de marcha errática, trancos, bloqueio de marcha ou entrada em modo de segurança;
- Motores mais modernos podem usar mais de um sensor por eixo para redundância.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

