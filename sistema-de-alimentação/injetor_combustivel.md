# Ficha Técnica – Injetor de Combustível

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Alimentação e Combustível

---

## 1. Identificação
Atuador eletromecânico responsável por pulverizar o combustível sob pressão na câmara de combustão ou no coletor de admissão, comandado pela ECU de forma precisa em tempo e volume.

---

## 2. Descrição Geral
Os injetores modernos são do tipo solenoide (eletromagnéticos) ou piezoelétricos, que ao receberem um sinal da ECU, abrem por milissegundos permitindo a passagem do combustível pressurizado por um orifício calibrado (bico injetor), atomizando o líquido.

---

## 3. Características Construtivas
- Corpo metálico com ponteira em aço inoxidável;
- Solenóide interno (ou cristal piezoelétrico);
- Filtro de entrada (telinha filtrante);
- O-ring de vedação superior e inferior;
- Conector elétrico de 2 pinos (sinal + e -);
- Vazão típica: 30 a 400 ml/min (varia conforme aplicação);
- Spray com 1 a 12 furos (modelos multiponto e GDI).

---

## 4. Funções
- Pulverizar o combustível com atomização adequada;
- Garantir precisão na dosagem da mistura ar-combustível;
- Responder em alta frequência ao comando da ECU;
- Trabalhar de forma sincronizada com o ciclo do motor.

---

## 5. Interações Sistêmicas
- **ECU:** Controla o tempo de abertura (tempo de injeção);
- **Sensor de Pressão e Temperatura do Combustível:** Influenciam o tempo e o modo de injeção;
- **Sensor de Oxigênio (Sonda Lambda):** Fornece feedback para ajustes na mistura;
- **Bomba de Combustível:** Deve manter pressão estável para injeção eficaz.

---

## 6. Defeitos Comuns
- Entupimento parcial ou total dos orifícios;
- Vazamento (injeção contínua ou gotejamento);
- Solenóide queimado ou travado;
- Mau contato no conector elétrico;
- Desgaste das vedações (O-rings).

---

## 7. Códigos DTC Associados (OBD-II)
- **P0200:** Circuito de injetor – falha genérica;
- **P0201** a **P0206:** Injetor específico com falha (cilindros 1 a 6);
- **P0300:** Falha de ignição aleatória (pode ser causada por injetor);
- **P0171 / P0172:** Mistura pobre ou rica (relacionado ao funcionamento do injetor).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal de comando (pulso negativo, geralmente 12 V);
- Verificação de tempo de injeção e forma de onda característica;
- Diagnóstico de falhas intermitentes no acionamento.

### Multímetro
- Medição de resistência da bobina (tipicamente entre 10 a 16 Ω);
- Teste de continuidade no circuito do injetor;
- Detecção de curto ou circuito aberto.

### Scanner
- Monitoramento do tempo de injeção em ms;
- Teste de atuador (comando individual para ver se o injetor responde);
- Análise de correções de mistura (LTFT/STFT) que indiquem falha de injeção.

---

## 9. Procedimentos de Diagnóstico
1. Verificar pulsos de acionamento com osciloscópio;
2. Medir resistência e continuidade elétrica dos injetores;
3. Utilizar scanner para acionar injetores individualmente;
4. Analisar correções de mistura e falhas de combustão;
5. Em caso de suspeita de entupimento, realizar teste de vazão ou ultrassom.

---

## 10. Observações
- Injetores com spray incorreto afetam diretamente consumo, emissões e desempenho;
- Substituição deve sempre considerar limpeza prévia e verificação de vedação.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

