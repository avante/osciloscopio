# Ficha Técnica – Atuador do Motor de Partida

**Tipo:** Atuador  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Partida / Motor Elétrico

---

## 1. Identificação
O motor de partida é responsável por acionar mecanicamente o motor de combustão interna durante o arranque, girando o virabrequim até que o motor entre em funcionamento por conta própria.

---

## 2. Descrição Geral
Trata-se de um motor elétrico de corrente contínua (DC) com alto torque, acoplado a um sistema de engrenagem e um solenoide. Este solenoide empurra o pinhão do motor contra a cremalheira do volante do motor, engatando temporariamente durante o acionamento.

---

## 3. Características Construtivas
- Motor elétrico com escovas e induzido;
- Solenoide de acionamento com bobinas de tração e retenção;
- Pinhão com mecanismo de avanço (Bendix ou engrenagem planetária);
- Caixa de redução (em alguns modelos);
- Corpo metálico com isolamento térmico;
- Terminal de alimentação direta da bateria (B+) e sinal da chave (50).

---

## 4. Funções
- Gerar torque inicial para partida do motor;
- Engrenar o pinhão à cremalheira de forma temporária;
- Desacoplar automaticamente após o arranque;
- Garantir partidas rápidas e confiáveis mesmo em baixas temperaturas.

---

## 5. Interações Sistêmicas
- **Chave de ignição / botão de partida:** Aciona o relé do motor de partida;
- **ECU (em veículos modernos):** Pode comandar o relé de partida em função de sensores;
- **Bateria:** Fornece energia de alta corrente;
- **Sensor de rotação (CKP):** Monitora sucesso da partida.

---

## 6. Defeitos Comuns
- Escovas gastas ou com mau contato;
- Solenoide com falha no avanço do pinhão;
- Enrolamento em curto ou aberto;
- Pinhão gasto ou engrenando mal;
- Oxidação nos terminais de alimentação.

---

## 7. Códigos DTC Associados (OBD-II)
- **P0615:** Circuito de comando do motor de partida;
- **P0616 / P0617:** Tensão baixa/alta no terminal de acionamento (50);
- **P2534:** Partida não autorizada (em veículos com sistema imobilizador);
- **U0100 / U0140:** Comunicação perdida com ECU de partida (em sistemas com comando eletrônico).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise da corrente de pico durante o acionamento (padrão de partida);
- Verificação de queda de tensão no momento da partida.

### Multímetro
- Medição da tensão nos terminais B+ e 50 durante a partida;
- Verificação da continuidade das bobinas;
- Teste de queda de tensão entre bateria e motor.

### Scanner
- Leitura de falhas de partida ou comandos negados;
- Monitoramento de sinais do sistema start/stop ou imobilizador;
- Teste de atuação em veículos com comando eletrônico.

---

## 9. Procedimentos de Diagnóstico
1. Verificar estado da bateria e carga;
2. Medir tensão no terminal 50 durante a partida;
3. Avaliar consumo com alicate amperímetro;
4. Testar continuidade e resistência das bobinas do solenoide;
5. Remover o motor de partida e testar em bancada, se necessário.

---

## 10. Observações
- Em motocicletas, o sistema pode ser mais compacto, mas segue o mesmo princípio;
- Em veículos com sistema start-stop, o motor de partida pode ser reforçado ou integrado ao alternador (BAS/ISG).

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

