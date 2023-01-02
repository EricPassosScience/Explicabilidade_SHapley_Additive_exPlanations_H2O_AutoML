# Explicabilidade de Modelos construídos com AutoML através de valores Shapley.


## O que é AutoML ?
AutoML  ou  Automated  Machine  Learning é  o  processo  de  automatizar  as  tarefas  do desenvolvimento  de  modelos  de  Machine  Learning.  Com  AutoML,  Cientistas  de  Dados podem criar modelos de ML com alta escala, eficiência e produtividade, ao mesmo tempo em que dão suporte à qualidade do modelo.

O  desenvolvimento  do  modelo  de  Machine  Learning  tradicional  tem  uso  intensivo  de recursos,  exigindo  conhecimento  de  domínio  significativo  e  tempo  para  produzir  e  comparar dezenas de modelos. Com AutoML, acelera-se o tempo necessário para obter modelos de ML prontos para produção com grande facilidade e eficiência.

## O que são os valores SHAPE? 
Por outro lado, SHAP – que significa SHpley Additive exPlanations –  provavelmente o estado da arte em explicabilidade de Machine Learning. Esse algoritmo foi publicado pela primeira vez em 2017 por Lundberg  e  Lee  (abaixo está  o link  do artigo  original)  e  é  uma  maneira  brilhante  de  fazer engenharia reversa da saída de qualquer algoritmo preditivo. 

Link - https://arxiv.org/abs/1705.07874

Em  poucas  palavras,  os  valores  SHAP  são  usados  sempre  que  você  tem  um  modelo complexo (pode ser um GBM, XGBoost, uma Rede Neural ou qualquer coisa que receba alguns recursos como  entrada  e  produz  algumas  previsões  como  saída)  e  você  deseja  entender  quais decisões o modelo tomou.

Os modelos preditivos respondem ao “quanto”. O SHAP responde ao “porquê”.

Os valores SHAP são baseados nos valores Shapley, um conceito vindo da teoria dos jogos. O que Shapley faz é quantificar a contribuição que cada jogador traz para o jogo. Ou seja, o  que  o  SHAP  faz  é  quantificar  a  contribuição  que cada  recurso  traz  para  a  previsão  feita  pelo modelo.

## Problema de negócio: 

Uma empresa produz itens hospitalares através de uma das suas fábricas no Brasil. Cada fábrica possui diversos equipamentos industriais que periodicamente requerem manutenção. A empresa coletou dados históricos associando diferentes métricas (variáveis preditoras) à necessidade de manutenção do equipamento (sim ou não). 

A ideia é ter um modelo de Machine Learning capaz de prever quando cada máquina vai requerer manutenção e assim evitar paradas não programadas. Mas antes de usar um modelo preditivo a alta gerência necessita compreender como o modelo faz as previsões e quais métricas tem maior impacto na previsão do modelo.Você foi convidado a fazer uma apresentação sobre o tema! 

Qual seria o processo para responder às dúvidas da alta gerência?

## ESPAÑOL:

# Explicabilidad de los modelos creados con AutoML a través de los valores de Shapley.

AutoML o aprendizaje automático automatizado es el proceso de automatización de las tareas de desarrollo de modelos de aprendizaje automático. Con AutoML, los científicos de datos pueden crear modelos de ML con alta escala, eficiencia y productividad, al mismo tiempo que respaldan la calidad del modelo.

El desarrollo de modelos de aprendizaje automático tradicional requiere muchos recursos, lo que requiere un conocimiento de dominio significativo y tiempo para producir y comparar docenas de modelos. Con AutoML, acelera el tiempo necesario para obtener modelos ML listos para la producción con gran facilidad y eficiencia.

SHAP, que significa SHpley Additive exPlanations, probablemente lo último en explicabilidad del aprendizaje automático. Este algoritmo fue publicado por primera vez en 2017 por Lundberg y Lee (a continuación se muestra el enlace al artículo original) y es una forma brillante de realizar ingeniería inversa en el resultado de cualquier algoritmo predictivo. Enlace - https://arxiv.org/abs/1705.07874

En pocas palabras, los valores SHAP se usan siempre que tenga un modelo complejo (podría ser un GBM, XGBoost, una red neuronal o cualquier cosa que tome algunas características como entrada y produzca algunas predicciones como salida) y desee comprender qué decisiones tomó la modelo.

Los modelos predictivos responden a “cuánto”. SHAP responde al “por qué”.

Los valores de SHAP se basan en los valores de Shapley, un concepto que proviene de la teoría de juegos. Lo que hace Shapley es cuantificar la contribución que cada jugador aporta al juego. Es decir, lo que hace SHAP es cuantificar la contribución que aporta cada característica a la predicción que hace el modelo.

## Problema de negocios:

Una empresa produce artículos para hospitales a través de una de sus fábricas en Brasil. Cada fábrica cuenta con varios equipos industriales que periódicamente requieren mantenimiento. La empresa recopiló datos históricos asociando diferentes métricas (variables predictoras) con la necesidad de mantenimiento de los equipos (si o no).

La idea es tener un modelo de Machine Learning capaz de predecir cuándo requerirá mantenimiento cada máquina y así evitar paradas no programadas. Pero antes de usar un modelo predictivo, la alta dirección debe comprender cómo el modelo hace predicciones y qué métricas tienen el mayor impacto en la predicción del modelo. ¡Ha sido invitado a dar una presentación sobre el tema!

¿Cuál sería el proceso para responder a las consultas de la alta dirección?
