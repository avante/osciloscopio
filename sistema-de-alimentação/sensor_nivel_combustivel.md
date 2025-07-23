# Ficha Técnica – Sensor de Nível de Combustível

**Tipo:** Sensor  
**Aplicação:** Linha Leve (L), Linha Pesada (P), Motocicletas (M)  
**Categoria:** Sistema de Alimentação e Combustível

---

## 1. Identificação
Sensor responsável por informar o nível de combustível presente no tanque ao painel de instrumentos ou ao módulo de controle eletrônico (BCM ou ECU).

---

## 2. Descrição Geral
Utiliza um mecanismo de bóia acoplada a um potenciômetro ou sensor resistivo. A variação da posição da bóia altera a resistência elétrica do circuito, que é interpretada como nível de combustível.

---

## 3. Características Construtivas
- Bóia articulada presa a uma haste;
- Resistência variável (potenciômetro ou sensor Hall, dependendo do modelo);
- Montado junto ao módulo da bomba (submerso) ou externamente no tanque;
- Faixa de resistência: varia conforme fabricante (ex: 10 a 180 ohms);
- Em motocicletas, pode ser do tipo magnético (sensor reed).

---

## 4. Funções
- Informar à central ou painel o volume de combustível presente;
- Permitir estratégias de reserva e autonomia no computador de bordo;
- Em veículos modernos, pode fornecer informações para o cálculo de consumo e emissões.

---

## 5. Interações Sistêmicas
- **Painel de Instrumentos:** Exibe a leitura do sensor para o condutor;
- **BCM / ECU:** Pode usar os dados para alertas, controle de evaporação ou ajuste de partida a frio;
- **Módulo da Bomba de Combustível:** Em alguns casos, integra os sensores ao conjunto.

---

## 6. Defeitos Comuns
- Leitura travada (sensor encharcado, bóia emperrada);
- Indicação oscilante ou errática (contato intermitente);
- Circuito aberto (resistência infinita);
- Aterramento deficiente;
- Deterioração dos trilhos resistivos ou sensor reed defeituoso.

---

## 7. Códigos DTC Associados (OBD-II)
- Em geral, esse sensor não gera DTC diretamente via OBD-II;
- Veículos com rede CAN podem apresentar:
  - **U0140:** Perda de comunicação com BCM (onde o sensor pode estar conectado);
  - Falhas específicas visíveis via scanner da montadora.

---

## 8. Métodos de Avaliação

### Osciloscópio
- Pouco comum, mas possível analisar a transição de sinal (em sensores digitais);
- Verificar ruídos, quedas bruscas ou falhas de continuidade.

### Multímetro
- Medição de resistência com o sensor fora do tanque (movimentar bóia);
- Verificação de aterramento e alimentação (se aplicável);
- Faixa de resistência deve ser progressiva e contínua.

### Scanner
- Em veículos com suporte: leitura do valor de nível em litros ou percentual;
- Teste de painel (verificar variação da indicação);
- Verificação de falhas de comunicação com a unidade correspondente.

---

## 9. Procedimentos de Diagnóstico
1. Verificar se o painel responde à movimentação da bóia;
2. Medir a resistência com o multímetro (comparar com a tabela do fabricante);
3. Verificar sinais de oxidação ou desgaste dos contatos;
4. Testar continuidade e resistência no chicote;
5. Confirmar leitura via scanner (se disponível).

---

## 10. Observações
- Veículos com tanques em formatos irregulares podem apresentar flutuação da leitura em aclives/declives;
- Alguns sistemas usam dois sensores (tanques com divisória), cuja leitura combinada é interpretada pela ECU ou BCM.

---

**Legenda:**  
L = Linha Leve  
P = Linha Pesada  
M = Motocicletas

