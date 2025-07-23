# Ficha Técnica – Sensor de Inclinação (Antiqueda)

**Tipo:** Sensor  
**Aplicação:** Motocicletas (M)  
**Categoria:** Sistema de Segurança / Interrupção de Motor

---

## 1. Identificação
Sensor de segurança presente em motocicletas, responsável por detectar inclinação excessiva (queda) e cortar o funcionamento do motor automaticamente, evitando danos ou agravamento do acidente.

---

## 2. Descrição Geral
Trata-se de um sensor inercial (geralmente do tipo MEMS ou de mercúrio) que detecta a inclinação da motocicleta com base na força gravitacional. Quando o sensor identifica um ângulo além do limite seguro (tipicamente >55° a 65°), ele envia um sinal de desligamento para a ECU.

---

## 3. Características Construtivas
- Sensor MEMS (Microelectromechanical Systems) ou ampola de mercúrio;
- Carcaça plástica selada contra umidade e vibração;
- Montagem com orientação específica (vertical);
- Conector elétrico com 2 ou 3 vias (sinal, alimentação, terra);
- Pode estar incorporado ao módulo IMU em motos modernas.

---

## 4. Funções
- Detectar queda ou inclinação crítica da motocicleta;
- Cortar a alimentação do motor para segurança;
- Acionar alarme (em alguns modelos);
- Impedir partida após queda, exigindo reset manual (em alguns sistemas).

---

## 5. Interações Sistêmicas
- **ECU / ECM:** Responsável por desligar o motor ao receber sinal de inclinação;
- **Sistema de injeção e ignição:** Interrompidos após queda;
- **Interruptores de segurança:** Funciona em conjunto com o descanso lateral e corta-corrente;
- **Módulo IMU (em motos modernas):** Inclui outros sensores inerciais.

---

## 6. Defeitos Comuns
- Falsos positivos por vibração excessiva;
- Sensor desalinhado ou mal fixado;
- Falha interna no sensor MEMS ou ampola quebrada;
- Conector solto ou oxidado;
- Corte de motor mesmo sem queda real.

---

## 7. Códigos DTC Associados (quando aplicável)
- **P1685:** Interrupção por sensor de inclinação;
- **U0123:** Falha de comunicação com módulo inercial;
- **Códigos específicos por fabricante podem ser utilizados.**

---

## 8. Métodos de Avaliação

### Osciloscópio
- Pouco aplicável, sinal digital de estado (ativado/desativado);
- Possível identificar mudança abrupta na linha de sinal após queda simulada.

### Multímetro
- Verificação de tensão em repouso e após inclinação simulada;
- Teste de continuidade e aterramento.

### Scanner
- Leitura do status do sensor (queda detectada ou normal);
- Presença de códigos de falha;
- Reset de falha para partida após corte automático.

---

## 9. Procedimentos de Diagnóstico
1. Simular inclinação para verificar resposta do sensor;
2. Verificar posicionamento e fixação correta;
3. Avaliar chicote e conectores com multímetro;
4. Usar scanner para detectar estado atual e falhas registradas;
5. Substituir sensor se apresentar instabilidade ou falsos positivos.

---

## 10. Observações
- Muitos sistemas exigem desligar e ligar a chave para reinicializar o sensor após corte por inclinação;
- Em motos esportivas, pode estar integrado com sensores de curva e frenagem ABS.

---

**Legenda:**  
M = Motocicletas

