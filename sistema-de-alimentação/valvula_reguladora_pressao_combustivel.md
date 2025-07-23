# Ficha Técnica – Válvula Reguladora de Pressão de Combustível

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Alimentação e Combustível

---

## 1. Identificação
Dispositivo responsável por manter a pressão do combustível constante no rail ou linha de alimentação, controlando o retorno para o tanque ou a modulação da bomba.

---

## 2. Descrição Geral
A válvula reguladora pode ser do tipo mecânico (com diafragma e mola) ou eletrônico (atuada por solenoide). Controla a pressão do combustível devolvendo o excedente para o tanque ou reduzindo a atuação da bomba.

---

## 3. Características Construtivas
- Corpo metálico com entrada e saída de combustível;
- Versões mecânicas usam mola calibrada e diafragma;
- Versões eletrônicas usam solenóide modulada por PWM;
- Conector elétrico de 2 ou 3 pinos (versão eletrônica);
- Montagem: no rail, na bomba ou em linha separada.

---

## 4. Funções
- Manter a pressão do sistema de combustível estável;
- Adaptar a pressão conforme o regime do motor;
- Em sistemas eletrônicos, permitir controle dinâmico pela ECU;
- Reduzir consumo energético ao limitar o trabalho da bomba.

---

## 5. Interações Sistêmicas
- **Sensor de Pressão do Combustível:** Atua em conjunto para fornecer feedback à ECU;
- **Bomba de Combustível:** A válvula regula a carga sobre a bomba;
- **ECU:** Em versões eletrônicas, comanda a válvula com base na demanda do motor;
- **Sistema de Injeção:** Depende de pressão estável para garantir pulverização eficiente.

---

## 6. Defeitos Comuns
- Pressão excessiva ou insuficiente;
- Válvula travada aberta ou fechada;
- Ruído excessivo por ressonância ou retorno excessivo;
- Conector com oxidação (versão eletrônica);
- Mola de retorno com fadiga (versão mecânica).

---

## 7. Códigos DTC Associados (OBD-II)
- **P0089:** Desempenho da regulagem de pressão de combustível incorreto;
- **P0090:** Circuito da válvula reguladora de pressão;
- **P0091:** Tensão baixa no circuito de controle;
- **P0092:** Tensão alta no circuito de controle.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Sinal PWM de controle (em versões eletrônicas);
- Verificação de atuação sob diferentes cargas de motor;
- Forma de onda estável e com duty cycle variável.

### Multímetro
- Medição de resistência da bobina (versão eletrônica);
- Tensão de acionamento (12 V ou modulada);
- Teste de continuidade do circuito.

### Scanner
- Monitoramento do valor de pressão de combustível;
- Atuação da válvula por teste de atuadores (se disponível);
- Leitura de falhas armazenadas relacionadas ao controle da pressão.

---

## 9. Procedimentos de Diagnóstico
1. Medir a pressão com manômetro e comparar com a leitura do scanner;
2. Acionar a válvula com o scanner (se aplicável) e observar resposta;
3. Verificar a resistência e alimentação da válvula (versão eletrônica);
4. Avaliar retorno ao tanque e presença de entupimentos na linha;
5. Substituir por peça conhecida em casos de travamento.

---

## 10. Observações
- Uma válvula com funcionamento incorreto pode causar marcha lenta irregular, perda de potência ou dificuldade de partida;
- Em alguns sistemas, a ausência da válvula (regulação feita via bomba modulada) pode levar a diagnóstico incorreto.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

