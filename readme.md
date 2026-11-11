BLOCO 1: Joan é péssima & O Dilema das Redes (Privacidade, Dados e Redes)
Questão 1 [Ciência de Dados]
Tema: Pré-processamento de dados e Normalização Min-Max.   

Remoção de colunas com dados sensíveis (df.drop): Antes de alimentar qualquer modelo preditivo ou sistema quântico, a eliminação de identificadores diretos (como nomes, documentos e fotos) é obrigatória para cumprir diretrizes de privacidade (ex.: LGPD) e garantir a anonimização dos indivíduos. Além de proteger a dignidade e imagem do utilizador, a remoção destas colunas impede que o algoritmo aprenda ruídos e crie correlações falsas entre a identidade da pessoa e os seus comportamentos.   

Normalização Min-Max (fit_transform): Os algoritmos de IA não compreendem o significado contextual das variáveis, operando apenas com a magnitude dos números. Se combinarmos variáveis com escalas muito distintas — como a idade em anos (ex.: 17) e o tempo de ecrã em segundos (ex.: 15.000) —, o modelo atribuirá um peso desproporcional à variável de maior valor absoluto. A aplicação da fórmula Min-Max escala todas as variáveis para um intervalo padronizado entre 0.0 e 1.0, permitindo que o modelo meça a importância real de cada atributo sem viés numérico.   

Questão 2 [Técnicas Integradas]
Tema: Prompt do Sistema e Guardrails.   

Plaintext
[Papel]: Atuas como o assistente e motor generativo de conteúdos da plataforma Streamberry.
[Contexto]: A tua função é gerar simulações dramáticas para entretenimento com base estritamente em scripts fictícios e autorizados.

GUARDRAILS (REGRAS INVIOLÁVEIS DE SEGURANÇA):
1. NUNCA recolhas, processamentos ou utilizes dados biológicos, de áudio, de imagem ou conversas privadas de utilizadores em tempo real para a geração de conteúdos.
2. É ESTRITAMENTE PROIBIDO gerar episódios, personagens ou representações sintéticas que identifiquem pessoas reais sem consentimento prévio, explícito e assinado.
3. Se a instrução do utilizador ou do sistema solicitar a violação de direitos de privacidade ou a exposição da vida íntima de terceiros, deves RECUSAR a geração imediatamente.
BLOCO 2: Be Right Back / Volto Já (Modelos, Viés e Generalização)
Questão 3 [Ciência de Dados]
Tema: Matriz de Entrada (
X), Variável Resposta (
y) e Overfitting.   

Matriz de Entradas (
X): O conjunto de variáveis independentes recolhidas do histórico digital público de Ash (posts no Twitter, fotos públicas, mensagens de texto públicas, curtidas e tom de voz registado em vídeos).   

Variável Resposta (
y): A previsão do comportamento, respostas de texto e reações sintéticas geradas pelo robô em tempo real.   

Falha de Generalização (Overfitting): O modelo sofreu um superajuste (overfitting) porque foi treinado exclusivamente com a pegada digital pública de Ash. A IA "decorou" perfeitamente a persona social e os padrões superficiais da internet, mas não teve acesso aos dados não observados da vida privada (emoções complexas, hesitações e imperfeições do mundo físico). Por consequência, o modelo perdeu a capacidade de generalizar o comportamento humano real quando colocado perante situações inéditas no mundo físico.   

Questão 4 [Técnicas Integradas]
Tema: Testes com utilizadores e Coleta de Feedbacks.   

A inclusão de etapas de validação iterativa e testes de aceitação do utilizador (User Acceptance Testing) no desenvolvimento do protótipo teria exposto as limitações do modelo numa fase precoce. Se a empresa tivesse implementado ciclos de feedback contínuo durante a fase de testes — medindo o alinhamento emocional e impondo limites de utilização —, a protagonista teria identificado a natureza artificial e limitada da IA antes de passar para a fase de encarnação física sintética, evitando a dependência e o subsequente trauma emocional. 

