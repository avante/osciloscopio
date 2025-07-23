# Ficha Técnica – Regulador de Tensão

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Carga / Controle do Alternador

---

## 1. Identificação
O regulador de tensão controla a tensão de saída do alternador, mantendo-a dentro de uma faixa segura para o sistema elétrico do veículo, protegendo a bateria e os componentes eletrônicos.

---

## 2. Descrição Geral
Geralmente integrado ao alternador, o regulador de tensão atua sobre o campo magnético do rotor, ajustando a geração de corrente conforme a demanda do sistema elétrico. Pode ser de controle interno (analógico) ou externo (digital, via ECU).

---

## 3. Características Construtivas
- Circuito eletrônico com transistores de potência;
- Sensor interno de tensão e temperatura;
- Comunicação com ECU via LIN ou sinal PWM (em sistemas inteligentes);
- Integrado ao alternador ou separado (reguladores externos);
- Resistente a altas temperaturas e vibrações.

---

## 4. Funções
- Manter a tensão de carregamento entre 13,8 V e 14,8 V (12V);
- Evitar sobrecarga da bateria e oscilação de tensão;
- Ajustar a carga conforme temperatura e consumo;
- Atuar em conjunto com estratégias de economia (load shedding);
- Controlar o desligamento temporário do alternador (em veículos modernos).

---

## 5. Interações Sistêmicas
- **Alternador:** Atua diretamente no campo do rotor;
- **Sensor de tensão da bateria:** Fornece parâmetro de controle;
- **ECU / BCM:** Comanda reguladores inteligentes;
- **Painel de instrumentos:** Exibe alertas de falha de carga.

---

## 6. Defeitos Comuns
- Regulagem incorreta da tensão de saída (alta ou baixa);
- Perda de controle pelo circuito de campo;
- Falhas por temperatura excessiva;
- Problemas de comunicação digital (LIN);
- Curto-circuito ou falha interna do módulo.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0620 a P0622:** Falhas no circuito de controle do alternador;
- **P2501 / P2503:** Tensão anormal da fonte de alimentação;
- **U0121 / U0140:** Perda de comunicação com o regulador inteligente.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Monitoramento do PWM de controle (em sistemas modernos);
- Análise de resposta do regulador em diferentes regimes.

### Multímetro
- Medição da tensão de saída do alternador com motor em marcha lenta e acelerado;
- Verificação do sinal de controle (LIN/PWM) no conector;
- Continuidade e tensão nos terminais do rotor (D+ e DF).

### Scanner
- Diagnóstico de falhas armazenadas;
- Leitura da tensão de carregamento em tempo real;
- Monitoramento de comandos do regulador ativo.

---

## 9. Procedimentos de Diagnóstico
1. Medir a tensão da bateria em repouso e com o motor ligado;
2. Verificar o controle do campo (sinal PWM ou DF);
3. Testar o alternador com carga elétrica elevada;
4. Checar integridade do chicote e fusíveis;
5. Substituir o regulador se estiver fora da faixa de controle.

---

## 10. Observações
- Sistemas inteligentes desligam o alternador sob baixa demanda;
- Em veículos modernos, o regulador pode estar codificado com a ECU.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

