# Ficha Técnica – Sensor de Posição do Virabrequim (CKP)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Ignição / Sincronismo do Motor

---

## 1. Identificação
Sensor responsável por informar à ECU a posição angular e a rotação do virabrequim, permitindo o sincronismo da ignição e da injeção de combustível.

---

## 2. Descrição Geral
O sensor CKP (Crankshaft Position Sensor) capta a rotação do motor a partir de um anel dentado (relutor) acoplado ao virabrequim. Pode ser do tipo indutivo (gerador de sinal AC) ou do tipo Hall (sinal digital com alimentação).

---

## 3. Características Construtivas
- Corpo metálico ou plástico com cápsula sensora;
- Sensor do tipo indutivo (2 fios) ou Hall (3 fios);
- Montado próximo ao volante do motor, polia do virabrequim ou engrenagem;
- Anel relutor com dentes usinados ou rebaixos;
- Conector elétrico selado contra umidade.

---

## 4. Funções
- Determinar o ponto exato do PMS (ponto morto superior);
- Fornecer rotação do motor (RPM) para a ECU;
- Controlar o sincronismo de injeção e ignição;
- Atuar em conjunto com o sensor CMP para identificar o ciclo do motor.

---

## 5. Interações Sistêmicas
- **ECU:** Recebe sinal do CKP para controle da ignição e injeção;
- **Sensor CMP:** Junto ao CKP, define o sincronismo completo do ciclo Otto;
- **Bobina de Ignição / Injetores:** São acionados conforme o sinal do CKP;
- **Sistemas de partida e corte de combustível.**

---

## 6. Defeitos Comuns
- Sensor aberto ou com resistência fora do padrão;
- Sinal intermitente por mau contato ou vibração;
- Acúmulo de limalha ou sujeira no sensor;
- Anel relutor danificado ou com dentes deformados;
- Sensor com leitura irregular em alta temperatura.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0335:** Falha no circuito do sensor de posição do virabrequim;
- **P0336:** Faixa/desempenho fora do esperado;
- **P0337:** Sinal baixo;
- **P0338:** Sinal alto;
- **P0339:** Sinal intermitente ou intermitência no circuito CKP.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Sinal senoidal (indutivo) ou quadrado (Hall);
- Forma de onda precisa e constante, sem falhas ou ruídos;
- Permite verificar falhas intermitentes, desalinhamento ou dentes ausentes.

### Multímetro
- Medição de resistência do sensor (indutivo: 500–1500 ohms);
- Teste de alimentação e sinal (sensor Hall);
- Teste de continuidade e isolamento dos fios.

### Scanner
- Leitura da rotação do motor (RPM);
- Verificação da presença do sinal em partida e funcionamento;
- Detecção de falhas de sincronismo.

---

## 9. Procedimentos de Diagnóstico
1. Medir resistência do sensor indutivo e comparar com especificação;
2. Verificar alimentação e sinal do sensor Hall com ignição ligada;
3. Avaliar forma de onda com osciloscópio durante a partida;
4. Verificar integridade do chicote e conector;
5. Inspecionar o anel relutor quanto a sujeira, limalha ou danos físicos.

---

## 10. Observações
- A ausência do sinal do CKP impede o motor de dar partida;
- Em alguns sistemas, uma falha intermitente pode causar corte súbito da ignição e injeção.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

