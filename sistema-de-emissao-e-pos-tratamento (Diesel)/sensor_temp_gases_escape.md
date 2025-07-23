# Ficha Técnica – Sensor de Temperatura dos Gases de Escape

**Tipo:** Sensor  
**Aplicação:** Linha Pesada (P)  
**Categoria:** Sistema de Pós-Tratamento de Emissões (SCR / DPF)

---

## 1. Identificação
O sensor de temperatura dos gases de escape mede a temperatura dos gases no sistema de exaustão, sendo crucial para proteger os componentes do pós-tratamento, como o catalisador SCR, filtro DPF e o próprio sensor de NOx.

---

## 2. Descrição Geral
Instalado em pontos estratégicos do sistema de escape (pré-turbo, pré-DPF, pós-DPF e pós-SCR), esse sensor fornece à ECU informações térmicas para controlar o tempo de injeção de Arla 32 e estratégias de regeneração do filtro DPF.

---

## 3. Características Construtivas
- Sensor tipo termistor (NTC ou PTC) ou termoelétrico (termopar tipo K);
- Corpo metálico com rosca de fixação e proteção térmica;
- Conector elétrico de 2 a 4 vias;
- Fiação blindada resistente à alta temperatura;
- Faixa de medição: até 900 °C ou mais.

---

## 4. Funções
- Monitorar a temperatura dos gases para evitar danos térmicos;
- Controlar o momento e a dosagem do Arla 32 (SCR);
- Atuar na estratégia de regeneração do DPF;
- Proteger sensores e atuadores instalados no sistema de exaustão;
- Permitir estratégias de autodiagnóstico e desativação de segurança.

---

## 5. Interações Sistêmicas
- **ECU de motor e pós-tratamento:** Calcula a dosagem de reagentes;
- **Sensor de NOx:** Tem a leitura corrigida com base na temperatura;
- **Sistema de regeneração do DPF:** Aciona com base em limiares térmicos;
- **Sistema de proteção térmica:** Desativa componentes em caso de superaquecimento.

---

## 6. Defeitos Comuns
- Falha por superaquecimento ou curto interno;
- Leitura travada (valor fixo);
- Fios rompidos ou conector oxidado;
- Sensor fora de especificação térmica;
- Erro intermitente em condições severas.

---

## 7. Códigos DTC Associados (OBD-II)
- **P2031 / P2032 / P2033:** Sensor de temperatura de gases – banco 1;
- **P0544:** Sensor de temperatura exaustão A – circuito aberto;
- **P2471 / P2472:** Falha sensor pós-DPF;
- **U029D:** Comunicação ausente (sensores com módulo).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise da variação da resistência/tensão durante aquecimento;
- Verificação da resposta térmica em tempo real.

### Multímetro
- Medição da resistência do sensor (em frio e em aquecimento);
- Teste de continuidade e alimentação;
- Análise da variação de tensão em sensores termoelétricos.

### Scanner
- Leitura da temperatura dos gases em tempo real;
- Verificação da coerência com outros sensores e com o regime do motor;
- Monitoramento durante regeneração ou carga plena.

---

## 9. Procedimentos de Diagnóstico
1. Verificar valores no scanner sob diferentes cargas e rotações;
2. Comparar leituras entre sensores instalados em série;
3. Medir resistência e continuidade do chicote;
4. Verificar falhas térmicas ou danos físicos no sensor;
5. Substituir se leituras forem inconsistentes ou ausentes.

---

## 10. Observações
- Sensores termoelétricos produzem tensão (mV) conforme o calor;
- A falha pode afetar diretamente o consumo de Arla 32 ou a eficiência do DPF.

---

**Legenda:**  
P = Linha Pesada

