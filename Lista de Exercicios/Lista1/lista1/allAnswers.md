**1. Defina em suas próprias palavras:
    a. Inteligência.
    b. Inteligência artificial.
    c. Aprendizado de máquina.**
    
R: 
    a) Inteligência é uma habilidade mental que determina a capacidade de algum ser vivo interpretar e se adaptar a novas circunstâncias.
    b) Inteligência artificial é um ramo de pesquisa que se dedica a desenvolver técnicas que possam simular o raciocínio humano numa máquina.
    c) O aprendizado de máquina é uma das aplicações de Inteligência Artificial, baseada na ideia de que as máquinas devem ter acesso a dados e aprender baseando-se nesses dados
    
    
    
**2. Diz-se que um programa de computador aprende com a experiência E com relação a alguma tarefa T e alguma medida de desempenho D, se seu desempenho em T, medido por D, melhorar com a experiência E. Suponha que um algoritmo de aprendizado seja alimentado com muitos dados climáticos históricos, e aprenda a prever o tempo. Qual seria uma escolha razoável para D?
    a. A probabilidade de prever corretamente o tempo de uma data futura.
    b. A tarefa de previsão do tempo.
    c. O processo do algoritmo que examina uma grande quantidade de dados climáticos históricos.
    d. Nenhum das alternativas anteriores.**
    
R: a) A probabilidade de prever corretamente o tempo de uma data futura
    
    
    
**3. Diz-se que um programa de computador aprende com a experiência E com relação a alguma tarefa T e alguma medida de desempenho D, se seu desempenho em T, medido por D, melhorar com a experiência E. Suponha que você esteja trabalhando numa agência meteorológica e deseje treinar um algoritmo de aprendizado com dados climáticos históricos para que este preveja o tempo. Neste caso, o que seriam T, E?**

R: A tarefa T" seria a tarefa de previsão do tempo. A experiência "E" seria o processo de examinar o histórico dos dados climáticos
    
    
    
**4. Suponha que você esteja trabalhando em uma agência meteorológica com previsão do tempo, e que a agência faça uma das três previsões para o clima de cada dia: ensolarado, nublado ou chuvoso. Você deseja usar um algoritmo de aprendizado para prever o tempo de amanhã. Você trataria essa tarefa como uma tarefa de classificação ou de regressão? Justifique sua escolha.**

R: Trataria essa tarefa como um problema de classificação porque a possibilidade de previsões é finita (ensolarado, nublado e chuvoso)
    
    
    
**5. Suponha que você esteja trabalhando em uma empresa de investimentos na previsão do mercado de ações e gostaria de prever o preço de uma determinada ação amanhã (medido em reais). Você deseja usar um algoritmo de aprendizado para isso. Você trataria essa tarefa como uma tarefa de classificação de regressão? Justifique sua escolha.**

R: Trataria essa tarefa como um problema de regressão porque a possibilidade de previsões é infinita (está limitada a números reais).
    
    
    
**6. Que tipo de algoritmo de aprendizado de máquina você usaria para permitir que um robô andasse em vários terrenos desconhecidos? Dica: o robô precisa, através de sensores, entender o estado do terreno (buracos, paredes, subidas íngremes, etc.) e baseado neste estado executar ações (se mover para frente/trás, esquerda/direita) e dependendo do resultado dessas ações decidir quais são as ações corretas para que ele ande sem problemas pelo terreno.**

R: Usaria um algoritmo de aprendizado por reforço como por exemplo o Q-Learning
    
    
    
**7. Que tipo de algoritmo de aprendizado de máquina você usaria para segmentar clientes de uma grande empresa de e-commerce em vários grupos? Dica: você pode ter os grupos já definidos e treinar um modelo para alocar novos clientes a esses grupos ou querer descobrir diferentes tipos de grupos de clientes.**

R: Usaria um algoritmo de clusterização como por exemplo o k-médias (k-means)
    
    
    
**8. Pesquise a literatura sobre IA/ML e descubra se as seguintes tarefas podem ser solucionadas por computadores. Se as tarefas puderem ser solucionadas, descreva sucintamente o algoritmo/método de IA/ML utilizado e como o problema é solucionado. Utilize o link abaixo como ponto de partida para sua pesquisa:
https://mlc.committees.comsoc.org/research-library/
    a. Alocação de recursos em redes móveis (e.g., LTE, 5G-NR, etc.).
    b. Mitigação de colisões em redes sem-fio e móveis.
    c. Projeto e otimização de esquemas de modulação e codificação.
    d. Sensoriamento espectral.
    e. Posicionamento e localização em ambientes indoor.
    f. Roteamento de redes.
    g. Detecção e estimação de canal em sistemas de transmissão ópticos.
    h. Pré-distorção digital de não-linearidades de front-ends de RF.
    i. Segurança e robustez em redes de comunicação.**

