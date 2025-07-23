# Ficha Técnica – Sensor de NOx

**Tipo:** Sensor  
**Aplicação:** Linha Pesada (P)  
**Categoria:** Sistema de Pós-Tratamento de Emissões (SCR)

---

## 1. Identificação
O sensor de NOx (óxidos de nitrogênio) mede a concentração desses poluentes nos gases de escape, sendo essencial para monitorar a eficiência do sistema de Redução Catalítica Seletiva (SCR) e controlar a injeção do reagente Arla 32.

---

## 2. Descrição Geral
Instalado antes e/ou depois do catalisador SCR, o sensor de NOx utiliza tecnologia eletroquímica para detectar a concentração de NO e NO₂. Ele se comunica com a ECU de pós-tratamento, que ajusta o sistema de dosagem de Arla 32 com base nas leituras.

---

## 3. Características Construtivas
- Sonda eletroquímica com elemento cerâmico aquecido;
- Unidade de controle integrada ou remota;
- Rosca de fixação em tubo de escape;
- Conector de 5 a 6 vias com alimentação, sinal e aquecimento;
- Comunicação via CAN.

---

## 4. Funções
- Monitorar a emissão de NOx antes e depois do SCR;
- Garantir a eficiência do sistema de redução catalítica seletiva;
- Atuar no controle da dosagem de Arla 32;
- Acionar alertas ou modo de emergência em caso de falhas;
- Ajudar no diagnóstico de falhas do catalisador ou da dosagem.

---

## 5. Interações Sistêmicas
- **ECU de pós-tratamento:** Recebe os sinais do sensor e ajusta a injeção de Arla 32;
- **Sistema SCR:** Atua com base nos dados de NOx para reduzir emissões;
- **Sensor de temperatura dos gases:** Auxilia na correção da leitura;
- **Módulo OBD:** Usa as informações para verificar conformidade ambiental.

---

## 6. Defeitos Comuns
- Falha no elemento sensor (sem leitura ou leitura incorreta);
- Envelhecimento do sensor e perda de precisão;
- Problemas no aquecedor da sonda;
- Oxidação do chicote ou falha na unidade de controle;
- Falha de comunicação CAN.

---

## 7. Códigos DTC Associados (OBD-II)
- **P2200 / P2201:** Circuito do sensor de NOx – banco 1;
- **P2202 / P2203:** Sinal fora de faixa ou inválido;
- **P229F / P2BAD:** Eficiência abaixo do limite;
- **U029D:** Comunicação com sensor de NOx perdida.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal digital CAN (quando disponível);
- Verificação de comportamento do aquecedor (sinal PWM).

### Multímetro
- Teste de alimentação e aterramento da unidade de controle;
- Continuidade dos fios e conectores.

### Scanner
- Leitura das concentrações de NOx em ppm;
- Teste funcional do sensor e do aquecedor;
- Monitoramento da eficiência do catalisador.

---

## 9. Procedimentos de Diagnóstico
1. Verificar códigos de falha no scanner;
2. Medir alimentação e sinal do sensor;
3. Avaliar o funcionamento do aquecedor;
4. Comparar leituras de pré e pós-SCR;
5. Substituir o sensor se leituras forem incorretas ou inexistentes.

---

## 10. Observações
- O sensor de NOx é fundamental para atender às normas de emissões Euro V/VI e P7/P8 no Brasil;
- A substituição requer, em alguns casos, reprogramação da ECU ou aprendizado via scanner.

---

**Legenda:**  
P = Linha Pesada

