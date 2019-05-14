# Business Intelligence and Artificial Intelligence

## Glossário ##
**Bussiness Intelligence** - refere-se ao processo de coleta, organização, análise, compartilhamento e monitoramento de informações que oferecem suporte a gestão de negócios. É um conjunto de técnicas e ferramentas para auxiliar na transformação de dados brutos em informações significativas e uteis a fim de analisar o negócio.

**Artificial Intelligence** - é um ramo da ciência da computação que se propõe a elaborar dispositivos que simulem a capacidade humana de raciocinar, perceber, tomar decisões e resolver problemas, enfim, a capacidade de ser inteligente.

##  Criar um serviço que faça a caracterização dos estudantes em perfis de acordo com o seu passado académico pré-ISEP, assiduidade, historial académico no ISEP, etc.

Para que este serviço seja possível, será necessário recolher dados dos estudantes. Seria pertinente completar a zona de submissão de documentos, para que, aquando a fase de inscrição no ISEP, o estudante pudesse submeter documentos autenticados com as suas notas e a sua assiduidade do ensino secundário, cursos e formações que tenham realizado antes de entrar na instituição. Também seria permitido que, durante o seu percurso académico no ISEP, fossem submetidos novos documentos autenticados caso o aluno frequentasse mais alguma formação extra curricular.

Neste momento, durante o processo de inscrição de novos alunos no ISEP, os alunos têm de preencher um formulário onde têm perguntas para que a instituição conheça um pouco melhor o estudante. Assim sendo, para complementar este serviço, seria imprescindível aplicar mais algumas perguntas, de acordo com os parâmetros a ter em conta para a caracterização do perfil do aluno (ex: um aluno que coloque no questionário que praticou/pratica algum desporto e que fez/faz parte de uma equipa federada, ficará classificado como uma pessoa com espírito de equipa).

No que toca aos KPI's deste serviço, temos o nível de autonomia, a quantidade de reprovação, a média e faltas do aluno.

##  Criar um serviço de colocação nas turmas e formação de grupos que tenha em atenção as características específicas dos estudantes, de acordo com os perfis criados pelo serviço de caracterização dos estudantes. A Direção do Curso e os Responsáveis de UC podem definir os critérios mais adequados a cada curso e UC. Este serviço terá capacidade de aprendizagem, no sentido de melhorar o processo com base nos resultados anteriores.

Este serviço está diretamente relacionado como primeiro ponto. 

##  Criar um serviço experimental de deteção de fraude académica que use o perfil do estudante e o seu histórico para identificar eventuais anomalias. Caberá aos docentes a análise concreta e a decisão sobre o alerta.

Este serviço relaciona-se com o primeiro, visto que este utilizaria os dados presentes no perfil do aluno de cadeiras semelhantes e, em geral, para determinar se deveria emitir um alerta sobre um trabalho, este serviço deverá analisar notas e detetar aumentos e decréscimos muito acentuados, para se poder ver se algo fora do normal para aquele aluno está a acontecer, claro que existem alunos cujas notas têm mais tendência a variar muito, essas tendências deverão ser determinadas através dos algoritmos e apenas devera gerar suspeitas caso algo vá contra elas.

Em conjunto com a análise dos dados do aluno do perfil deveriam ser também utilizados e melhorados alguns dos algoritmos já existentes em certas cadeiras para comparar código  entre alunos. Sendo que pode também ser utilizado algo como historial de turmas para dar mais importância a parecenças no código entre pessoas que já estiveram na mesma turma ou grupo.

Se for detetada alguma irregularidade a partir dai deve  ser criada e enviada para o docente (regente ou professor PL) uma notificação a indicar a suspeita de fraude, e os alunos entre qual existe essa suspeita. Caso seja determinado que foi uma deteção falsa deverá alterar-se no registo de deteções.

##  Criar um serviço de análise da qualidade de ensino baseado na análise de indicadores de desempenho (KPI) da atividade de ensino e do desempenho individual dos estudantes. Com este serviço pretende-se eliminar definitivamente os inquéritos pedagógicos, substituindo-os por uma ferramenta inteligente.

KPIs- qualidade do serviço, SLA, disponibilidade do serviço, diminuição de tempo gasto, conformidade com RGPD

Este serviço da qualidade no ensino vai utilizar, entre outras coisas, o serviço de caracterização de um aluno para poder decidir se durante o semestre houve melhorias nas notas. Terá também acesso à média das notas das turmas do professor, desta forma pode analisar se o problema foi do aluno ou se é comum a todas as turmas do professor.
Pode ainda ser utilizado em conjunto com o serviço de colocação em turmas de forma a juntar alunos e professores mais compatíveis.
Desta forma automatiza-se os inquéritos pedagógicos, para além disso o que representa um professor passa a ser os resultados que obtém em vez da opinião que os alunos têm dele.