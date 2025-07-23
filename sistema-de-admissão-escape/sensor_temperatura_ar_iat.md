# Ficha Técnica – Sensor de Temperatura do Ar de Admissão (IAT)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Admissão de Ar / Cálculo de Carga e Mistura

---

## 1. Identificação
Sensor que mede a temperatura do ar que entra no motor, permitindo correções na injeção e no avanço da ignição com base na densidade do ar admitido.

---

## 2. Descrição Geral
Sensor do tipo termistor NTC (Negative Temperature Coefficient), cuja resistência varia de acordo com a temperatura do ar. Essa informação é usada para corrigir o volume de combustível injetado e otimizar o funcionamento do motor.

---

## 3. Características Construtivas
- Elemento sensor encapsulado em corpo plástico ou metálico;
- Sensor do tipo NTC (resistência diminui com aumento de temperatura);
- Conector de 2 pinos (alimentação e sinal ou sinal e terra);
- Pode ser instalado no coletor de admissão, duto do filtro de ar, ou integrado ao sensor MAF ou MAP;
- Faixa típica: -40 °C a +125 °C.

---

## 4. Funções
- Medir a temperatura do ar de admissão;
- Corrigir a densidade do ar para cálculo da mistura ideal;
- Atuar na estratégia de partida a frio;
- Corrigir avanço de ignição conforme a temperatura do ar.

---

## 5. Interações Sistêmicas
- **Sensor MAP / MAF:** Trabalha em conjunto para cálculo da massa de ar;
- **ECU:** Utiliza o valor para ajustar injeção e ignição;
- **Sensor de Temperatura do Motor:** Confronta dados para detecção de falhas.

---

## 6. Defeitos Comuns
- Leitura congelada (valor fixo);
- Resistência fora da faixa;
- Sensor aberto ou em curto;
- Oxidação ou mau contato no conector;
- Sensor sujo (pode afetar resposta térmica).

---

## 7. Códigos DTC Associados (OBD-II)
- **P0110:** Circuito do sensor IAT;
- **P0111:** Faixa/desempenho incorreto;
- **P0112:** Tensão baixa (temperatura muito alta);
- **P0113:** Tensão alta (temperatura muito baixa);
- **P0114:** Intermitência no sinal do sensor.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Curva de resposta lenta e estável conforme variação térmica;
- Possibilidade de observar ruídos ou falhas de aterramento.

### Multímetro
- Medição de resistência do sensor;
- Valor típico: ~2,5 kΩ a 25 °C, com queda progressiva à medida que aquece;
- Teste de alimentação (se houver) e continuidade.

### Scanner
- Leitura da temperatura do ar em tempo real;
- Comparação com temperatura ambiente e do motor;
- Leitura de DTCs associados.

---

## 9. Procedimentos de Diagnóstico
1. Verificar no scanner se a leitura está coerente com a temperatura ambiente;
2. Medir resistência do sensor com motor frio e quente;
3. Verificar a integridade do chicote e conector;
4. Realizar comparação cruzada com a leitura do sensor de temperatura do motor (ECT);
5. Substituir o sensor em caso de valores incompatíveis com a tabela do fabricante.

---

## 10. Observações
- Sensores integrados ao MAF ou MAP compartilham chicote e podem gerar falhas múltiplas;
- Leitura errada do IAT pode causar mistura rica ou pobre, afetando consumo e emissões.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

