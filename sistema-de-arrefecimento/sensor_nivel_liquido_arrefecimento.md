# Ficha Técnica – Sensor de Nível do Líquido de Arrefecimento

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Arrefecimento / Monitoramento de Segurança

---

## 1. Identificação
Sensor responsável por informar ao módulo de controle ou painel de instrumentos a presença ou ausência de líquido de arrefecimento no reservatório ou radiador, prevenindo danos por superaquecimento.

---

## 2. Descrição Geral
Pode operar por princípio de contato (flutuador com reed switch), condutividade (sensor resistivo), ou sensor óptico. Geralmente está instalado no reservatório de expansão e fornece um sinal digital (nível ok / baixo).

---

## 3. Características Construtivas
- Flutuador magnético com reed switch (modelo mais comum);
- Carcaça plástica com vedação tipo O-ring;
- Sensor resistivo ou capacitivo em modelos avançados;
- Conector de 2 vias (sinal e terra ou alimentação);
- Montagem direta no reservatório ou radiador.

---

## 4. Funções
- Detectar o nível mínimo de segurança do líquido de arrefecimento;
- Acionar luz de advertência no painel;
- Informar falhas no sistema de arrefecimento;
- Prevenir superaquecimento por vazamentos ou evaporação.

---

## 5. Interações Sistêmicas
- **Painel de Instrumentos / BCM:** Exibe alerta visual e/ou sonoro;
- **ECU:** Pode usar o dado para estratégia de proteção térmica;
- **Reservatório de Expansão:** Integra o sensor à sua estrutura;
- **Sensor ECT:** Trabalha em conjunto para informar condição crítica.

---

## 6. Defeitos Comuns
- Sinal fixo (nível sempre baixo ou sempre alto);
- Boia travada por sujeira ou detritos;
- Sensor com mau contato no conector;
- Falso positivo devido a flutuação do nível;
- Curto ou circuito aberto.

---

## 7. Códigos DTC Associados (OBD-II)
- Não padronizado no OBD-II genérico;
- Códigos específicos podem ser lidos via scanner OEM;
- Ex: **U0128:** Perda de comunicação com módulo de controle de arrefecimento (BCM).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Pouco utilizado, mas possível observar variação de sinal em sensores resistivos;
- Verificação de ruído ou oscilação falsa.

### Multímetro
- Teste de continuidade do reed switch (ON/OFF com variação de nível);
- Medição de tensão de sinal no conector (geralmente 0 V = nível baixo);
- Verificação da alimentação e integridade do chicote.

### Scanner
- Verificação da presença do sinal do sensor (em sistemas suportados);
- Leitura de alertas armazenados ou condições de falha;
- Monitoramento em tempo real em módulos BCM ou ECU avançados.

---

## 9. Procedimentos de Diagnóstico
1. Testar continuidade com o sensor dentro e fora do fluido;
2. Verificar o estado do conector e possíveis sinais de oxidação;
3. Confirmar se o alerta desaparece ao preencher o reservatório;
4. Medir tensão no conector e comparar com o estado do nível;
5. Substituir o sensor se houver leitura incorreta persistente.

---

## 10. Observações
- A falta de líquido no reservatório pode causar falhas graves por superaquecimento mesmo com o motor operando normalmente por alguns minutos;
- Sistemas mais modernos podem estimar o consumo de líquido por algoritmo, comparando ECT com tempo de funcionamento.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

