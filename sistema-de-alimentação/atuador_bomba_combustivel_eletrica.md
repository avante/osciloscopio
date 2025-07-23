# Ficha Técnica – Atuador da Bomba de Combustível Elétrica

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Alimentação e Combustível

---

## 1. Identificação
Atuador eletromecânico responsável por fornecer pressão adequada de combustível ao sistema de injeção, controlado direta ou indiretamente pela ECU.

---

## 2. Descrição Geral
A bomba elétrica de combustível é um dispositivo rotativo (geralmente do tipo turbina ou palhetas) acionado por um motor elétrico, instalado no interior do tanque. A pressão e o volume são controlados conforme a demanda do motor.

---

## 3. Características Construtivas
- Motor elétrico DC selado;
- Elemento bombeador centrífugo ou de palhetas;
- Incorporada ao módulo de envio de combustível (em muitos veículos);
- Conectores elétricos (2 a 4 vias: positivo, negativo, sinal PWM, retorno);
- Alguns modelos com válvula de retenção integrada e pré-filtro;
- Alimentada por relé ou módulo eletrônico de controle (FPCM – Fuel Pump Control Module).

---

## 4. Funções
- Pressurizar o sistema de combustível;
- Alimentar os injetores com vazão e pressão adequadas;
- Manter a pressão estável sob diferentes regimes de funcionamento;
- Auxiliar na partida do motor (pressurização inicial).

---

## 5. Interações Sistêmicas
- **ECU:** Comanda a bomba diretamente ou via módulo intermediário;
- **Relé de Bomba / Módulo de Controle:** Faz o chaveamento da alimentação;
- **Sensor de Pressão do Combustível:** Fornece feedback para modulação da bomba;
- **Injetores:** Dependem da vazão adequada para funcionar corretamente.

---

## 6. Defeitos Comuns
- Bomba sem acionamento (motor queimado);
- Pressão insuficiente (desgaste interno, entupimento);
- Ruído excessivo (rolamento ou cavitação);
- Interrupção intermitente (falha no relé, conector ou chicote);
- Pré-filtro entupido (baixa vazão).

---

## 7. Códigos DTC Associados (OBD-II)
- **P0230:** Circuito primário da bomba de combustível;
- **P0231:** Tensão baixa no circuito secundário;
- **P0232:** Tensão alta no circuito secundário;
- **P0087:** Pressão de combustível insuficiente;
- **P0627:** Falha de controle da bomba (comando).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação do sinal de acionamento PWM (em sistemas modulados);
- Análise do consumo de corrente em tempo real (forma de onda característica);
- Diagnóstico de falhas intermitentes por análise do ruído elétrico.

### Multímetro
- Medição da tensão nos terminais da bomba (12 V em funcionamento);
- Teste de continuidade do motor da bomba;
- Verificação da queda de tensão entre bateria e bomba.

### Scanner
- Comando de acionamento da bomba via atuadores (teste de saída);
- Monitoramento da pressão reportada pelo sensor;
- Verificação de falhas armazenadas no sistema.

---

## 9. Procedimentos de Diagnóstico
1. Verificar se há tensão no conector da bomba durante o acionamento;
2. Testar resistência do motor da bomba (valores típicos: 1 a 3 Ω);
3. Observar consumo de corrente com amperímetro ou osciloscópio (forma de onda padrão);
4. Utilizar scanner para forçar acionamento e monitorar resposta;
5. Verificar pré-filtro e condições do combustível (contaminações).

---

## 10. Observações
- Falhas na bomba podem causar partida difícil, perda de potência e funcionamento irregular;
- Bomba com desgaste pode gerar pressão suficiente em marcha lenta, mas falhar sob carga.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

