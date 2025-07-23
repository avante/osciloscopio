# Ficha Técnica – Válvula Borboleta Eletrônica (ETB)

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Controle da Admissão / Aceleração Eletrônica

---

## 1. Identificação
Atuador responsável pelo controle da entrada de ar no motor através da abertura de uma válvula borboleta comandada eletronicamente pela ECU, eliminando o uso de cabo mecânico.

---

## 2. Descrição Geral
A válvula borboleta eletrônica (Electronic Throttle Body – ETB) integra um motor elétrico, engrenagens de redução e sensores de posição. A ECU calcula a abertura ideal com base na posição do pedal do acelerador e outras variáveis operacionais.

---

## 3. Características Construtivas
- Corpo em alumínio ou plástico com duto e eixo da borboleta;
- Motor elétrico DC acoplado a engrenagens de acionamento;
- Duplo sensor de posição da borboleta (TPS integrado);
- Conector de 6 vias (motor + sensores);
- Sistema de retorno por mola (fail-safe);
- Pode ter aquecimento em aplicações diesel para controle de emissões.

---

## 4. Funções
- Controlar a abertura da borboleta com precisão;
- Melhorar o conforto e a eficiência no controle de torque;
- Eliminar o cabo de acelerador mecânico;
- Integrar funções como controle de tração, marcha lenta e cruise control.

---

## 5. Interações Sistêmicas
- **Pedal do Acelerador (Sensor APP):** Fornece sinal de demanda ao ETB;
- **ECU:** Controla o motor da borboleta com base em múltiplos parâmetros;
- **Sensor MAP/MAF:** Valida a resposta da borboleta e calcula a carga;
- **Sistema de Controle de Emissões:** Pode fechar a borboleta para gerar vácuo ou controlar recirculação de gases.

---

## 6. Defeitos Comuns
- Borboleta travada (sujeira ou carbonização);
- Motor com desgaste ou engrenagens danificadas;
- Divergência entre sensores de posição;
- Modo de emergência ativado (borboleta limitada);
- Falhas no chicote ou no conector.

---

## 7. Códigos DTC Associados (OBD-II)
- **P2100–P2119:** Diversas falhas relacionadas ao controle da borboleta;
- **P0120–P0124:** Problemas nos sensores de posição TPS integrados;
- **P2135:** Correlação incorreta entre sensores de posição;
- **P2111:** Borboleta travada aberta;
- **P2112:** Borboleta travada fechada.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal dos sensores de posição (TPS 1 e TPS 2);
- Forma de onda do motor da borboleta (PWM);
- Verificação de divergência ou resposta lenta.

### Multímetro
- Verificação de alimentação (5 V e 12 V);
- Teste de continuidade do motor e sensores;
- Medição de resistência das bobinas.

### Scanner
- Leitura da posição da borboleta e do pedal do acelerador;
- Teste de atuador (acionamento pelo scanner);
- Leitura de falhas e modo de emergência.

---

## 9. Procedimentos de Diagnóstico
1. Verificar atuação da borboleta via scanner (comando de atuador);
2. Observar a resposta da borboleta em relação ao pedal;
3. Medir sinais dos sensores com osciloscópio e checar coerência;
4. Verificar chicote quanto a resistência, curto ou mau contato;
5. Limpar o corpo da borboleta em caso de carbonização excessiva.

---

## 10. Observações
- Após a limpeza, alguns sistemas requerem reaprendizado da posição da borboleta via scanner;
- Falhas na ETB ativam modo de segurança com limitação de aceleração.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

