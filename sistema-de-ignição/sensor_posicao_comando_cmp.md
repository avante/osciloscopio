# Ficha Técnica – Sensor de Posição do Comando de Válvulas (CMP)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Ignição / Sincronismo do Motor

---

## 1. Identificação
Sensor responsável por informar à ECU a posição angular do eixo comando de válvulas, necessário para identificar o ciclo do motor (admissão/escapamento) e sincronizar injeção e ignição.

---

## 2. Descrição Geral
O sensor CMP (Camshaft Position Sensor) opera de forma similar ao sensor CKP, mas com montagem no eixo comando. Pode ser indutivo ou Hall, e lê um ressalto ou alvo metálico (relutor) no eixo de comando.

---

## 3. Características Construtivas
- Sensor do tipo indutivo (2 fios) ou Hall (3 fios);
- Montado na tampa do cabeçote ou próximo ao comando;
- Relutor com ressaltos ou dentes no eixo de comando;
- Conector vedado de 2 a 3 vias;
- Pode ser incorporado a sistemas VVT (comando variável).

---

## 4. Funções
- Informar à ECU o ciclo de funcionamento (admissão ou escape);
- Auxiliar o sincronismo de ignição e injeção;
- Permitir partida sequencial (reduz consumo e emissões);
- Controlar o sistema de comando de válvulas variável (quando presente).

---

## 5. Interações Sistêmicas
- **Sensor CKP:** Atua em conjunto para definir o sincronismo completo do motor;
- **ECU:** Usa o CMP para controlar injeção sequencial, ignição e VVT;
- **Sistema de Injeção Eletrônica:** Exige sincronismo preciso para economia e desempenho.

---

## 6. Defeitos Comuns
- Sensor com leitura ausente ou intermitente;
- Relutor desalinhado ou danificado;
- Mau contato elétrico no conector;
- Sensor contaminado com óleo do motor;
- Variação térmica causando falhas em sensores Hall.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0340:** Circuito do sensor CMP com falha;
- **P0341:** Faixa/desempenho incorreto;
- **P0342:** Tensão baixa no sinal do CMP;
- **P0343:** Tensão alta;
- **P0344:** Intermitência ou perda de sinal.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Sinal senoidal (indutivo) ou quadrado (Hall);
- Deve haver correlação com o sinal do CKP;
- Forma de onda estável e periódica durante o funcionamento.

### Multímetro
- Medição de resistência (indutivo);
- Verificação de alimentação e sinal (Hall);
- Continuidade e isolamento do chicote.

### Scanner
- Verificação da sincronização do CMP com o CKP;
- Detecção de falhas e perda de sinal;
- Teste de sincronismo dinâmico (em alguns modelos).

---

## 9. Procedimentos de Diagnóstico
1. Comparar a forma de onda do CMP com o CKP;
2. Verificar resistência e tensão no sensor;
3. Checar o alinhamento do relutor com o comando;
4. Avaliar ruídos ou contaminação no sensor;
5. Confirmar funcionamento do VVT (quando aplicável).

---

## 10. Observações
- A ausência de sinal do CMP pode causar partida prolongada ou falhas intermitentes;
- Em motores com comando variável, o CMP é essencial para controle de torque e emissões.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

