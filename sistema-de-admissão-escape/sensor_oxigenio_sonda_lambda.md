# Ficha Técnica – Sensor de Oxigênio (Sonda Lambda)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Controle de Emissões

---

## 1. Identificação
Sensor que mede a concentração de oxigênio presente nos gases de escape, informando à ECU se a mistura ar-combustível está rica ou pobre.

---

## 2. Descrição Geral
A sonda lambda pode ser do tipo convencional (narrowband) ou do tipo banda larga (wideband). Ambas operam com células eletroquímicas baseadas em dióxido de zircônio ou titânio, gerando uma tensão ou corrente proporcional ao teor de oxigênio no escapamento.

---

## 3. Características Construtivas
- Corpo metálico com rosca para fixação no escapamento;
- Elemento sensor de zircônio com aquecedor interno (heater);
- Conector de 1 a 6 vias (sinal, terra, aquecimento);
- Tensão de operação: narrowband (0–1 V), wideband (corrente ou sinal digital);
- Faixa térmica: ~300 °C a 800 °C.

---

## 4. Funções
- Monitorar a qualidade da combustão (mistura rica/pobre);
- Permitir correções em tempo real da mistura (controle de malha fechada);
- Avaliar a eficiência do catalisador (sonda pós-catalisador);
- Reduzir emissões e otimizar consumo de combustível.

---

## 5. Interações Sistêmicas
- **ECU:** Ajusta o tempo de injeção e ignição com base na leitura da sonda;
- **Catalisador:** A segunda sonda avalia sua eficiência;
- **Sensor MAF/MAP/IAT:** Trabalham em conjunto no controle da mistura;
- **Sistema de partida a frio:** Considera o atraso na ativação da sonda (aquecimento).

---

## 6. Defeitos Comuns
- Sensor sem resposta (elemento danificado ou aquecedor inoperante);
- Sinal fixo (mistura congelada, chicote com falha);
- Resposta lenta (sonda contaminada por óleo ou combustível);
- Sonda pós-catalisador acusando baixa eficiência (catalisador comprometido);
- Falha no sistema de aquecimento.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0130 a P0167:** Diversos códigos relacionados às sondas lambda por banco e posição;
- **P0420:** Eficiência do catalisador abaixo do ideal;
- **P0133:** Resposta lenta da sonda;
- **P0135:** Falha no aquecimento da sonda (heater);
- **P2195 / P2196:** Mistura rica/pobre detectada incorretamente.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Sonda narrowband: variação de 0 a 1 V oscilando rapidamente em marcha lenta (1–2 Hz);
- Sonda wideband: análise de corrente ou PWM com precisão maior;
- Detecção de lentidão, travamento ou ruídos no sinal.

### Multímetro
- Leitura da tensão do sinal (narrowband);
- Verificação de alimentação do aquecedor (12 V);
- Medição de resistência do elemento aquecedor.

### Scanner
- Leitura em tempo real do valor da mistura (lambda, AFR, V);
- Verificação de resposta da sonda ao acelerar/desacelerar;
- Avaliação da sonda pós-catalisador (eficiência do catalisador);
- Leitura e limpeza de DTCs relacionados.

---

## 9. Procedimentos de Diagnóstico
1. Observar a oscilação do sinal em marcha lenta;
2. Testar o aquecimento: medir a resistência do heater e verificar se recebe alimentação;
3. Forçar variações de mistura (ex: desconectar mangueira de vácuo) e observar reação;
4. Avaliar com scanner a eficiência do catalisador (comparar pré e pós-sonda);
5. Verificar existência de contaminação no sensor (óleo, silicone, aditivos).

---

## 10. Observações
- Sondas wideband exigem interpretação correta via scanner ou osciloscópio, pois seus sinais não são simplesmente em volts;
- Substituição deve sempre considerar a compatibilidade com o sistema de controle e com o tipo de combustível (flex, diesel, GNV).

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