R: 
    a) Alocação de recursos em redes móveis (e.g., LTE, 5G-NR, etc.): Em **"Deep learning power allocation in massive MIMO"**(<https://arxiv.org/abs/1812.03640>), uma Rede Neural foi treinada para aprender a mapear as diferentes posições dos equipamentos de usuários e as políticas optimas de alocação de energia. Essa informação é depois usada para prever os perfis de alocação de energia para um conjunto de posições de equipamentos de usuários. A abordagem proposta por este trabalho não requer o cálculo de qualquer média estatística (que seria necessário na maioria dos métodos tradicionais), assegurando um desempenho quase ideal.
    b) Mitigação de colisões em redes sem-fio e móveis: Em **"Decentralized Spectrum Learning for IoT Wireless Networks Collision Mitigation"** (<https://ieeexplore.ieee.org/abstract/document/8804828>), um algoritmo de treinamento por reforço é usado para mitigar colisões em nas faixas ISM não licenciadas. Isso é feito numa rede LoRaWAN sem acrescentar overhead tanto no processamento como na rede, portanto a técnica é compatível com dispositivos IoT e não requer qualquer modificação na rede LoRaWAN. Do ponto de vista do algoritmo de aprendizado, um sucesso ocorre quando o dispositivo IoT recebe uma mensagem de sucesso (ACK) da rede.
    c. Projeto e otimização de esquemas de modulação e codificação: Em **"Joint Transceiver Optimization for Wireless Communication PHY Using Neural Network"** (<https://ieeexplore.ieee.org/document/8664650>) uma rede neural convulucional é usada para optimizar a comunicação na camada física do transmissor e receptor em canais com desvanecimento. O sistema é treinado usando dois canais com desvanecimento Rayleigh e um AWGN. A solução proposta realiza o papel de modulação, equalização e demodulação.
    d. Sensoriamento espectral: Em **"Generative Adversarial Learning for Spectrum Sensing"** (<https://ieeexplore.ieee.org/document/8422223>), uma GAN (Generative Adversarial Network) é usada para optimizar o sensoriamento espectral e consequentemente as janelas de transmissão. A GAN é usada para gerar dados sintéticos de treinamento porque um dos maiores problemas de usar abordagens de IA em radio cognitivo é a pouca quantidade de dados a disposição. A principal vantagem da técnica usada é que ela não depende de um modelo matemático, portanto é bastante flexível, podendo ser aplicada em outros cenários de rádio cognitivo tais como aqueles em que o receptor escuta vários canais em simultâneo com o objectivo de detectar se o canal está ocioso. Tanto o gerador como o discriminador são treinados por meio usando a técnica "backpropagation of error".
    e. Posicionamento e localização em ambientes indoor: Em **"CSI-Based Fingerprinting for Indoor Localization: A Deep Learning Approach"** (<https://ieeexplore.ieee.org/abstract/document/7438932>), um sistema de localização indoor usa deep-learning para analisar a informação do estado do canal, do inglês Channel State Information (CSI) e usa-lo como uma impressão digital para identificar e localizar dispositivos num ambiente indoor. Durante a fase de treinamento, algoritmos de deep learning são usados para ajustar todos os pesos e criar as "impressões digitais". Além disso, um algoritmo de aprendisado greedy que faz uso de uma pilha restrita de máquinas Bolzmann é usado para treinar cada uma das camadas, reduzindo a complexidade do treinamento. Uma vez que o treinamento for concluído, a rede neural é capaz de estimar a localização do dispositivo.
    f. Roteamento de redes: Em **"SIR: A New Wireless Sensor Network Routing
Protocol Based on Artificial Intelligence"** (<https://link.springer.com/chapter/10.1007/11610496_35>), um algoritmo de roteamento voltado a QoS (Quality of Service) é treinado usando uma rede neural não supervisionada baseada na técnica Self-organizing Map (SOM), em que cada um dos nós da rede implementa a rede neural mencionada para que a rede possa prover maior qualidade de serviço.
    g. Detecção e estimação de canal em sistemas de transmissão ópticos: Em **"Symbol detection and channel estimation using neural networks in optical communication systems"** (<https://ieeexplore.ieee.org/document/8761449>) uma rede neural é usada para detectar e estimar os símbolos transmitidos que não dependem do modelo de um canal. O trabalho é baseado em simulação e os dados de treinamento são gerados de acordo a uma expressao matemática.
    h. Pré-distorção digital de não-linearidades de front-ends de RF: Em **"Adaptive Digital Predistortion of Wireless Power Amplifiers/Transmitters Using Dynamic Real-Valued Focused Time-Delay Line Neural Networks"** (<https://ieeexplore.ieee.org/document/5340581>) uma técnica de pré-distorção digital baseada em redes neurais treinadas por meio do algoritmo de retropropagação Levenberg-Marquardt é validada num ambiente real.   
    i. Segurança e robustez em redes de comunicação: Em **"Cyberattack Detection in Mobile Cloud Computing: A Deep Learning Approach"** (<https://ieeexplore.ieee.org/document/8376973>), os autores desenvolveram uma framework para detectar e prevenir ataques cibernéticos usando algoritmos de Deep learning, em que uma rede neural passa por um processo de treinamento composto por duas fases i) pré-treinamento, no qual dados não rotulados são usados e pesos são atribuídos aos atributos. ii) "Afinação", em que dados rotulados são inseridos para refinar o algoritmo, e os pesos anteriores são refinados para melhor discriminação. Após a conclusão do treinamento, o modelo de deep learning com os pesos de treino foi capaz de detectar com ataques com uma acuracia superior a 90% em três datasets distintos.