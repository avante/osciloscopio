# Ficha Técnica – Sensor de Temperatura do Líquido de Arrefecimento (ECT)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Arrefecimento / Estratégias de Operação do Motor

---

## 1. Identificação
Sensor responsável por informar à ECU a temperatura do líquido de arrefecimento do motor, essencial para controle de injeção, ignição, acionamento do eletroventilador e proteção térmica.

---

## 2. Descrição Geral
O ECT (Engine Coolant Temperature) é geralmente um termistor NTC, cuja resistência diminui com o aumento da temperatura. Ele está instalado na carcaça do termostato, cabeçote ou bloco do motor.

---

## 3. Características Construtivas
- Elemento sensor do tipo NTC encapsulado em corpo metálico;
- Rosca para instalação com vedação em junta ou anel O-ring;
- Conector de 2 pinos (sinal e terra ou alimentação);
- Faixa de operação: -40 °C a +130 °C;
- Tempo de resposta rápido.

---

## 4. Funções
- Corrigir tempo de injeção e avanço de ignição;
- Atuar na estratégia de partida a frio;
- Acionar eletroventilador via ECU;
- Informar sobreaquecimento e proteger o motor;
- Permitir controle de emissões e regeneração do catalisador.

---

## 5. Interações Sistêmicas
- **ECU:** Ajusta parâmetros conforme a temperatura lida;
- **Sensor IAT:** Trabalha em conjunto para correção térmica da mistura;
- **Eletroventilador:** Controlado pela ECU com base na leitura do ECT;
- **Painel de Instrumentos:** Exibe a temperatura para o condutor.

---

## 6. Defeitos Comuns
- Leitura congelada (valor fixo);
- Sinal incorreto (NTC degradado);
- Circuito aberto ou curto;
- Oxidação nos terminais;
- Sensor com tempo de resposta muito lento.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0115:** Circuito do sensor de temperatura do líquido de arrefecimento;
- **P0116:** Faixa ou desempenho incorreto;
- **P0117:** Tensão baixa (temperatura alta);
- **P0118:** Tensão alta (temperatura baixa);
- **P0119:** Intermitência no sinal do sensor.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação da transição suave da tensão conforme variação térmica;
- Forma de onda estável e progressiva;
- Diagnóstico de ruídos ou falhas intermitentes.

### Multímetro
- Medição da resistência do sensor e comparação com tabela do fabricante;
- Tensão de alimentação e sinal (5 V e leitura entre 0,2–4,5 V);
- Teste de continuidade e verificação de terra.

### Scanner
- Leitura da temperatura em tempo real;
- Verificação da coerência com o motor frio e quente;
- Leitura e exclusão de DTCs;
- Teste funcional de acionamento do eletroventilador.

---

## 9. Procedimentos de Diagnóstico
1. Medir a resistência do sensor com o motor frio e comparar com a tabela;
2. Aquecer o motor e acompanhar a variação com scanner e multímetro;
3. Verificar tensão de alimentação e integridade do chicote;
4. Avaliar resposta dinâmica no osciloscópio;
5. Confirmar correlação entre o valor do sensor e o acionamento do ventilador.

---

## 10. Observações
- A falha nesse sensor pode afetar toda a estratégia de funcionamento do motor;
- Motores modernos podem usar até dois sensores ECT (um para ECU e outro para painel).

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

