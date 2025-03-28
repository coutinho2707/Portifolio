# Portifolio
Atividade individual da matéria de Sistemas embarcados de 2025

# Esquemático
![17431212888425468133457041952315](https://github.com/user-attachments/assets/ebf88242-c4cf-4061-a32a-264d4c58ebe3)

### Componentes Principais:

• TR1 (Transformador): Reduz a tensão AC da rede elétrica para um nível adequado para retificação.

• BR1 (Ponte Retificadora): Converte a tensão AC do transformador em tensão DC pulsante.

• C1 (1µF): Atua como um capacitor de filtro para suavizar a tensão retificada.

• U1 (7805): Regulador de tensão que estabiliza a saída em 5V DC.

• C2 e C3 (22nF cada): Capacitores que reduzem ruídos e picos de tensão.

• R1 (220Ω): Resistor limitador de corrente para o LED indicador.

• D1 (LED Vermelho): Indica que a saída de 5V está ativa.

### Funcionamento:

• A corrente alternada é reduzida pelo transformador para um nível adequado.

• A ponte retificadora converte AC em DC pulsante.

• O capacitor C1 ajuda a suavizar essa tensão.

• O regulador 7805 estabiliza a saída em 5V DC.

• Os capacitores C2 e C3 reduzem ruídos.

• O LED D1, com o resistor R1, indica que o circuito está funcionando corretamente.

# Montagem prática 

• O regulador 7805 está posicionado no centro da protoboard, com o capacitor eletrolítico ao seu lado para filtragem.

• A ponte retificadora é montada com diodos discretos.

• Pequenos capacitores cerâmicos são usados para reduzir ruídos.

• O LED vermelho (com resistor de 220Ω) atua como um indicador de que a saída está funcionando.

### Teste com Multímetro

Na segunda imagem, um multímetro digital está sendo utilizado para medir a tensão de saída do circuito. O visor mostra 4.99V. Já na segunda imagem, O visor mostra 9.83V, porém está incorreto de deveria marcar 12.00V no regulador testado.

# PCB

### Componentes Identificados:

• J2 – Conector de entrada de energia ou sinal.

• BR1 – Ponte retificadora, usada para converter corrente alternada (AC) em corrente contínua (DC).

• C1, C2, C3 – Capacitores, provavelmente para filtragem e estabilização da tensão.

• U1 – Possível regulador de tensão ou microcontrolador.

• L1 – Indutor, possivelmente para um circuito de filtragem ou conversor DC-DC.

• R1 – Resistor de 30mm de comprimento, pode estar limitando corrente em um circuito específico.

### Especificações:

• Camadas: Single-layer (apenas trilhas na parte inferior).

• Trilhas: Representadas em azul, interconectando os componentes.

• Furos e Pads: Em roxo, onde os componentes serão soldados.

• Bordas da Placa: Delimitadas pelas linhas amarelas.

# Visualização 3D do PCB

### Imagem 1:

A primeira imagem exibe a montagem dos componentes no PCB:

• O grande componente preto na esquerda é a ponte retificadora (BR1).

• O componente cilíndrico próximo a ele é um capacitor eletrolítico (C1).

• Os capacitores cerâmicos C2 e C3 estão posicionados ao lado.

• No centro superior, há um regulador de tensão (U1) com dissipador de calor.

• À direita, um resistor (R1) está conectado a um pequeno conector.

• A placa mede 50mm x 30mm, conforme indicado nas dimensões.

### Imagem 2

A segunda imagem mostra a parte traseira da PCB, onde estão as trilhas condutoras
