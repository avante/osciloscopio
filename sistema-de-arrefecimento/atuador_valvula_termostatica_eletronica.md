# Ficha Técnica – Atuador da Válvula Termostática Eletrônica

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Arrefecimento / Controle Térmico Ativo

---

## 1. Identificação
Dispositivo responsável pelo controle eletrônico da abertura da válvula termostática, otimizando a temperatura do motor em diferentes condições operacionais.

---

## 2. Descrição Geral
A válvula termostática eletrônica difere da convencional por contar com um elemento de acionamento controlado eletricamente, que pode ser um resistor PTC, motor de passo ou solenóide, em vez do bulbo com cera expansiva.

---

## 3. Características Construtivas
- Corpo metálico ou termoplástico com alojamento para a válvula;
- Atuador elétrico incorporado (resistência ou motor);
- Conector elétrico de 2 a 4 pinos;
- Sensor de temperatura interno em alguns modelos;
- Canal de derivação para recirculação ou bypass;
- Pode ser integrada ao módulo do alojamento do termostato.

---

## 4. Funções
- Controlar a abertura do circuito de arrefecimento principal;
- Manter o motor operando na faixa térmica ideal;
- Reduzir emissões em partidas a frio;
- Acelerar o aquecimento do motor e da cabine (em motores a diesel ou flex);
- Permitir estratégias térmicas otimizadas para consumo e desempenho.

---

## 5. Interações Sistêmicas
- **ECU:** Controla a abertura conforme mapa térmico;
- **Sensor ECT:** Fornece temperatura do motor para controle da válvula;
- **Eletroventilador:** Atua em conjunto para gerenciar o calor excedente;
- **Aquecedor de Cabine:** Se beneficia do controle térmico mais preciso.

---

## 6. Defeitos Comuns
- Válvula travada aberta ou fechada;
- Falha no atuador elétrico (abertura tardia ou ausente);
- Queima do resistor de acionamento;
- Falha na comunicação com a ECU;
- Variações térmicas não condizentes com a estratégia.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0597:** Circuito de controle do termostato aberto;
- **P0598:** Baixa tensão no controle do termostato;
- **P0599:** Alta tensão no controle do termostato;
- **P0128:** Temperatura do motor abaixo da ideal por tempo prolongado (indicativo de válvula travada aberta).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal de controle (PWM ou tensão direta);
- Observação do tempo de resposta térmico;
- Verificação de feedback (quando aplicável).

### Multímetro
- Medição de resistência do atuador;
- Teste de tensão no conector;
- Verificação da continuidade do chicote.

### Scanner
- Comando de teste de atuador (se suportado);
- Monitoramento da temperatura do motor e tempo de aquecimento;
- Leitura de falhas relacionadas ao sistema térmico.

---

## 9. Procedimentos de Diagnóstico
1. Verificar tensão de alimentação e continuidade do chicote;
2. Observar a variação da temperatura com o motor em funcionamento;
3. Forçar a atuação da válvula via scanner (em modelos compatíveis);
4. Medir resistência do resistor de aquecimento;
5. Comparar o tempo de aquecimento com a curva esperada.

---

## 10. Observações
- A válvula eletrônica oferece controle térmico mais eficiente, mas exige diagnóstico mais técnico;
- Em caso de falha, o sistema pode adotar estratégias de fallback (modo de segurança).

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

