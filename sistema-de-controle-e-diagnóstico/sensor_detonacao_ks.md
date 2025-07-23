# Ficha Técnica – Sensor de Detonação (Knock Sensor - KS)

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Ignição / Combustão / Antidetonante

---

## 1. Identificação
O sensor de detonação (KS – Knock Sensor) detecta vibrações anormais no bloco do motor causadas pela detonação (combustão espontânea), permitindo à ECU ajustar o ponto de ignição para evitar danos ao motor.

---

## 2. Descrição Geral
Trata-se de um sensor piezoelétrico que converte vibrações mecânicas de frequência específica em sinais elétricos. Instalado geralmente no bloco do motor, capta as frequências características da batida de pino e envia essas informações à ECU.

---

## 3. Características Construtivas
- Elemento piezoelétrico encapsulado;
- Rosca metálica para fixação no bloco do motor;
- Corpo metálico com isolamento elétrico e térmico;
- Conector elétrico com 2 vias (sinal e terra);
- Alguns modelos possuem blindagem contra ruídos externos.

---

## 4. Funções
- Detectar a ocorrência de detonação (pré-ignição);
- Permitir o ajuste do ponto de ignição (retardo);
- Proteger o motor contra danos por combustão anormal;
- Auxiliar na adaptação do motor a diferentes qualidades de combustível;
- Monitorar o estado de operação do motor sob carga.

---

## 5. Interações Sistêmicas
- **ECU:** Analisa os sinais e ajusta a ignição;
- **Sensores de rotação e posição:** Sincronizam o momento da análise;
- **Sistema de ignição:** Atua para reduzir a detonação;
- **Mapas de ignição:** São corrigidos dinamicamente;
- **Sistema de diagnóstico:** Armazena falhas persistentes.

---

## 6. Defeitos Comuns
- Sensor com sinal ausente ou ruidoso;
- Conector oxidado ou com mau contato;
- Sensor solto ou com torque inadequado (afeta sensibilidade);
- Ruídos falsos por vibração excessiva do motor;
- Ruptura do cristal piezoelétrico.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0325:** Circuito defeituoso do sensor de detonação (Banco 1);
- **P0330:** Circuito defeituoso do sensor de detonação (Banco 2);
- **P0326, P0327, P0328:** Sinal fora de faixa;
- **P0332, P0333:** Falha de resposta do sensor.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal de frequência durante funcionamento sob carga;
- Identificação de ruídos anômalos ou ausência de resposta;
- Comparação entre bancos (se houver dois sensores).

### Multímetro
- Difícil avaliação direta (sinal AC de baixa amplitude);
- Verificação de continuidade do chicote;
- Teste de aterramento e resistência do circuito.

### Scanner
- Leitura de detonações detectadas em tempo real;
- Presença de DTCs relacionados a detonação;
- Monitoramento da estratégia de avanço de ignição.

---

## 9. Procedimentos de Diagnóstico
1. Verificar torque de aperto do sensor (geralmente 20-25 Nm);
2. Usar scanner para monitorar ocorrências de detonação;
3. Avaliar a resposta do motor com combustível de maior octanagem;
4. Testar o chicote e o aterramento;
5. Substituir por sensor compatível se o sinal estiver ausente.

---

## 10. Observações
- A presença de detonação é comum em cargas elevadas e combustível de má qualidade;
- O sensor de detonação é fundamental para a durabilidade do motor e desempenho otimizado.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

