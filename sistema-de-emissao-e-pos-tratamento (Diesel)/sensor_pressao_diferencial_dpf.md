# Ficha Técnica – Sensor de Pressão Diferencial do Filtro DPF

**Tipo:** Sensor  
**Aplicação:** Linha Pesada (P)  
**Categoria:** Sistema de Pós-Tratamento de Emissões (DPF)

---

## 1. Identificação
O sensor de pressão diferencial do DPF (filtro de partículas diesel) mede a diferença de pressão entre a entrada e a saída do filtro, permitindo à ECU monitorar o grau de entupimento e controlar o processo de regeneração.

---

## 2. Descrição Geral
O sensor é conectado por duas mangueiras ao início e ao fim do filtro DPF, detectando a diferença de pressão provocada pelo acúmulo de fuligem. A ECU interpreta esse sinal para acionar a regeneração ativa, passiva ou forçada do filtro.

---

## 3. Características Construtivas
- Corpo compacto com dois bocais para mangueiras de pressão;
- Sensor piezoresistivo ou capacitivo de alta precisão;
- Conector de 3 vias (alimentação, terra e sinal);
- Comunicação analógica (tensão) ou digital (CAN);
- Faixa de medição: geralmente de 0 a 100 kPa.

---

## 4. Funções
- Detectar o nível de entupimento do DPF;
- Permitir o acionamento da regeneração quando necessário;
- Prevenir danos ao motor e ao sistema de escape;
- Identificar falhas como entupimento severo ou vazamentos;
- Monitorar a eficiência do processo de queima da fuligem.

---

## 5. Interações Sistêmicas
- **ECU de motor:** Aciona e gerencia o ciclo de regeneração;
- **Sensor de temperatura dos gases:** Auxilia na estratégia térmica da regeneração;
- **Sistema de injeção:** Pode ser ajustado para elevar temperatura de escape;
- **Sensor de fluxo de ar:** Complementa o diagnóstico do DPF.

---

## 6. Defeitos Comuns
- Obstrução ou rompimento das mangueiras de pressão;
- Vazamentos nas conexões do sensor;
- Sensor com leitura travada ou fora da faixa;
- Acúmulo de condensado dentro do sensor;
- Falha elétrica (alimentação, sinal ou comunicação).

---

## 7. Códigos DTC Associados (OBD-II)
- **P2452 / P2453 / P2454:** Sensor de pressão diferencial – falha de sinal;
- **P2002:** Eficiência do DPF abaixo do limiar;
- **P2463:** Acúmulo excessivo de fuligem no DPF;
- **U029D:** Perda de comunicação com o sensor (quando digital).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação da variação do sinal com o motor em diferentes cargas;
- Análise da resposta dinâmica ao acelerar.

### Multímetro
- Medição da tensão do sinal (faixa comum: 0,5 a 4,5 V);
- Teste da alimentação (5 V ou 12 V) e aterramento;
- Continuidade dos fios.

### Scanner
- Leitura da pressão diferencial em kPa ou mbar;
- Acompanhamento durante ciclos de regeneração;
- Reset de falhas e dados de fuligem acumulada.

---

## 9. Procedimentos de Diagnóstico
1. Verificar integridade das mangueiras e conexões;
2. Medir tensão de alimentação e resposta de sinal;
3. Comparar leitura com valores esperados em marcha lenta e sob carga;
4. Realizar limpeza ou substituição em caso de entupimento;
5. Resetar a memória do DPF após substituição ou regeneração.

---

## 10. Observações
- O entupimento do DPF pode causar aumento de consumo e perda de potência;
- A regeneração ineficaz pode gerar falhas recorrentes no sensor.

---

**Legenda:**  
P = Linha Pesada

