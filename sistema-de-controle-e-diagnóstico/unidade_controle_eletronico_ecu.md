# Ficha Técnica – Unidade de Controle Eletrônico (ECU / ECM / PCM)

**Tipo:** Atuador/Sensor Lógico  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Controle / Estratégia / Diagnóstico

---

## 1. Identificação
A ECU (Engine Control Unit), ECM (Engine Control Module) ou PCM (Powertrain Control Module) é a unidade central de processamento responsável por gerenciar o funcionamento do motor, transmissão e outros subsistemas por meio da leitura de sensores e controle de atuadores.

---

## 2. Descrição Geral
Trata-se de um módulo eletrônico com microprocessador, memória e circuitos integrados, que processa sinais de diversos sensores e comanda atuadores conforme mapas e algoritmos programados. Pode haver uma unidade para o motor e outra para a transmissão, ou uma unidade integrada para todo o trem de força.

---

## 3. Características Construtivas
- Placa eletrônica com processador, conversores A/D e memória;
- Carcaça metálica com dissipação térmica;
- Conectores múltiplos (até 120 vias ou mais);
- Interface de comunicação (CAN, LIN, K-Line);
- Montagem em compartimento protegido (cofre ou painel);
- Proteção contra vibração, umidade e EMI.

---

## 4. Funções
- Gerenciar tempo de injeção e ignição;
- Controlar marcha lenta, turbo, EGR, VVT, etc.;
- Acionar bomba de combustível, bobinas, eletroventilador;
- Diagnosticar falhas e armazenar códigos DTC;
- Gerar estratégias de emergência e adaptação;
- Comunicar com scanner e módulos auxiliares.

---

## 5. Interações Sistêmicas
- **Sensores:** Fornecem entradas críticas (MAP, MAF, TPS, CKP, etc.);
- **Atuadores:** São comandados com base em lógica interna;
- **Painel de instrumentos:** Recebe dados processados;
- **Módulos auxiliares (ABS, TCM, BCM):** Comunicação e sincronia;
- **Scanner automotivo:** Interação via OBD-II para diagnóstico.

---

## 6. Defeitos Comuns
- Falha de comunicação com periféricos;
- Processamento incorreto por falha de software;
- Mau contato nos conectores (oxidação);
- Dano por sobretensão ou inversão de polaridade;
- Falha de memória EEPROM.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0600 a P0606:** Falhas internas na ECU;
- **U0100:** Perda de comunicação com ECU principal;
- **P0650:** Falha no controle da luz de injeção;
- Outros diversos, pois a ECU gerencia todos os subsistemas.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Diagnóstico indireto por análise de sinais gerados pela ECU;
- Avaliação de comunicação CAN, PWM e sinais de sensores;
- Detecção de ruídos e interferências.

### Multímetro
- Verificação de alimentação (12 V, 5 V) e aterramento;
- Continuidade e resistência de trilhas (quando acessível);
- Teste de sinais básicos como TPS e CKP no conector.

### Scanner
- Acesso a dados em tempo real;
- Leitura e limpeza de DTCs;
- Programação, codificação e reset de adaptações;
- Atualizações de software (flash).

---

## 9. Procedimentos de Diagnóstico
1. Verificar alimentação e aterramento adequados;
2. Avaliar comunicação com scanner e demais módulos;
3. Conferir DTCs ativos e parâmetros incoerentes;
4. Revisar chicotes e conectores com teste de continuidade;
5. Se necessário, reprogramar ou substituir o módulo.

---

## 10. Observações
- A substituição da ECU pode exigir codificação de chaves, imobilizador e adaptações;
- A variação de nomenclatura (ECU, ECM, PCM) depende do fabricante.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

