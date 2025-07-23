# Ficha Técnica – Bobina de Ignição

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Ignição

---

## 1. Identificação
Dispositivo responsável por transformar a tensão da bateria (12 V) em alta tensão (10 kV a 45 kV), necessária para gerar a centelha na vela de ignição.

---

## 2. Descrição Geral
A bobina de ignição é composta por enrolamentos primário e secundário, operando como um transformador. Pode ser do tipo convencional, dupla, caneta (COP – coil on plug) ou integrada ao módulo de ignição.

---

## 3. Características Construtivas
- Núcleo ferromagnético;
- Enrolamento primário (resistência baixa) e secundário (alta resistência);
- Isolamento de alta tensão;
- Corpo em resina epóxi ou termoplástico;
- Conector elétrico de 2 a 4 vias (alimentação, terra, comando);
- Conector de alta tensão para a vela (exceto nos sistemas COP).

---

## 4. Funções
- Gerar alta tensão necessária para a ignição da mistura ar-combustível;
- Atuar com precisão conforme o comando da ECU;
- Reduzir o tempo de carregamento (dwell time) e maximizar energia;
- Trabalhar em conjunto com o sistema de detecção de detonação.

---

## 5. Interações Sistêmicas
- **ECU:** Envia o comando de acionamento com base nos sinais de CKP e CMP;
- **Sensor de Detonação:** Pode retardar a ignição em caso de pré-detonação;
- **Vela de Ignição:** Recebe a centelha gerada;
- **Módulo de Ignição (quando presente):** Intermediário entre ECU e bobina.

---

## 6. Defeitos Comuns
- Isolamento rompido (fugas de corrente);
- Falhas em alta temperatura;
- Curto entre os enrolamentos;
- Centelha fraca ou ausente;
- Ruído eletromagnético excessivo (interferência).

---

## 7. Códigos DTC Associados (OBD-II)
- **P0350 a P0362:** Falha de circuito na bobina de ignição (códigos variam por cilindro);
- **P0300:** Falha de ignição aleatória;
- **P0301 a P0306:** Falha de ignição específica por cilindro;
- **P1300:** Diagnóstico de falha no sistema de ignição (fabricantes específicos).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Forma de onda de alta tensão (pico e duração da centelha);
- Verificação do tempo de carga e de queima (dwell e burn time);
- Análise de instabilidade ou falhas intermitentes.

### Multímetro
- Medição da resistência dos enrolamentos (primário e secundário);
- Teste de continuidade e fuga para o terra;
- Verificação de alimentação da bobina (12 V).

### Scanner
- Detecção de falhas de ignição por cilindro;
- Verificação de tempo de injeção e avanço;
- Leitura de parâmetros de correção em tempo real.

---

## 9. Procedimentos de Diagnóstico
1. Testar alimentação e sinal de comando no conector;
2. Verificar continuidade dos enrolamentos com multímetro;
3. Observar o padrão da centelha com osciloscópio;
4. Substituir por bobina conhecida em caso de falha intermitente;
5. Avaliar estado da vela e dos cabos para evitar retorno de alta tensão.

---

## 10. Observações
- O uso de bobinas fora da especificação pode causar falhas graves na ECU;
- Em sistemas COP, a falha pode ser confundida com problema no sensor de detonação ou na vela.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

