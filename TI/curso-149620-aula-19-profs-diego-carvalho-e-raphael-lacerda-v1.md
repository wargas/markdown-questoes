(CETRO / Pref. São Paulo (AFT) - 2014) Em um sistema de informação de uma instituição bancária, está sendo realizada uma transação de transferência de valores entre uma conta de um cliente para a conta de outro cliente. No decorrer da transação, ocorre uma falha geral no sistema e a transação é cancelada. Imagine que o valor da transferência saiu da conta do primeiro cliente, mas, antes de ser acrescentado ao saldo do segundo cliente, houve a falha do sistema. Caso o banco de dados não possuir a capacidade de recuperar o estado original dos dados antes da falha, é correto afirmar que ocorreu um problema de:
***
integridade.
***
redundância.
***
anomalia de acesso.
***
atomicidade.
***
isolamento.
***
D
****
(CESPE / STM - 2018) O modelo conceitual, que reflete uma estrutura simplificada do banco de dados, é responsável por registrar como os dados estão armazenados no sistema de gerenciamento de banco de dados (SGBD).
***
E
****
(CESPE / TCE-PB - 2018) A respeito de SGBD, assinale a opção correta.
***
Um SGBD é um software que não prevê as funções de definição, recuperação e alteração de dados, sendo essa tarefa a função básica de um sistema de banco de dados.
***
A consistência de dados é o princípio que determina a manutenção de determinado dado em vários arquivos diferentes.
***
Conforme o princípio da atomicidade, caso ocorra erro em determinada transação, todo o conjunto a ela relacionado será desfeito até o retorno ao estado inicial, como se a transação nunca tivesse sido executada.
***
O controle de concorrência é o princípio que garante e permite a manipulação, no mesmo momento, de um mesmo dado por mais de uma pessoa ou um sistema.
***
Um SGBD, por definição, não é flexível, dada a dificuldade de mudar a estrutura dos dados quando os requisitos mudam.
***
C
****
(UEPA / SEFA – 2013) Uma empresa em sua expansão verificou que existia a necessidade de ser realizada a duplicação de dados em arquivos separados como forma de contingência. Em relação aos conceitos de banco de dados, a duplicação de dados em arquivos separados é conhecida como:
***
redundância de dados 
***
integridade de dados 
***
relacionamento de dados 
***
entidades de dados 
***
sistemas de gerenciamento de banco de dados.
***
A
****
(FGV / SEFAZ-MS - 2006) A implementação de Sistemas Gerenciadores de Banco de Dados - SGBD proporciona duas grandes vantagens, que consistem em:
I. impedir que um determinado código ou chave em uma tabela não tenha correspondência em outra tabela.
II. permitir o armazenamento da informação em um único local com acesso descentralizado e, sendo compartilhada com vários sistemas, os usuários estarão utilizando uma informação confiável.
Essas vantagens são conhecidas por:
***
Manutenção de Integridade / Eliminação de Inconsistências.
***
Independência dos Dados / Eliminação de Redundâncias.
***
Independência dos Dados / Eliminação de Inconsistências.
***
Restrições de Segurança / Eliminação de Inconsistências.
***
Restrições de Segurança / Eliminação de Redundâncias.
***
A
****
(CESPE / MPOG - 2015) O SGBD proporciona um conjunto de programas que permite o acesso aos dados sem exposição dos detalhes de representação e armazenamento de dados, por meio de uma visão abstrata dos dados, conhecida como independência de dados.
***
C
****
(CESPE / TRE-BA - 2017) Sistemas de banco de dados estão sujeitos a falhas como falta de energia, erros de software ou mesmo sabotagem dos dados. O sistema de recuperação é responsável pela restauração do banco para um estado consistente que havia antes da ocorrência da falha. Para precaver-se de tais falhas, devem-se preservar as propriedades de:
***
consistência e durabilidade.
***
isolamento e consistência.
***
atomicidade e durabilidade.
***
durabilidade e isolamento.
***
atomicidade e isolamento.
***
C
****
(CONSULPLAN / TRF 2ª REGIÃO - 2017) Em banco de dados relacional à arquitetura mais difundida na literatura é a Arquitetura “Three-Schema” (também conhecida como arquitetura ANSI/SPARC), proposta por Tsichritzis & Klug em 1978. A arquitetura “three-schema” pode ser utilizada para explicar conceitos de independência de dados, que podem ser definidos como a capacidade de alterar o esquema de um nível sem ter que alterar o esquema no próximo nível superior. Um SGBD é uma coleção de arquivos e programas inter-relacionados permitindo a consulta e modificação de dados, no qual é possível ter uma abstração dos dados em 3 níveis; na arquitetura ANSI/SPARC são conhecidos como:
***
Lógico, físico e hierárquico.
***
Interno, conceitual e externo.
***
Relacional, rede e hierárquico.
***
Conceitual, relacional e hierárquico.
***
B
****
(FCC / DPE-SP - 2015) As transações em bancos de dados distribuídos precisam preservar as propriedades conhecidas como ACID. Dentre estas propriedades está a:
***
Atomicidade.
***
Confidencialidade.
***
Autenticidade.
***
Integridade.
***
Disponibilidade.
***
A
****
(INSTITUTO AOCP / EBSERH - 2015) A técnica utilizada para a especificação e explorar estrutura orientada a dados para um banco de dados é chamada de Modelagem de dados. Para entender como os modelos de dados podem ser usados na prática, depara-se com três estilos básicos de modelos de dados. Quais são esses estilos?
***
Modelos Conceituais, Modelos Lógicos e Modelos de Contexto.
***
Modelos Conceituais, Modelos de Contexto e Modelos Físicos.
***
Modelos de Contexto, Modelos Lógicos e Modelos Físicos.
***
Modelos Conceituais, Modelos Lógicos e Modelos Físicos.
***
Modelos de Aplicações, Modelos de Contexto e Modelos Conceituais.
***
D
****
(FUNDATEC / BRDE - 2015) Uma transação corresponde a uma coleção de operações que desempenha uma função lógica única dentro de uma aplicação do sistema de banco de dados e deve possuir todas as seguintes propriedades fundamentais, impostas pelos métodos de controle de concorrência e recuperação do sistema de gerenciamento de banco de dados, EXCETO:
***
Atomicidade.
***
Consistência.
***
Durabilidade.
***
Escalabilidade.
***
Isolamento.
***
D
****
(FUNCAB / PRODAM-AM - 2014) Uma transação é uma unidade de execução de programa que acessa e, possivelmente, atualiza vários itens. Há uma propriedade das transações que garante que a execução simultânea de transações resulte em uma situação no sistema equivalente ao estado obtido caso as transações tivessem sido executadas uma de cada vez, independente da ordem em que são executadas. Essa propriedade denomina-se:
***
isolamento.
***
consistência.
***
atomicidade.
***
durabilidade.
***
dinamicidade.
***
A
****
(FCC / SABESP - 2014) Um SGBD possui a capacidade de mudar o esquema interno sem ter de alterar o esquema conceitual, consequentemente não havendo necessidade de alteração do esquema externo. As mudanças no esquema interno podem ser necessárias para que alguns arquivos físicos possam ser reorganizados, por exemplo, pela criação de estruturas de acesso adicionais para aperfeiçoar o desempenho da recuperação ou atualização de dados.
Essa característica de um SGBD é denominada:
***
modelo lógico de dados.
***
modelo físico de dados.
***
independência modular.
***
representação conceitual.
***
independência física de dados.
***
E
****
(VUNESP / DESENVOLVESP - 2014) Há 4 propriedades básicas que uma transação de um banco de dados relacional deve respeitar. Assinale a alternativa que contém duas dessas propriedades:
***
Atomicidade e isolamento.
***
Consistência e normalização.
***
Durabilidade e paralelismo.
***
Normalização e atomicidade.
***
Paralelismo e isolamento.
***
A
****
(FDC / AGERIO - 2014) A arquitetura ANSI/SPARC de bancos de dados é composta por três níveis independentes, cada um deles descrevendo o banco em um nível diferente de abstração.
Um desses níveis se refere ao armazenamento físico dos dados e à definição das estruturas físicas que permitem obter um desempenho satisfatório. Esse nível é conhecido por:
***
interno
***
operacional
***
estratégico
***
conceitual
***
externo
***
A
****
(FUNCAB / MDA - 2014) Em 1971, o Comitê sobre Computador e Processamento de Informações, abreviado Comitê X3, do American National Standards Institute (ANSI), formou um grupo de estudo especial, denominado Comitê de Planejamento e Requisitos de Padrões (Standards Planning and Requirements Committee – SPARC), que propôs uma arquitetura de esquemas de um sistema de gerência de banco de dados, ou arquitetura de Sistema de Banco de Dados (SBD) , arquitetura esta conhecida como ANSI/X3/SPARC ou, simplesmente, ANSI/SPARC.
A arquitetura ANSI/SPARC pode ser usada para melhor explicar o conceito de independência de dados. Esse conceito pode ser dividido em:
***
lógica e física
***
conceitual e lógica.
***
física e conceitual.
***
esquema e lógica.
***
física e esquema.
***
A
****
(FUNCAB / MDA - 2014) Em 1971, o Comitê sobre Computador e Processamento de Informações, abreviado Comitê X3, do American National Standards Institute (ANSI), formou um grupo de estudo especial, denominado Comitê de Planejamento e Requisitos de Padrões (Standards Planning and Requirements Committee – SPARC), que propôs uma arquitetura de esquemas de um sistema de gerência de banco de dados, ou arquitetura de Sistema de Banco de Dados (SBD), arquitetura esta conhecida como ANSI/X3/SPARC ou, simplesmente, ANSI/SPARC.
A arquitetura ANSI/SPARC possui a seguinte quantidade de níveis:
***
2
***
3
***
5
***
6
***
8
***
B
****
(FUNCAB / MDA - 2014) Em um banco de dados, uma transação constitui uma operação, como inclusão, leitura, atualização ou exclusão, realizada em um banco de dados. Nesse contexto, alguns princípios devem ser atendidos, tais como:
I. se ocorrerem falhas que interrompam o processo de atualização de valores de estoque, o sistema deve manter os valores antigos.
II. se a transação for completada sem problemas, a soma das quantidades existentes em estoque do produto transferido (nos dois estoques), antes e depois da transação, deve ser a mesma.
Os princípios definidos em I e II são denominados, respectivamente:
***
consistência e durabilidade.
***
durabilidade e independência 
***
independência e confiabilidade 
***
confiabilidade e atomicidade.
***
atomicidade e consistência.
***
E
****
(CESGRANRIO / IBGE - 2013) Um sistema de banco de dados sofreu uma falha severa devido à perda de energia no meio da execução de um comando SQL de UPDATE que alterava milhares de registros. Devido às garantias fornecidas pelo SGBD, após o reinício do sistema, a transação de UPDATE foi revertida, e o banco de dados voltou ao seu estado original.
A propriedade ACID usada nesse caso foi o(a):
***
isolamento
***
determinismo
***
consistência
***
atomicidade
***
durabilidade
***
D
****
(VUNESP / COREN-SP - 2013) Uma das propriedades que uma transação de um banco de dados relacional deve respeitar é a que estabelece que uma transação deva ser completada até seu término, não sendo admissível implementá-la apenas parcialmente. Essa é a propriedade da:
***
conexão.
***
unicidade.
***
dependência.
***
atomicidade.
***
compatibilidade.
***
D
****
(ESPP / COBRA TECNOLOGIA - 2013) A integridade de uma transação depende de 4 propriedades conhecidas como ACID, assinale a alternativa que NÃO faz parte destas propriedades:
***
Atomicidade.
***
Consciência
***
Isolamento.
***
Durabilidade.
***
B
****
(CCV - UFC / UFC - 2013) Em banco de dados, uma transação é um conjunto de procedimentos que é executado no banco de dados, que para o usuário é visto como uma única ação. Para garantir a integridade de uma transação, algumas propriedades devem dar-se no ambiente do banco de dados. De acordo as afirmações abaixo, marque a alternativa correta que associa as afirmações a uma das propriedades.
- Se uma transação é concluída com sucesso, então seus efeitos são persistidos.
- Ou todas as ações da transação acontecem, ou nenhuma delas acontece.
***
durabilidade e atomicidade.
***
isolação e esquematização 
***
durabilidade e consistência.
***
persistência e automação.
***
isolação e atomicidade.
***
A
****
(ESAF / MF - 2013) Banco de Dados é:
***
uma relação de dependência entre dados que tem por objetivo atender a uma comunidade de usuários.
***
um conjunto de dados integrados que tem por objetivo impedir acessos indevidos a dados armazenados.
***
um conjunto de dados integrados que tem por objetivo atender a requisitos do sistema operacional.
***
um conjunto de dados integrados que tem por objetivo atender a uma comunidade de usuários.
***
uma estrutura de máquina virtual que tem por objetivo atender a necessidades do software de acesso.
***
D
****
(COPEVE-UFAL/ MPE-AL - 2012) A arquitetura ANSI/SPARC define três níveis (ou camadas) que ficam entre o banco de dados em si (disco rígido) e as aplicações do usuário; são eles:
***
físico, tabelas e modelo.
***
físico, lógico e conceitual.
***
físico, estrutural e externo.
***
interno, lógico e conceitual.
***
interno, conceitual e externo.
***
E
****
(CESGRANRIO / CHESF - 2012) A arquitetura de um Banco de Dados ANSI/SPARC possui três níveis. O primeiro desses níveis é responsável pelo armazenamento de dados, o segundo serve de interface entre o primeiro e o terceiro nível, o qual, por seu turno, é responsável pela visualização dos dados pelo usuário.
Esses três níveis são denominados, respectivamente, de:
***
físico, externo e conceitual.
***
físico, conceitual e externo.
***
externo, físico e conceitual.
***
conceitual, externo e físico.
***
conceitual, físico e externo.
***
B
****
(CESPE / BANCO DA AMAZÔNIA - 2012) A arquitetura ANSI SPARC é um modelo de interoperabilidade de dados, voltado para o domínio de sistemas de gerenciamento de bases de dados (SGBDs). O modelo em questão é organizado em três níveis, dos quais um é o nível conceitual, mais semântico; e outro é o nível físico ou interno, mais sintático.
***
C
****
(FUNCAB / PRODAM-AM - 2010) Marque a alternativa que apresenta os três níveis descritos na proposta ANSI/SPARC para a definição de uma arquitetura de três esquemas para sistemas de banco de dados.
***
Conceitual, Lógico e Físico.
***
Hierárquico, Em Redes e Relacional.
***
Conceitual, Relacional e Orientado a Objetos.
***
Interno, Conceitual e Externo.
***
Relacional, Objeto-Relacional e Orientado a Objetos.
***
D
****
(CESPE / INMETRO - 2010) No processamento de transações em sistemas de bancos de dados, a implementação de mecanismos de controle de concorrência garante às transações a característica de:
***
isolamento.
***
atomicidade.
***
durabilidade.
***
prioridade.
***
individualidade.
***
A
****
(PACTCPB / PREF PATOS - 2010) Sobre a arquitetura ANSI/SPARC de sistemas de banco de dados, julgue corretos os itens abaixo:
I) Divide a arquitetura em dois níveis.
II) O nível interno define como os dados são vistos pelos usuários individuais.
III) O nível lógico dá uma visão comunitária dos dados.
IV) O nível lógico compõe-se de tabelas.
Estão corretos:
***
I e III.
***
I e IV.
***
I e II.
***
III e IV.
***
II e IV.
***
D
****
(FGV / BADESC - 2010) A arquitetura de um SGBD ou a arquitetura de um sistema de banco de dados, também denominada de arquitetura ANSI/SPARC em três níveis, determina que um SGBD descreva como os dados devem ser armazenados e acessados e conter estes mesmos dados de fato armazenados.
As terminologias desta arquitetura que contêm essas descrições e os dados de fato armazenados, são respectivamente:
***
esquema físico e nível físico.
***
nível físico e esquema físico.
***
nível físico e esquema conceitual.
***
nível conceitual e esquema físico.
***
nível conceitual e esquema conceitual.
***
A
****
(ESAF / SUSEP - 2010) Um Banco de Dados é um:
***
conjunto de objetos da realidade sobre os quais se deseja manter informações.
***
conjunto de operações sobre dados integrados destinados a modelar processos.
***
software que incorpora as funções de definição, recuperação e alteração de dados.
***
software que modela funções de definição, recuperação e alteração de dados e programas.
***
conjunto de dados integrados destinados a atender às necessidades de uma comunidade de usuários.
***
E
****
(MOVENS / PREF MANAUS - 2010) Uma transação é uma unidade de execução de programa que acessa e, possivelmente, atualiza itens de dados. Com base nesse assunto, assinale a opção que apresenta uma propriedade das transações:
***
divergência
***
atomicidade
***
compartilhamento
***
Variabilidade
***
B
****
(FCC / TCE-SP - 2010) A propriedade das transações de um SGBD que garante: “ou todas as operações da transação são refletidas corretamente no banco de dados ou nenhuma o será” é a:
***
Atomicidade.
***
Isolamento.
***
Consistência.
***
Integridade.
***
Durabilidade.
***
A
****
(FCC / TRT 20 - 2010) Em relação à execução de uma transação em um banco de dados, considere:
Para que uma transação seja efetivada, todas as ações que compõem a respectiva unidade de trabalho devem ser concluídas com sucesso. Caso contrário, a ação que constituiu falha e a transação devem ser desfeitas.
A afirmação refere-se a uma das quatro propriedades da integridade de uma transação, denominada:
***
Atomicidade.
***
Isolamento.
***
Durabilidade.
***
Consistência.
***
Efetividade.
***
A
****
(FCC / SEFAZ - SP - 2009) A arquitetura ANSI/SPARC aplicada aos bancos de dados divide-os em níveis com as seguintes características:
I. O que se ocupa do modo como os dados são fisicamente armazenados.
II. O que se ocupa do modo como os dados são vistos por usuários individuais.
III. Nível lógico de comunidade ou apenas lógico (mais abstrato que o físico e diferente da visão do usuário individual).
Em um projeto arquitetural, os itens I, II e III são classificados, respectivamente, como níveis 
***
externo, conceitual e interno.
***
externo, interno e conceitual.
***
interno, externo e conceitual.
***
interno, conceitual e externo.
***
conceitual, externo e interno.
***
C
****
(COSEAC / DATAPREV - 2009) Uma transação acontece como um todo ou nada deve ser feito.
A esta propriedade dar-se o nome de:
***
durabilidade;
***
consistência;
***
isolamento;
***
atomicidade;
***
integridade.
***
D
****
(CESGRANRIO / CASA DA MOEDA - 2009) Em reunião técnica sobre a construção de um sistema financeiro, foi levantada a exigência de que uma transação deve ter todas as suas operações executadas, em caso de sucesso, ou nenhum efeito sobre a base de dados, em caso de falha. O administrador de banco de dados afirma que não há problema, uma vez que o SGBD corporativo garante a propriedade ACID de:
***
atomicidade.
***
isolamento.
***
durabilidade.
***
consistência.
***
unicidade.
***
A
****
(FUNIVERSA / IPHAN - 2009) O American National Standards Institute (ANSI), por meio do Standards Planning and Requirements Committee (SPARC), estabeleceu um padrão para o desenvolvimento de tecnologias de Banco de Dados (BD), definindo uma arquitetura de três níveis independentes. Assinale a alternativa que apresenta os três níveis da arquitetura ANSI/SPARC para banco de dados:
***
Plano, Relacional e Hierárquico.
***
Local, Remoto e Distribuído.
***
Interno, Conceitual e Externo.
***
File, Table e View.
***
DSL, DDL e DML.
***
C
****
(UNIRIO / UNIRIO - 2009) A propriedade de atomicidade garante que:
***
a transação será executada no menor tempo possível.
***
a execução da transação não interferirá na execução das transações concorrentes a ela.
***
a transação cancelará as transações concorrentes.
***
ou a transação será executada até seu fim com sucesso ou nenhuma operação da transação terá efeito.
***
a execução das operações da transação serão registradas no log (histórico).
***
D
****
(NCE-UFRJ / UFRJ - 2008) A sigla ACID é usualmente empregada para evocar as propriedades que as transações executadas num banco de dados devem possuir. Essas propriedades são:
***
atomicidade, consistência, independência, durabilidade;
***
atomicidade, concorrência, indexação, durabilidade;
***
atualização, concorrência, inserção, deleção;
***
atomicidade, concorrência, independência, durabilidade;
***
atomicidade, consistência, isolamento, durabilidade.
***
E
****
(CESGRANRIO / PETROBRAS - 2008) Atomicidade é uma propriedade de transação de um SGBD relacional que garante que:
***
uma transação seja realizada de forma independente de outras transações.
***
uma operação de uma transação seja efetuada de forma independente de outras operações.
***
nenhuma operação de uma transação seja subdividida em tarefas menores pelo SGBD.
***
todos os atributos manipulados por uma transação sejam atômicos.
***
todas as operações em um banco de dados, em uma transação, sejam executadas ou nenhuma delas o seja.
***
E
****
(CESGRANRIO / DECEA - 2006) Que propriedade do modelo ACID garante que uma transação é totalmente executada ou nenhum passo dela é executado?
***
atomicidade.
***
durabilidade.
***
consistência.
***
completude.
***
isolamento.
***
A
****
(CESGRANRIO / DECEA - 2006) Segundo a arquitetura ANSI/SPARC, os três níveis de esquema usados para separar o banco de dados físico das aplicações do usuário são:
***
físico, estrutural e externo.
***
lógico, físico e interno.
***
interno, conceitual e externo.
***
interno, lógico e restrito.
***
conceitual, estrutural e físico.
***
C
****
(CESGRANRIO / AL-TO - 2005) Um SGBD para manter a integridade dos dados deve apresentar algumas propriedades para as transações. A propriedade que define "ou todas as operações da transação são refletidas corretamente no banco de dados ou nenhuma deve ser refletida" é:
***
atomicidade.
***
consistência.
***
durabilidade.
***
isolamento.
***
polimorfismo.
***
A
****
(NCE-UFRJ / TRE-RJ - 2001) Uma vantagem da arquitetura de 3 níveis ANSI/ SPARC é prover independência de dados. De acordo com esta arquitetura, é possível prover dois tipos de independência de dados:
***
funcional e lógica;
***
cronológica e funcional;
***
física e lógica;
***
física e referencial;
***
cronológica e referencial.
***
C
****
(NCE-UFRJ / TRE-RJ - 2001) De acordo com a arquitetura ANSI/SPARC um Sistema de Banco de Dados divide-se em três níveis gerais: interno, conceitual e externo. É correto afirmar que:
***
o nível interno é responsável pelo mapeamento entre os níveis externo e conceitual;
***
o nível externo é o mais próximo ao armazenamento físico;
***
o nível conceitual é o mais próximo ao usuário;
***
o nível conceitual esconde os detalhes sobre o armazenamento físico dos dados;
***
existe uma única visão externa no nível externo.
***
D