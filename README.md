# Neumorphism Analog Clock - Soft UI Virtual Clock

Um componente de relógio analógico funcional, elegante e totalmente responsivo desenvolvido com HTML5, CSS3 e JavaScript. O projeto explora a fundo a estética do Neumorfismo (Neumorphism / Soft UI), utilizando um jogo refinado de múltiplas sombras opostas e sobreposições concêntricas para esculpir um mostrador tátil que simula um dispositivo mecânico real em sincronia com o horário do sistema.

## Tecnologias Utilizadas

* HTML5: Estruturação semântica da caixa do relógio, marcadores de horas e ponteiros estruturais.
* CSS3: Estilização completa, uso de formas perfeitamente circulares, paleta monocromática fosca e gerenciamento avançado de sombras projetadas (`box-shadow` externas e internas via `inset`).
* JavaScript: Lógica de captura do objeto nativo `Date`, cálculo matemático de ângulos e rotação dinâmica do DOM em tempo real.

## Funcionalidades e Técnicas Aplicadas

* Design Soft UI em Camadas Concêntricas: O corpo do relógio apresenta um anel externo extrudado em alto relevo e um disco central rebaixado em baixo relevo (`box-shadow: inset`), conferindo profundidade tridimensional realista à interface cinza-clara fosca.
* Mecânica Estatística de Ponteiros Customizados:
  * Ponteiro de horas: Mais curto e estilizado em tom azul fosco marcante.
  * Ponteiro de minutos: Mais longo, desenhado em preto sólido de alta precisão.
  * Ponteiro de segundos: Uma linha fina vermelha de alta vibração cromática, conferindo excelente legibilidade.
* Marcadores de Quadrante Minimalistas: Inclusão de traços geométricos finos distribuídos de forma perfeitamente radial na borda do mostrador, destacando os eixos principais (12h, 3h, 6h, 9h) em azul e os intermediários em preto.
* Sincronização e Rotação Contínua via DOM: Uso do método `setInterval` em JavaScript para atualizar as coordenadas de tempo a cada segundo. O script calcula dinamicamente a angulação geométrica de cada ponteiro ($360^\circ$ divididos pelas unidades de tempo) e injeta a propriedade `transform: rotate()` de forma performática.

## Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone 
