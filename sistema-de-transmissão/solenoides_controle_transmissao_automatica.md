# Ficha Técnica – Solenoides de Controle da Transmissão Automática

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Transmissão / Gerenciamento Eletrônico Hidráulico

---

## 1. Identificação
Dispositivos eletromecânicos responsáveis por controlar a aplicação da pressão hidráulica para engatar ou liberar marchas dentro da transmissão automática, de acordo com os comandos da TCM ou ECU.

---

## 2. Descrição Geral
As solenoides de transmissão são válvulas controladas eletricamente que direcionam fluido sob pressão a determinados circuitos hidráulicos. Elas podem ser do tipo on/off (binárias) ou moduladoras (proporcionais via PWM), controlando o momento e a firmeza da troca de marcha.

---

## 3. Características Construtivas
- Carcaça metálica cilíndrica com núcleo móvel;
- Bobina elétrica para acionamento;
- Filtro interno para proteção contra partículas;
- Conector de 2 vias (alimentação e sinal);
- Montadas no corpo de válvulas da transmissão;
- Compatíveis com óleo ATF (resistência química e térmica).

---

## 4. Funções
- Direcionar pressão hidráulica para acionamento de embreagens e freios internos;
- Controlar a pressão de linha e pressão de troca;
- Modificar o comportamento da transmissão conforme modo de condução;
- Permitir bloqueio e liberação do conversor de torque;
- Atuar nas estratégias de proteção e economia de combustível.

---

## 5. Interações Sistêmicas
- **TCM (Transmission Control Module):** Controla as solenoides via mapeamento dinâmico;
- **Sensores de rotação e posição:** Ajustam o momento ideal da atuação;
- **Conversor de Torque:** Solenoides específicas para controle de lock-up;
- **Sensor de pressão interna (quando aplicável):** Feedback de atuação.

---

## 6. Defeitos Comuns
- Solenoide travada (aberta ou fechada);
- Bobina queimada ou com resistência fora da faixa;
- Filtro entupido por contaminação de fluido;
- Ruído ou oscilação na válvula moduladora;
- Comunicação incorreta com o TCM.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0750 a P0779:** Falhas nas solenoides A, B, C da transmissão;
- **P0745:** Falha na pressão da linha de controle;
- **P2714:** Solenoide de pressão hidráulica travada ou fora da faixa;
- **U0101:** Perda de comunicação com o TCM.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Verificação do sinal PWM em válvulas moduladoras;
- Análise de corrente de atuação e forma de onda;
- Identificação de falhas intermitentes ou de resposta lenta.

### Multímetro
- Medição de resistência da bobina (geralmente 5 a 20 Ω);
- Teste de continuidade e curto entre pinos;
- Verificação de alimentação (12 V ou 5 V, conforme projeto).

### Scanner
- Leitura do estado das válvulas e testes de acionamento;
- Monitoramento da pressão de linha e de troca;
- Detecção de falhas intermitentes em marcha.

---

## 9. Procedimentos de Diagnóstico
1. Identificar a válvula com falha através dos DTCs;
2. Verificar resistência da bobina com multímetro;
3. Aplicar teste funcional com scanner (se disponível);
4. Usar osciloscópio para observar atuação dinâmica;
5. Avaliar a qualidade do fluido ATF e presença de contaminantes.

---

## 10. Observações
- Solenoides defeituosas podem causar trancos, falta de engate ou funcionamento em modo de emergência;
- A substituição geralmente exige drenagem do óleo e acesso ao corpo de válvulas.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

