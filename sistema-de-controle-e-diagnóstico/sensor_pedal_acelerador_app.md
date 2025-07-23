# Ficha Técnica – Sensor de Pedal do Acelerador (APP)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Admissão / Aceleração Eletrônica

---

## 1. Identificação
O sensor de pedal do acelerador (APP – Accelerator Pedal Position) converte a posição do pedal em sinais elétricos que indicam à ECU a intenção de aceleração do condutor, substituindo o cabo de acelerador mecânico.

---

## 2. Descrição Geral
É composto geralmente por dois sensores internos (TPS A e B) que operam de forma redundante para segurança. Os sinais enviados variam conforme o ângulo de inclinação do pedal. A ECU utiliza essas informações para controlar a borboleta eletrônica e o fornecimento de combustível.

---

## 3. Características Construtivas
- Módulo fixado ao pedal ou ao suporte;
- Dois sensores de posição tipo potenciômetro ou Hall;
- Retorno por mola para posição de repouso;
- Conector elétrico com 5 ou 6 vias;
- Corpo em termoplástico resistente a vibração.

---

## 4. Funções
- Informar a demanda de torque do condutor;
- Comandar a posição da borboleta eletrônica;
- Permitir estratégias de controle de tração e torque;
- Operar em redundância para segurança contra falhas;
- Auxiliar no controle de emissões e economia.

---

## 5. Interações Sistêmicas
- **ECU:** Interpreta sinais A e B e controla o motor;
- **Corpo eletrônico do acelerador:** Atua segundo os sinais recebidos;
- **Sistemas de ABS e tração:** Podem limitar a resposta do pedal;
- **Controle de cruzeiro:** Usa o sinal do pedal para retomar velocidade.

---

## 6. Defeitos Comuns
- Falha em um ou ambos sensores (potenciômetro);
- Sinais A e B fora de sincronia (falha de redundância);
- Chicote rompido ou oxidado;
- Posição errática ou pedal travando;
- Mal funcionamento por retorno mecânico danificado.

---

## 7. Códigos DTC Associados (OBD-II)
- **P2122 a P2129:** Falhas em sensores de posição do pedal;
- **P2138:** Correlação incorreta entre os sinais A e B;
- **P0641 / P0651:** Falha em linha de alimentação de sensor;
- **P2100+:** Códigos relacionados ao drive-by-wire.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação da linearidade dos sinais A e B durante curso do pedal;
- Comparação dos sinais simultâneos para validar correlação;
- Identificação de falhas intermitentes (pulsos ou quedas).

### Multímetro
- Medição da tensão de saída dos sensores (geralmente 0,5 a 4,5 V);
- Verificação da alimentação de 5 V e terra;
- Continuidade do chicote.

### Scanner
- Leitura dos dois sinais de posição em tempo real;
- Verificação de falhas presentes e armazenadas;
- Teste funcional com acionamento do pedal.

---

## 9. Procedimentos de Diagnóstico
1. Verificar alimentação de 5 V e sinal de terra;
2. Medir sinais A e B com multímetro ou osciloscópio;
3. Comparar sinais quanto à linearidade e sincronismo;
4. Realizar teste com scanner em marcha lenta e aceleração parcial;
5. Substituir o sensor em caso de falha de redundância.

---

## 10. Observações
- É comum que o APP opere em modo de segurança quando há erro de sinal;
- Alguns veículos exigem aprendizado de posição do pedal após troca.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

