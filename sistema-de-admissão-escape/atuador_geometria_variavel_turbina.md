# Ficha Técnica – Atuador de Geometria Variável da Turbina

**Tipo:** Atuador  
**Aplicação:** Linha Pesada (P)  
**Categoria:** Sistema de Admissão Forçada / Controle de Pressão de Turbo

---

## 1. Identificação
Atuador responsável por controlar a abertura das palhetas móveis da turbina de geometria variável (VGT – Variable Geometry Turbocharger), otimizando o fluxo dos gases de escape e a pressão do turbo em diferentes regimes de rotação.

---

## 2. Descrição Geral
O sistema VGT utiliza palhetas móveis no alojamento da turbina, que variam sua posição para modificar a área de passagem dos gases de escape. O atuador pode ser pneumático, elétrico ou eletrônico (com feedback de posição), comandado pela ECU ou por módulo de controle dedicado.

---

## 3. Características Construtivas
- Atuador pneumático com diafragma (tradicional) ou motor elétrico com engrenagens;
- Sensor de posição integrado (em atuadores eletrônicos);
- Conector de 3 a 6 vias (versões eletrônicas);
- Fixação por haste ligada ao conjunto de palhetas da turbina;
- Materiais resistentes a alta temperatura e vibração.

---

## 4. Funções
- Controlar a pressão de sobrealimentação (boost);
- Melhorar o torque em baixas rotações e a potência em altas;
- Reduzir o turbo lag e emissões de NOx;
- Proteger o motor contra sobrepressão.

---

## 5. Interações Sistêmicas
- **ECU ou Módulo VGT:** Controla a posição do atuador com base na carga e rotação;
- **Sensor MAP e Sensor de Fumaça (Smoke Limiter):** Usados para calcular o ponto ideal de atuação;
- **Sensor de Posição do Atuador:** Fornece feedback para controle fechado;
- **Sistema EGR e DPF:** Interagem com o VGT para controle de emissões.

---

## 6. Defeitos Comuns
- Atuador travado ou engrenagem gasta;
- Sensor de posição com leitura incorreta;
- Vazamento no sistema pneumático;
- Avaria no motor elétrico ou módulo de controle;
- Acúmulo de fuligem nas palhetas, impedindo movimento.

---

## 7. Códigos DTC Associados (OBD-II/HD OBD)
- **P2563:** Faixa/desempenho incorreto do sensor de posição do atuador VGT;
- **P003A:** Controle de posição da geometria variável – posição incorreta;
- **P0045:** Circuito de controle do atuador turbo VGT com falha;
- **P0234:** Pressão de sobrealimentação excessiva;
- **P0299:** Pressão de turbo insuficiente (boost abaixo do esperado).

---

## 8. Métodos de Avaliação

### Osciloscópio
- Análise do sinal PWM de comando (versão eletrônica);
- Observação do feedback do sensor de posição (forma de onda linear);
- Detecção de atraso, ruído ou falhas intermitentes.

### Multímetro
- Verificação da tensão de alimentação e sinal do sensor;
- Teste de resistência do motor ou solenoide de comando;
- Medição do sensor de posição.

### Scanner
- Leitura da posição do atuador em tempo real;
- Comando de teste de atuador (se disponível);
- Verificação de pressão de turbo e coerência com o comando do VGT;
- Leitura de falhas e parâmetros associados (boost, posição, fumaça).

---

## 9. Procedimentos de Diagnóstico
1. Verificar a movimentação da haste do VGT durante o teste de atuador;
2. Testar a resposta do sensor de posição com ignição ligada;
3. Medir o tempo de resposta e a estabilidade da posição com osciloscópio;
4. Checar obstruções mecânicas ou carbonização nas palhetas;
5. Comparar a pressão de sobrealimentação real com a esperada pela ECU.

---

## 10. Observações
- O acúmulo de fuligem é uma das principais causas de falha em sistemas VGT;
- Em alguns veículos, o sistema VGT trabalha junto ao freio motor, influenciando seu desempenho.

---

**Legenda:**  
P = Linha Pesada

