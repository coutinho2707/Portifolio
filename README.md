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

### Imagem 1
![17431213604808436462126157225813](https://github.com/user-attachments/assets/d428cb0c-936c-46c0-a5b6-21ed8e23f54e)

### Imagem 2
![modelo_pratico2](https://github.com/user-attachments/assets/e36a06b7-9fd2-4170-b7bc-e72aec55ae7b)

### Iamgem 3
![modelo_pratico3](https://github.com/user-attachments/assets/9e846616-16a6-4307-81d2-e81ae317a214)

• O regulador 7805 está posicionado no centro da protoboard, com o capacitor eletrolítico ao seu lado para filtragem.

• A ponte retificadora é montada com diodos discretos.

• Pequenos capacitores cerâmicos são usados para reduzir ruídos.

• O LED vermelho (com resistor de 220Ω) atua como um indicador de que a saída está funcionando.

### Teste com Multímetro

Na segunda imagem, um multímetro digital está sendo utilizado para medir a tensão de saída do circuito. O visor mostra 4.99V. Já na segunda imagem, O visor mostra 9.83V, porém está incorreto de deveria marcar 12.00V no regulador testado.

# PCB
![modelo_pcb](https://github.com/user-attachments/assets/aed163bd-fa3c-4700-8d5f-0fa3a7c1ae20)

### Componentes Identificados:

• J2: Conector de entrada de energia ou sinal, com dois pinos.

• U1: Circuito integrado com três pinos, possivelmente um regulador de tensão ou outro componente ativo.

• D1: Diodo, com identificação dos terminais ânodo (A) e cátodo (K).

• BR1: Ponte retificadora, usada para converter corrente alternada (AC) em corrente contínua (DC).

• AC1, AC2: Terminais para conexão de corrente alternada.

• C1, C2, C3: Capacitores eletrolíticos, com polaridade indicada (+).

• R1: Resistor com terminais 1 e 11.
Características do Layout:

• Dimensões: A placa tem 50mm de largura e 30mm de altura.

• Camadas: Camada única (apenas trilhas na parte inferior).

• Trilhas: Representadas em azul, interligando os componentes.
Furos e Pads: Em roxo, onde os componentes serão soldados.

• Bordas da Placa: Delimitadas pelas linhas ciano.

• Grade: Grade de pontos preta para auxiliar no posicionamento dos componentes.

# Visualização 3D do PCB

### Imagem 1:
![modelo_3D](https://github.com/user-attachments/assets/1f1a32a4-6a90-4bd3-9482-bbca36c9de75)

A primeira imagem exibe a montagem dos componentes no PCB:

• O grande componente preto na esquerda é a ponte retificadora (BR1).

• O componente cilíndrico próximo a ele é um capacitor eletrolítico (C1).

• Os capacitores cerâmicos C2 e C3 estão posicionados ao lado.

• No centro superior, há um regulador de tensão (U1) com dissipador de calor.

• À direita, um resistor (R1) está conectado a um pequeno conector.

• A placa mede 50mm x 30mm, conforme indicado nas dimensões.

### Imagem 2
![modelo_3D2](https://github.com/user-attachments/assets/d251649e-6c79-48ed-a046-f083796182df)

A segunda imagem mostra a parte traseira da PCB, onde estão as trilhas condutoras