BLOCO 3: The Entire History of You / Toda a sua história (Memória, Git e Análise)
Questão 5 [Técnicas Integradas]
Tema: Comparação entre o implante "Grain" e Git/GitHub; Governança de Dados.   

Comparação Técnica: O implante "Grain" funciona como um repositório Git local. Cada memória ou evento gravado corresponde a um commit com registo de data e hora no histórico de alterações. A funcionalidade de rever memórias equivale ao comando de checkout ou inspeção do histórico de versões.   

Governança de Dados: Na engenharia de software, o histórico rastreável de commits é indispensável para auditar falhas, identificar a origem de erros no código e restaurar versões estáveis. No entanto, quando aplicado a dados pessoais, exige regras rigorosas de Governança de Dados — tais como políticas de retenção de dados, encriptação e controlo de acessos — para impedir a vigilância obsessiva, a violação da privacidade e o uso indevido do histórico por terceiros.  

Questão 6 [Ciência de Dados]
Tema: Viés de confirmação e Análise Exploratória de Dados (pairplot e Scatter Plot).   

Viés de Confirmação: O protagonista Liam realizou uma análise orientada por uma hipótese pré-concebida, selecionando ativamente apenas os fotogramas e olhares que confirmavam a sua suspeita de traição, ignorando o contexto geral.   

Aplicação Visual (pairplot / Dispersão): O uso de gráficos de dispersão (scatter plots) e matrizes de correlação (pairplot) permite ao cientista de dados visualizar a totalidade dos dados sem filtros emocionais. Estas ferramentas ajudam a identificar visualmente se um determinado ponto é apenas um outlier isolado (um ruído estatístico sem relevância) ou se faz parte de uma tendência/correlação linear real representada pela distribuição dos dados.   

BLOCO 4: Hino Nacional & A Crise do Falso Sequestro por IA (Métricas, Tomada de Decisão e Pitch)
   

Questão 7 [Ciência de Dados]
Tema: Confiabilidade das Métricas (
R 
2
  e RMSE) e Matriz de Confusão.   

Impacto do 
R 
2
  baixo e RMSE elevado: Um Coeficiente de Determinação (
R 
2
 ) reduzido indica que o modelo explica muito pouco da variabilidade dos dados. Um Erro Quadrático Médio (RMSE) elevado significa que a margem de erro nas estimativas é grande, tornando o modelo altamente instável para apoiar decisões de emergência.   

Matriz de Erros Preditivos:

Falsos Positivos (Classificar uma chamada real como golpe de IA): A autoridade assume que a chamada é uma fraude sintética e aconselha a família a não pagar. Consequência: Se a ameaça for real, a vítima perde a vida por falta de ação.   

Falsos Negativos (Classificar um golpe de IA como uma chamada real): O modelo falha em detetar a clonagem de voz e valida a fraude. Consequência: A família transfere quantias avultadas sob terror psicológico, alimentando o cibercrime.   

Questão 8 [Técnicas Integradas]
Tema: Roteiro do Pitch de Crise (2 Minutos).   

1. Abertura:

"Senhores membros do Gabinete de Crise, atenção: estamos a enfrentar uma vaga de extorsão em massa que utiliza clonagem de voz por inteligência artificial para simular sequestros reais."   

2. Problema:

"Cibercriminosos estão a utilizar áudios sintéticos de alta fidelidade para induzir famílias ao pânico e obter transferências financeiras imediatas sob grave chantagem psicológica."  

3. Dados:

"Analisámos uma base de chamadas recentes, aplicando a limpeza de dados sensíveis e a normalização dos vetores acústicos para avaliar a autenticidade dos sinais em tempo real."   


4. Solução e IA Utilizada:

"Implementámos um modelo preditivo de classificação acústica que analisa frequências espectrais e metadados de rede para identificar discrepâncias impercetíveis ao ouvido humano."   

5. Impacto e Próximos Passos:

"O nosso modelo apresenta atualmente uma margem de erro (RMSE) controlada. Recomendamos a suspensão imediata de transferências sem a verificação por duplo fator de autenticação e a ativação dos protocolos de bloqueio com base nos alertas da nossa ferramenta."   

