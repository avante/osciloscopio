# Ficha Técnica – Sensor de Velocidade da Roda

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Freios / ABS / Controle de Tração e Estabilidade

---

## 1. Identificação
Sensor responsável por medir a rotação individual de cada roda, fundamental para o funcionamento de sistemas como ABS, controle de tração (TCS), controle de estabilidade (ESP) e transmissão automática.

---

## 2. Descrição Geral
O sensor de velocidade da roda pode ser do tipo indutivo (passivo) ou do tipo Hall (ativo). Ele mede a variação do campo magnético causado pela passagem dos dentes da roda fônica (ou reluctora) acoplada ao cubo da roda, gerando um sinal elétrico proporcional à velocidade de rotação.

---

## 3. Características Construtivas
- Sensor passivo: bobina e ímã permanente;
- Sensor ativo: circuito eletrônico com alimentação e saída digital;
- Corpo plástico ou metálico resistente a calor e umidade;
- Conector de 2 (passivo) ou 3 vias (ativo);
- Montagem próxima ao cubo da roda ou eixo.

---

## 4. Funções
- Informar a rotação da roda para o sistema ABS;
- Auxiliar no cálculo da velocidade real do veículo;
- Atuar no controle de tração e estabilidade;
- Prover dados para o módulo da transmissão e piloto automático;
- Base para estratégia de frenagem regenerativa (veículos híbridos/elétricos).

---

## 5. Interações Sistêmicas
- **Módulo ABS/ESP:** Responsável por interpretar os sinais de velocidade;
- **ECU:** Pode ajustar estratégias de torque e ignição;
- **Transmissão Automática:** Adapta marchas conforme a velocidade;
- **Painel de Instrumentos:** Exibe a velocidade do veículo (em alguns sistemas);
- **Sistema de Freios:** Modula a pressão de frenagem individual.

---

## 6. Defeitos Comuns
- Sensor danificado (sinal ausente ou intermitente);
- Mau contato no conector ou chicote quebrado;
- Acúmulo de sujeira ou limalha na roda fônica;
- Roda fônica danificada ou com folga;
- Ruído eletromagnético interferindo no sinal.

---

## 7. Códigos DTC Associados (OBD-II)
- **C0035 a C0050:** Falha do sensor de velocidade da roda (específico por roda);
- **C0200 a C0279:** Erros de sinal ou circuito no sistema de ABS;
- **U0121:** Perda de comunicação com o módulo ABS.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise da forma de onda (senoidal no passivo, digital no ativo);
- Verificação de integridade, ruídos e amplitude;
- Comparação entre as quatro rodas.

### Multímetro
- Medição de resistência da bobina (sensor passivo);
- Tensão de alimentação e sinal (sensor ativo);
- Teste de continuidade e integridade do chicote.

### Scanner
- Leitura em tempo real da velocidade de cada roda;
- Identificação de falhas intermitentes;
- Testes de atuador e simulação de rotações para diagnóstico.

---

## 9. Procedimentos de Diagnóstico
1. Verificar integridade do chicote e conector;
2. Medir resistência do sensor (caso passivo) e tensão (caso ativo);
3. Testar resposta dinâmica com osciloscópio em rotação simulada;
4. Usar scanner para comparar velocidade entre rodas;
5. Limpar roda fônica e verificar folgas mecânicas.

---

## 10. Observações
- A variação da velocidade entre rodas pode indicar não apenas falha do sensor, mas também problemas mecânicos (rolamento, homocinética, etc.);
- Motores com controle de torque e freio motor utilizam os dados desse sensor.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

