# Ficha Técnica – Sensor de Pressão do Coletor (MAP)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Admissão de Ar / Cálculo de Carga do Motor

---

## 1. Identificação
Sensor que mede a pressão absoluta no coletor de admissão, permitindo à ECU calcular a carga do motor, corrigir o tempo de injeção e controlar a ignição.

---

## 2. Descrição Geral
O sensor MAP (Manifold Absolute Pressure) converte a pressão do coletor de admissão em um sinal elétrico, geralmente do tipo analógico. Ele é crucial para sistemas de injeção sem sensor MAF, e também atua em redundância quando ambos estão presentes.

---

## 3. Características Construtivas
- Corpo plástico selado com diafragma sensível à pressão;
- Elemento sensor piezoresistivo com circuito integrado;
- Conector de 3 vias (alimentação, sinal e terra);
- Pode estar montado diretamente no coletor ou conectado por mangueira;
- Faixa típica: 20 a 250 kPa absolutos (0,2 a 2,5 bar).

---

## 4. Funções
- Informar à ECU a pressão absoluta no coletor de admissão;
- Calcular a massa de ar admitida usando equações termodinâmicas (em motores sem MAF);
- Determinar a carga do motor e corrigir avanço de ignição e tempo de injeção;
- Atuar na estratégia de partida e controle de emissões.

---

## 5. Interações Sistêmicas
- **ECU:** Usa o sinal do MAP para cálculo de carga e mistura;
- **Sensor IAT:** Junto ao MAP, permite cálculo da densidade do ar;
- **Sensor TPS:** Corrige as variações rápidas de abertura da borboleta;
- **Sensor MAF (quando presente):** Atua em redundância ou comparação.

---

## 6. Defeitos Comuns
- Sinal fora da faixa (baixa ou alta pressão);
- Sensor com resposta lenta ou travado;
- Mangueira obstruída ou desconectada (em sensores remotos);
- Contato elétrico deficiente;
- Leitura incorreta por entupimento de óleo ou vapores do blow-by.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0105:** Circuito do sensor MAP / pressão barométrica;
- **P0106:** Faixa/desempenho incorreto;
- **P0107:** Tensão baixa do sensor MAP;
- **P0108:** Tensão alta do sensor MAP;
- **P0109:** Intermitência no circuito do sensor MAP.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação da forma de onda da pressão em marcha lenta e aceleração;
- Sinal analógico progressivo (0,5 a 4,5 V);
- Possível detectar variações anormais causadas por vazamentos.

### Multímetro
- Medição da tensão de alimentação (geralmente 5 V);
- Medição do sinal em repouso e sob carga;
- Teste de continuidade do chicote.

### Scanner
- Leitura da pressão em kPa ou bar;
- Comparação com a pressão barométrica e condição do motor (motor desligado = pressão atmosférica);
- Análise da coerência com TPS e rotação do motor.

---

## 9. Procedimentos de Diagnóstico
1. Medir a tensão do sinal com ignição ligada e motor desligado (deve indicar pressão atmosférica);
2. Observar a variação da pressão com o motor em marcha lenta e acelerado;
3. Comparar leitura do scanner com valores de referência por rotação;
4. Verificar obstruções na linha de vácuo (se aplicável);
5. Testar alimentação e aterramento do sensor.

---

## 10. Observações
- Em altitude elevada, a leitura do MAP será menor mesmo com motor desligado;
- Muitos sensores MAP modernos integram também o sensor IAT (chamados T-MAP).

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

