# Ficha Técnica – Sensor de Ângulo do Volante

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Direção / Estabilidade

---

## 1. Identificação
O sensor de ângulo do volante mede a posição angular e a velocidade de rotação do volante, sendo essencial para o funcionamento dos sistemas de controle de estabilidade (ESP), direção elétrica e assistência à condução.

---

## 2. Descrição Geral
Geralmente localizado na coluna de direção, esse sensor monitora a posição exata do volante em graus, enviando as informações para a ECU ou para o módulo do ESP. Pode ser do tipo óptico, magnético ou baseado em codificadores rotativos (encoder).

---

## 3. Características Construtivas
- Sensor rotativo com encoder óptico ou magnético;
- Faixa de medição de até 720° (duas voltas completas);
- Comunicação digital via barramento CAN ou LIN;
- Alimentação elétrica de 5 V ou 12 V;
- Integrado ao conjunto da coluna de direção ou separado.

---

## 4. Funções
- Determinar o ângulo e a direção de rotação do volante;
- Atuar no controle eletrônico de estabilidade (ESP);
- Auxiliar na direção elétrica (EPS);
- Integrar dados em sistemas de estacionamento automático;
- Sincronizar com sensores de velocidade da roda e força G.

---

## 5. Interações Sistêmicas
- **Módulo ESP:** Compara ângulo do volante com trajetória real do veículo;
- **Direção elétrica (EPS):** Adapta esforço de assistência;
- **Piloto automático adaptativo:** Considera mudanças de direção;
- **Central de assistência ao condutor (ADAS):** Integra os dados para controle avançado.

---

## 6. Defeitos Comuns
- Perda de calibração após manutenção ou colisão;
- Falha de sinal por dano no cabo flat;
- Erro de leitura por sujeira em sensores ópticos;
- Falha de comunicação com o módulo ESP;
- Sensor travado ou com valores fixos.

---

## 7. Códigos DTC Associados (OBD-II)
- **C0051:** Sinal inválido do sensor de ângulo de direção;
- **U0126:** Perda de comunicação com sensor de direção;
- **C1B00 / C1B01:** Falha de calibração ou valores fora da faixa;
- Códigos adicionais podem variar por fabricante.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Leitura da forma de onda ou variação digital ao girar o volante;
- Análise de resposta em tempo real.

### Multímetro
- Testes de alimentação e continuidade dos fios;
- Validação da tensão nos terminais de saída (sistemas analógicos).

### Scanner
- Leitura do ângulo do volante em tempo real;
- Calibração e reset do sensor após alinhamento;
- Leitura de falhas de comunicação ou sinal inválido.

---

## 9. Procedimentos de Diagnóstico
1. Verificar alimentação e conexão no conector do sensor;
2. Girar o volante e observar resposta no scanner;
3. Realizar calibração via scanner após alinhamento da direção;
4. Inspecionar danos no chicote ou na estrutura da coluna de direção;
5. Substituir o sensor se não responder corretamente.

---

## 10. Observações
- É essencial recalibrar o sensor após alinhamento da direção;
- Pode estar integrado ao módulo de direção elétrica em veículos modernos.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

