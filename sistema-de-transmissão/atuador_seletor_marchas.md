# Ficha Técnica – Atuador do Seletor de Marchas

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P)  
**Categoria:** Sistema de Transmissão / Controle de Engrenagens

---

## 1. Identificação
Dispositivo eletromecânico responsável por selecionar eletronicamente a posição das engrenagens na transmissão, substituindo a alavanca mecânica tradicional em sistemas automatizados ou robotizados.

---

## 2. Descrição Geral
O atuador do seletor de marchas opera movendo os mecanismos de engate dentro da caixa de câmbio conforme comando da ECU ou TCM. Pode utilizar motores elétricos de passo, servo motores ou solenóides lineares, dependendo do sistema.

---

## 3. Características Construtivas
- Motores elétricos ou solenóides de curso;
- Engrenagens ou eixos de tração para movimentação das engrenagens;
- Sensor de posição integrado (hall ou potenciômetro);
- Conector elétrico com múltiplos pinos;
- Carcaça resistente à vibração e temperatura;
- Montagem externa ou interna à carcaça da transmissão.

---

## 4. Funções
- Acionar as engrenagens correspondentes à marcha selecionada;
- Realizar trocas de marcha de forma automatizada;
- Trabalhar em conjunto com o atuador de embreagem e ECU;
- Executar marcha a ré, neutro e drive automaticamente;
- Auxiliar na estratégia de emergência (modo reserva).

---

## 5. Interações Sistêmicas
- **TCM / ECU:** Controla o momento e a posição do seletor;
- **Sensores de rotação e posição:** Coordenam o momento da troca;
- **Atuador da embreagem:** Opera em sincronia para evitar trancos;
- **Painel de instrumentos:** Informa marcha engatada;
- **Freio de estacionamento eletrônico:** Pode impedir trocas incorretas.

---

## 6. Defeitos Comuns
- Motor travado ou engrenagens desgastadas;
- Sensor de posição com leitura incorreta;
- Mau contato ou falha no chicote;
- Acúmulo de sujeira ou detritos internos;
- Erro de sincronismo com os demais atuadores.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0906 a P0915:** Falhas na atuação ou sinal do seletor;
- **P182E:** Falha de posição do seletor de marchas;
- **U0101:** Perda de comunicação com TCM;
- **P0810:** Desalinhamento do mecanismo de seleção.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Monitoramento do sinal de retorno do sensor de posição;
- Avaliação da corrente de atuação do motor;
- Verificação de estabilidade do sinal durante trocas.

### Multímetro
- Medição de tensão de alimentação e sinal;
- Teste de resistência do motor ou solenóide;
- Verificação de continuidade no chicote e conector.

### Scanner
- Leitura da marcha atual e posição do seletor;
- Comando manual de troca (teste de atuador);
- Leitura de falhas presentes e armazenadas.

---

## 9. Procedimentos de Diagnóstico
1. Verificar alimentação elétrica e aterramento do atuador;
2. Medir sinal do sensor de posição e alimentação;
3. Comandar seletor pelo scanner (quando disponível);
4. Observar sincronismo com outros atuadores (embreagem);
5. Verificar fixação e ausência de obstruções mecânicas.

---

## 10. Observações
- O desalinhamento do seletor pode impedir o veículo de sair do neutro;
- Após substituição, muitos sistemas exigem calibração com scanner OEM.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada

