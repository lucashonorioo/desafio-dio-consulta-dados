# desafio-dio-consulta-dados

Entendendo Desafio 
Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos abordados até aqui, aplique os conhecimentos adquiridos nas aulas e documente sua experiência para demonstrar sua compreensão dos temas discutidos.

Descrição do Desafio
Este laboratório tem como objetivo aplicar técnicas de organização e pesquisa de documentos por meio da ingestão de dados e indexação utilizando ferramentas de inteligência artificial. Durante as aulas, foram abordados três passos principais: ingestão de conteúdo para IA, criação de índices inteligentes e exploração prática dos dados organizados. O foco está em desenvolver uma compreensão sólida sobre como essas ferramentas podem ser utilizadas para minerar e extrair conhecimento de grandes volumes de informação. Como entregável, espera-se um repositório estruturado contendo registros das etapas realizadas e insights obtidos ao longo da prática.

Objetivos de Aprendizagem 
Ao concluir este desafio, você será capaz de: 

Aplicar os conceitos aprendidos em um ambiente prático;
Documentar processos técnicos de forma clara e estruturada; 
Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica. 

Resumo do que foi feito por mim: 

O conteúdo utilizado nesta aula de laboratório foi o Azure Cognitive Search, serviço de busca inteligente baseado em inteligência artificial.

O primeiro passo foi criar um novo recurso AI Search, que é utilizado para criar mecanismos de busca customizados em grandes volumes de dados, permitindo consultas inteligentes e rápidas.

Em seguida, foi criado um novo serviço cognitivo, necessário para agregar capacidades de IA (como análise de linguagem natural e reconhecimento de padrões) ao mecanismo de busca, enriquecendo os dados indexados.

Conforme solicitado no laboratório, também foi criada uma conta de armazenamento para armazenar os dados que seriam utilizados no exercício. Na opção de redundância, foi selecionado o LRS (Locally Redundant Storage), pois para os fins de laboratório (baixo custo e simplicidade) era a opção mais adequada.

Dentro da configuração da conta de armazenamento, na opção de permitir acesso anônimo ao blob, deixei habilitado para possibilitar a alteração do nível de acesso ao criar o container, facilitando o gerenciamento do acesso aos arquivos públicos no experimento.

Na parte de armazenamento de dados e contêineres, criei um novo container chamado reviewsmercearia, destinado a armazenar os dados simulados de avaliações de uma mercearia fictícia, usados para alimentar o serviço de busca no laboratório.

Posteriormente, no AI Services, realizei a importação dos dados adicionados na conta de armazenamento.
Por fim, foram realizadas as consultas sobre os documentos importados e todos os processos funcionaram conforme o esperado, demonstrando o funcionamento da solução.
Organizei todos os recursos criados em um único grupo de recursos chamado RecursoDeConsultasDados, para manter a estrutura organizada e deixar claro que todos os componentes estavam relacionados à mesma finalidade de consultas de dados.
