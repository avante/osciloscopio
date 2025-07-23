# Ficha Técnica – Sensor de Tensão da Bateria

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema Elétrico / Monitoramento de Carga

---

## 1. Identificação
Sensor responsável por monitorar a tensão da bateria do veículo em tempo real, fornecendo dados essenciais à ECU ou BCM para controle de carga, diagnóstico e estratégias de economia de energia.

---

## 2. Descrição Geral
Trata-se de um sensor eletrônico que mede a tensão presente nos terminais da bateria, enviando essas informações ao módulo de controle para ajuste do carregamento pelo alternador, corte de cargas acessórias e diagnóstico de falhas.

---

## 3. Características Construtivas
- Sensor integrado ao terminal da bateria ou chicote principal;
- Placa eletrônica com divisor resistivo e conversor A/D;
- Comunicação digital (LIN, CAN) ou sinal analógico;
- Conector elétrico de 2 a 3 vias;
- Construção resistente à vibração e calor.

---

## 4. Funções
- Monitorar a tensão da bateria em tempo real;
- Permitir ajuste do regime de carga pelo regulador de tensão;
- Ativar modos de economia de energia;
- Alertar falhas no sistema de carga;
- Evitar sobrecarga ou descarga profunda.

---

## 5. Interações Sistêmicas
- **ECU / BCM:** Processa a informação para comandar o alternador;
- **Regulador de tensão:** Controla o campo do alternador conforme a tensão lida;
- **Sistema start-stop:** Avalia a saúde da bateria para permitir desligamento do motor;
- **Painel de instrumentos:** Exibe alertas de carga baixa.

---

## 6. Defeitos Comuns
- Falha de comunicação com módulo central;
- Leituras incorretas por oxidação no terminal;
- Sensor danificado por sobretensão;
- Chicote rompido ou em curto;
- Mau contato com a bateria.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0560:** Tensão do sistema fora da faixa;
- **P0562:** Tensão do sistema baixa;
- **P0563:** Tensão do sistema alta;
- **U0121 / U0129:** Perda de comunicação com o sensor (via LIN/CAN).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise da estabilidade da tensão com motor ligado/desligado;
- Comparação com tensão real medida nos terminais.

### Multímetro
- Medição direta da tensão na saída do sensor;
- Comparação com leitura da ECU via scanner;
- Verificação de alimentação e sinal.

### Scanner
- Leitura da tensão da bateria em tempo real;
- Verificação de erros no sistema de carga;
- Monitoramento do comportamento em carga e descarga.

---

## 9. Procedimentos de Diagnóstico
1. Verificar integridade do chicote e conector do sensor;
2. Comparar leitura do scanner com multímetro;
3. Inspecionar oxidação no terminal e conexão com a bateria;
4. Testar o sensor fora do veículo, se possível;
5. Substituir o sensor em caso de falhas intermitentes ou permanentes.

---

## 10. Observações
- A leitura incorreta da tensão pode afetar todo o gerenciamento elétrico do veículo;
- Em alguns veículos, o sensor está integrado ao terminal negativo da bateria.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

