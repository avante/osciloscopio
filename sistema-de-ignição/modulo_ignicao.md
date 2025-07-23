# Ficha Técnica – Módulo de Ignição

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Ignição / Comando de Centelha

---

## 1. Identificação
Unidade eletrônica responsável por controlar o tempo de acionamento das bobinas de ignição com base no sinal da ECU ou sensores de rotação, determinando o momento exato da centelha.

---

## 2. Descrição Geral
O módulo de ignição recebe sinais do CKP e CMP (ou da ECU) e determina o dwell (tempo de carga da bobina) e o disparo da centelha. Em alguns sistemas, está incorporado à bobina; em outros, é um componente separado.

---

## 3. Características Construtivas
- Circuito eletrônico encapsulado em resina térmica;
- Dissipador de calor integrado (para alta durabilidade);
- Conectores de entrada (sinais e alimentação) e saída para bobinas;
- Entrada de sinal de disparo (pulsos digitais);
- Pode ser digital (com comunicação com ECU) ou analógico (sinal de sensor indutivo).

---

## 4. Funções
- Comandar o tempo de carga (dwell) e o momento de disparo da centelha;
- Garantir energia adequada na bobina em todas as rotações;
- Trabalhar em conjunto com o sistema de detonação e sensor de rotação;
- Eliminar falhas por sobreaquecimento ou excesso de carga.

---

## 5. Interações Sistêmicas
- **Sensor CKP/CMP:** Fornecem dados de posição e rotação;
- **ECU:** Pode comandar diretamente ou de forma indireta o módulo;
- **Bobinas de Ignição:** São acionadas com base no sinal do módulo;
- **Sensor de Detonação:** Pode ajustar o tempo de disparo via ECU.

---

## 6. Defeitos Comuns
- Ausência de centelha (módulo queimado);
- Centelha fraca por tempo de dwell incorreto;
- Comando intermitente (sinal corrompido);
- Ruído elétrico induzido nos sinais;
- Falha por sobreaquecimento ou falha de aterramento.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0350 a P0362:** Falhas em circuitos de ignição (variam conforme cilindro);
- **P1320:** Falha de módulo de ignição (Nissan, Mitsubishi, outros);
- **P1300:** Diagnóstico geral de falha de ignição;
- **P2300 a P2308:** Circuito primário da ignição com falha.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação do pulso de disparo para a bobina;
- Análise de falhas intermitentes ou distorções de forma de onda;
- Avaliação do tempo de dwell e da coerência do disparo.

### Multímetro
- Teste de alimentação e aterramento;
- Verificação de continuidade nos circuitos de entrada e saída;
- Avaliação de sinais PWM (em modo leitura rápida).

### Scanner
- Leitura de falhas de ignição;
- Teste de atuadores (em módulos inteligentes);
- Correlação entre avanço de ignição e comando do módulo.

---

## 9. Procedimentos de Diagnóstico
1. Medir alimentação e terra no conector do módulo;
2. Verificar integridade dos sinais de entrada e saída com osciloscópio;
3. Confirmar tempo de dwell e disparo sob carga;
4. Testar continuidade até a bobina de ignição;
5. Substituir por módulo conhecido em caso de dúvida.

---

## 10. Observações
- Módulos que operam sem dissipador térmico adequado tendem a falhar por calor;
- Alguns sistemas integraram o módulo à própria ECU ou bobina para simplificar o circuito.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

