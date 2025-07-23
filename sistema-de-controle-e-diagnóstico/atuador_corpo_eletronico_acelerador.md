# Ficha Técnica – Atuador de Corpo Eletrônico de Acelerador

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Admissão / Controle Eletrônico de Aceleração

---

## 1. Identificação
O atuador do corpo eletrônico de acelerador substitui o cabo mecânico e realiza o controle da borboleta de admissão de ar por comando eletrônico da ECU, com base na posição do pedal do acelerador.

---

## 2. Descrição Geral
O sistema é composto por um motor elétrico, sensores de posição da borboleta e retorno eletrônico. A ECU calcula, com base em diversos parâmetros, a posição ideal da borboleta e comanda o motor elétrico para movê-la. Trata-se de um componente crítico do sistema drive-by-wire.

---

## 3. Características Construtivas
- Corpo em alumínio ou plástico com canal de ar;
- Motor elétrico DC interno com engrenagens de redução;
- Duplo sensor de posição (TPS redundante);
- Retorno por mola para posição de segurança (fail-safe);
- Conector elétrico com múltiplas vias;
- Possui fusível e proteção contra curto.

---

## 4. Funções
- Controlar a entrada de ar no motor conforme a demanda do condutor;
- Corrigir rotação em marcha lenta e situações de carga;
- Implementar controle de tração e estabilidade (via ECU);
- Ajudar no controle do freio-motor;
- Permitir estratégias de segurança (modo de emergência).

---

## 5. Interações Sistêmicas
- **ECU:** Comanda a posição da borboleta via PWM;
- **Sensor APP (pedal do acelerador):** Informa a demanda do condutor;
- **Sensores de temperatura, rotação e carga:** Corrigem a posição ideal;
- **Sistema de controle de tração e freio ABS:** Interagem para reduzir torque.

---

## 6. Defeitos Comuns
- Acúmulo de sujeira impede fechamento completo;
- Engrenagens desgastadas ou motor com falha;
- Sensor de posição da borboleta com leitura errada;
- Falha na calibração ou adaptação da borboleta;
- Interrupção da alimentação elétrica.

---

## 7. Códigos DTC Associados (OBD-II)
- **P2101 a P2104:** Problemas no circuito do atuador ou range de operação;
- **P2111 / P2112:** Borboleta travada aberta ou fechada;
- **P0120 a P0123:** Falhas nos sensores de posição da borboleta;
- **P0638:** Desempenho do atuador fora de especificação.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Monitoramento da resposta dos sensores TPS A e B;
- Forma de onda do sinal PWM do motor;
- Verificação da sincronia entre comando e resposta.

### Multímetro
- Medição de resistência do motor e sensores;
- Verificação de alimentação (geralmente 5 V e 12 V);
- Continuidade do chicote e aterramentos.

### Scanner
- Teste funcional da borboleta (abertura/fechamento);
- Leitura dos sensores TPS em tempo real;
- Reset de adaptação da borboleta.

---

## 9. Procedimentos de Diagnóstico
1. Verificar o estado físico e limpeza do corpo;
2. Usar scanner para teste funcional e reset de adaptação;
3. Medir sinais do motor e sensores com multímetro/osciloscópio;
4. Avaliar fusíveis e continuidade do chicote;
5. Realizar aprendizado automático da borboleta (quando aplicável).

---

## 10. Observações
- A borboleta pode operar em modo de segurança com rotação limitada;
- A substituição exige aprendizado da nova posição com scanner.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

