(FUNDEP / Análise de Sistemas / CODEMIG – 2013) Assinale a alternativa que apresenta qual a tecnologia RAID que deve ser utilizada para se criar um espelhamento de disco com a finalidade de evitar desastres e perdas de dados.
***
RAID 0.
***
RAID 1.
***
RAID 2.
***
RAID 3.
***
B
****
(IBFC / Técnico em Informática / EBSERH – 2013) O nível de RAID que implementa o espelhamento de disco, também conhecido como mirror, que é implementado com o mínimo de dois discos é o:
***
RAID 0
***
RAID 5
***
RAID 1
***
RAID 4
***
C
****
(FUNCEFET / Técnico em Informática / Prefeitura de Nilópolis/RJ – 2011) O RAID ou Conjunto Redundante de Discos Independentes é um meio de se criar um subsistema de armazenamento composto por vários discos individuais, com a finalidade de ganhar segurança e desempenho, e pode ser implementado via software ou hardware. Considere um RAID com as seguintes características:
 exige, no mínimo, 4 discos rígidos,  os discos são alocados em pares e cada par será espelhado, garantindo redundância,  os pares são distribuídos, melhorando o desempenho,  até metade dos discos pode falhar simultaneamente, sem colocar o conjunto a perder, desde que não falhem os dois discos de um mesmo espelho,  normalmente, por segurança, se usam discos de lotes diferentes em cada “lado” do espelho,  é o nível recomendado para bases de dados, por ser o mais seguro e dos mais velozes e  deve ser utilizado quando a necessidade de economia não se sobrepõe à segurança e ao desempenho.
A modalidade de RAID, que atende a essas características, é:
***
RAID1.
***
RAID50.
***
RAID5.
***
RAID10.
***
D
****
(SRH / Análise de Sistemas / UERJ – 2015) Para operar com grandes volumes de dados ou garantir uma alta disponibilidade no armazenamento, é necessário conhecimentos em Redundant Array of Independent Disks (RAID). Com o objetivo de promover uma alta disponibilidade de dados, um administrador decide investir na confiabilidade do armazenamento de um servidor com 4 (quatro) discos rígidos (hard disk) por meio do uso de RAID. A tecnologia RAID que oferece a maior confiabilidade em caso de falhas simultâneas de disco é:
***
RAID0
***
RAID1
***
RAID6
***
RAID10
***
B
****
(CS-UFG / Técnico de Laboratório / UFG – 2018) O nível do RAID, normalmente indicado por um número, apresenta a tecnologia que está em uso. Como característica, requer ao menos três discos para ser usado e um disco do volume pode falhar sem comprometer os dados. Estas características definem o:
***
RAID-0
***
RAID-1
***
RAID-2
***
RAID-5
***
D
****
(FCC / Analista de Sistemas / CAIXA – 2011) O RAID (Redundant Array of Independent Drives) é um meio de se criar um subsistema de armazenamento composto por vários discos individuais, com a finalidade de ganhar segurança e desempenho. Das seis técnicas mais conhecidas para distribuição dos dados pelos drives para permitir operação paralela, duas delas necessitam que as rotações de todos os drives sejam sincronizadas. São elas:
***
RAID 2 e RAID 3
***
RAID 4 e RAID 5
***
RAID 0 e RAID 1
***
RAID 1 e RAID 4
***
RAID 3 e RAID 5
***
A
****
(FCC / Analista Judiciário / TRE-PR – 2017) Considere, por hipótese, que um Tribunal Regional Eleitoral utiliza uma solução RAID que não oferece proteção contra falhas, já que no arranjo não existe redundância. Isso significa que uma falha em qualquer um dos discos pode ocasionar perda de informações para o sistema todo, especialmente porque fragmentos do mesmo arquivo podem ficar armazenados em discos diferentes. Um Analista Judiciário propôs que fosse implementado outro arranjo RAID que oferece redundância através de um esquema que utiliza um bit de paridade. Neste novo arranjo as informações de paridade, assim como os próprios dados, são distribuídos entre todos os discos do sistema. Normalmente, o espaço destinado à paridade é equivalente ao tamanho de um dos discos, assim, um arranjo formado por três HDs de 500 GB terá 1 TB para armazenamento e 500 GB para paridade. Caso um disco falhe, o esquema de paridade permite recuperar os dados a partir das informações existentes nas demais unidades. A solução de armazenamento de dados atualmente existente no Tribunal e a nova solução proposta pelo Analista são, correta e respectivamente, 
***
RAID 1 − RAID 5.
***
RAID 1+0 − RAID 4.
***
RAID 0+1 − RAID 6.
***
RAID 0 − RAID 5.
***
RAID 0 − RAID 6.
***
D
****
(VUNESP / Agente da Fiscalização Financeira / TCE-SP – 2015) Para responder à questão, observe, no arranjo, a seguinte organização de dados em cada disco.
De acordo com a localização dos dados e de suas respectivas informações de paridade (indicadas com o sufixo “p"), pode-se concluir corretamente que os níveis RAID identificados pelas letras X e Y correspondem, respectivamente, ao:
***
RAID 0 e RAID 1.
***
RAID 0 e RAID 5.
***
RAID 1 e RAID 0.
***
RAID 1 e RAID 5.
***
RAID 5 e RAID 0.
***
D
****
(SEPROD / Técnico em Informática / Câmara de Estância/SE – 2014) O sistema RAID consiste em um conjunto de dois ou mais discos rígidos com dois objetivos básicos: tornar o sistema de disco mais rápido (isto é, acelerar o carregamento de dados do disco), através de uma técnica chamada divisão de dados (data stripping) e/ou tornar o sistema de disco mais seguro, através de uma técnica chamada espelhamento (mirroring). Essas duas técnicas podem ser usadas isoladamente ou em conjunto. A divisão de dados e o espelhamento são respectivamente:
***
RAID 5 e RAID 0.
***
RAID 5 e RAID 1.
***
RAID 0 e RAID 1.
***
RAID 7 e RAID 0.
***
RAID 5 e RAID 6.
***
C
****
(AOCP / Assessor Técnico de Informática / TCE-PA – 2012) O RAID 0:
***
funciona com três ou mais discos iguais onde um dos discos guarda a paridade da informação contida em todos os outros discos.
***
é conhecido como striping, e os dados são subdivididos em segmentos consecutivos, escritos sequencialmente por cada um dos discos de um array.
***
é similar ao RAID 4, superando problemas sobre paridade para os dados do array, distribuídos ao longo de todos os discos ao invés de serem armazenadas em um disco dedicado, oferecendo uma maior tolerância a falhas ao sistema.
***
é conhecido como mirror e implementa o espelhamento de disco, utilizando no mínimo dois deles.
***
é um padrão relativamente novo e semelhante ao RAID 5, porém usa o dobro de bits de paridade como forma de garantir a integridade dos dados, caso até dois discos falhem ao mesmo tempo.
***
B
****
(IF-PE / Técnico de Laboratório / IF-PE – 2017) A tecnologia RAID consiste em fazer com que vários discos rígidos funcionem como um só e foi desenvolvida para melhorar o armazenamento de dados. Assinale a alternativa que corresponde à descrição a seguir: “Nesse tipo de RAID são necessários discos em número par. O funcionamento é simples: todos os dados são gravados em dois discos diferentes; se um disco falhar ou for removido, os dados preservados no outro disco permitem a não descontinuidade da operação do sistema.” 
***
RAID10
***
RAID6
***
RAID1
***
RAID9
***
RAID0
***
C
****
(ESAF / Gestão de Infraestrutura / ESAF – 2015) O nível de RAID (Redundant Array of Independent Drives) que utiliza paridade dupla e que garante a integridade dos dados em caso de até 2 dos HDs falharem ao mesmo tempo é o:
***
RAID 0.
***
RAID 1.
***
RAID 3.
***
RAID 5.
***
RAID 6.
***
E
****
(FUNCAB / Analista de Business Intelligence / MDA – 2014) No contexto da adoção de ferramentas de um projeto em BI, há que se considerar uma solução para o armazenamento de dados. Nesse sentido, RAID representa uma tecnologia para prover maior segurança e melhor desempenho. Entre as técnicas RAID, qual a que possui as características listadas a seguir?
I. Os dados são distribuídos em espelhos ou duplicações em discos diferentes, permitindo uma completa estratégia de tolerância a falhas.
II. Os dados replicados serão atualizados diretamente pelo próprio sistema de disco, com pequeno overhead, mas garantirão disponibilidade imediata em caso de perda nos discos originais.
***
RAID5
***
RAID4
***
RAID3
***
RAID1
***
RAID0
***
D
****
(IF-SC / Técnico Administrativo / IF-SC – 2014) É um modo que utiliza no mínimo dois HDs, sendo que o segundo armazena uma imagem idêntica ao do primeiro. Se, por algum motivo, o disco titular falhar, teremos uma cópia de segurança armazenada no segundo disco. Assinale a alternativa CORRETA que engloba o modo descrito nesse enunciado:
***
RAID 0.
***
RAID 1.
***
RAID 2.
***
RAID 3.
***
RAID 5.
***
B
****
(FCC / Analista Judiciário / TRT-RJ – 2014) O nível de RAID que implementa com, no mínimo, dois discos o espelhamento de disco para, em caso de problema com um deles, o outro possa manter a continuidade de operação do sistema, é o:
***
RAID 3.
***
RAID 4.
***
RAID 1.
***
RAID 0.
***
RAID 2.
***
C
****
(FUNCAB / Analista de Sistema Operacional / MDA – 2014) A tecnologia RAID pode ser utilizada tanto para melhorar a performance quanto para aumentar a disponibilidade de um computador. O nível RAID que apresenta grande tolerância a falhas e que, caso um driver venha falhar, basta usar, diretamente, a cópia completa desse driver no seu lugar é o:
***
RAID 3
***
RAID 1
***
RAID 2
***
RAID 4
***
RAID 0
***
B
****
(FGV / Técnico Superior Especializado / DPE-RJ – 2014) Existem diversos tipos de RAID (Redundant Array of Independent Disks). Para fazer simplesmente o espelhamento de discos, de modo que as informações sejam armazenadas simultaneamente em mais de um disco, criando copias idênticas, deve-se implementar um esquema de:
***
RAID 0.
***
RAID 1
***
RAID 3.
***
RAID 5.
***
RAID 6.
***
B
****
(FGV / Técnico Superior Especializado / DPE-RJ – 2014) Existem diversos tipos de RAID (Redundant Array of Interpendent Disks). O método que permite espalhar os dados em dois ou mais discos físicos, criando um disco lógico de maior capacidade, aumentando a performance mas sem prover redundância ou esquema de correção é conhecido como:
***
RAID 0.
***
RAID 1.
***
RAID 2.
***
RAID 3.
***
RAID 5.
***
A
****
(FUNRIO / Técnico em Informática / SESAU-RO – 2017) Um nível de RAID muito utilizado é conhecido como espelhamento de disco e permite usar dois discos rígidos, onde cada um deles é a cópia idêntica do outro. Ao usar este tipo de RAID caso um dos dois discos falhe, por qualquer motivo, haverá uma cópia operacional e funcional armazenada no outro. Este tipo de RAID é o:
***
RAID 5.
***
RAID 2.
***
RAID 0.
***
RAID 1.
***
RAID 4.
***
D
****
(IF-PE / Analista de Tecnologia da Informação / IF-PE – 2016) RAID (Redundant Array of Inexpensive Disks) é uma técnica de virtualização de disco que pode ser utilizada para aumentar o desempenho e a confiabilidade do sistema de armazenamento de dados em discos. Dentre os vários esquemas disponíveis, um que suporta a falha de mais de um disco, quando utilizado em uma matriz composta de pelo menos 4 discos é a:
***
RAID 1.
***
RAID 5.
***
RAID 0.
***
RAID 4.
***
RAID 2.
***
A
****
(COPEVE-UFAL / Analista do Ministério Público / MPE-AL – 2012) Em se tratando da escolha de um conjunto redundante de discos independentes (RAID) para o sistema de armazenamento físico do banco de dados, qual opção possui o menor tempo de leitura/escrita e a maior eficiência quanto ao armazenamento dos dados?
***
RAID 0
***
RAID 1
***
RAID 2
***
RAID 3
***
RAID 4
***
A
****
(INAZ / Analista de Informática / DPE-PR – 2017) A busca por diversas formas de proteger as informações contidas em seus dispositivos sob quaisquer circunstâncias levou as empresas a adotarem uma solução que utiliza vários discos rígidos em uma disposição específica denominada RAID (Redundant Array os Idependent Drives). Essa solução cria um subsistema de armazenamento composto por vários discos individuais, com finalidade de ganhar segurança e desempenho. Sobre esse assunto, marque a alternativa correta com a descrição do nível da RAID responsável por realizar o que comumente chamamos de mirroring?
***
RAID 0
***
RAID 1
***
RAID 2
***
RAID 3
***
RAID 4
***
B
****
(IBADE / Analista de TI / Câmara de Porto Velho-RO – 2018) Quando um "array" de discos utiliza-se de 2 discos físicos criando um disco lógico (espelhamento), diz-se que o "array" é do tipo:
***
RAID 0.
***
RAID 1.
***
RAID 2.
***
RAID 3.
***
RAID 4.
***
B
****
(CESGRANRIO / Analista de Sistemas / LIQUIGÁS – 2018) RAID (Redundant Array of Independent Disks) é a designação que se dá aos esquemas de armazenamento baseados em múltiplos discos que, para o sistema operacional, são vistos como um único dispositivo, e que permitem maior confiabilidade e desempenho no acesso aos dados devido ao particionamento/espelhamento das informações por esses diferentes discos. Há diferentes estratégias de particionamento/espelhamento, que podem ainda utilizar esquemas de redundância (baseados em paridade) para aumentar a confiabilidade. Essas estratégias dão origem aos diferentes esquemas de RAID, numerados de 0 a 7. Em um dos esquemas de RAID, toda a informação é duplicada, isto é, está toda presente em dois discos físicos diferentes. Esse esquema corresponde ao:
***
RAID 0
***
RAID 1
***
RAID 2
***
RAID 3
***
RAID 5
***
B
****
(UFGD / Técnico de Laboratório / UFGD – 2019) A tecnologia RAID (Matriz Redundante de Discos Independentes) é uma solução computacional que combina vários discos rígidos para formar uma única unidade lógica de armazenamento de dados. A importância de sua utilização consiste em ter várias unidades de armazenamento trabalhando em conjunto de modo que, se um disco rígido sofrer danos, os dados presentes nele não serão perdidos, pois podem ser replicados em outras unidades. É possível também aumentar a capacidade de armazenamento adicionando-se mais discos rígidos. O acesso à informação é mais rápido, pois os dados são distribuídos, entre outras vantagens. Para se aplicar esse sistema, é necessário definir o nível de RAID. Cada nível possui características distintas justamente para atender às mais variadas necessidades. Dessa forma, a Necessidade de Fracionamento em que os dados são divididos em pequenos segmentos e distribuídos entre os discos, não se tendo neste nível proteção contra falhas, pois não há redundância, e sua importância reside no desempenho, ou seja, na soma da velocidade de transmissão de dados de cada unidade, refere-se à característica de qual nível de RAID?
***
RAID 0.
***
RAID 1.
***
RAID 4.
***
RAID 5.
***
RAID 6.
***
A
****
(FCC / Analista Trainee / METRÔ-SP – 2008) A tecnologia para médias e grandes implementações de armazenamento, que possibilita redundância e performance simultaneamente e que exige um mínimo de quatro discos, é denominada:
***
RAID-1.
***
RAID-2.
***
RAID-4.
***
RAID-5.
***
RAID-10.
***
E
****
(IADES / Analista de Tecnologia da Informação / EBSERH – 2013) Redundância significa ter componentes de reserva, a postos, para substituir o principal, caso este falhe por qualquer motivo. no caso dos discos rígidos, existem diferentes modos de operação do RAID. O modo RAID, no qual são usados 2 HDs, onde o primeiro HD armazena dados e o segundo armazena uma cópia exata do primeiro, atualizada em tempo real, é o:
***
RAID 0.
***
RAID 1.
***
RAID 5.
***
RAID 6.
***
RAID 10.
***
B
****
(FUNRIO / Analista de Tecnologia da Informação / IF-PI – 2014) Sobre a tecnologia de armazenamento de dados conhecida como RAID, qual é o nível que requer, no mínimo, três discos e utiliza um esquema de paridade distribuída entre os discos?
***
RAID 0.
***
RAID 1.
***
RAID 2.
***
RAID 5.
***
RAID 10.
***
D
****
(FGV / Analista da Procuradoria / PGE-RO – 2015) A configuração que permite aumentar a confiabilidade e o desempenho do sistema de armazenamento de dados por meio da distribuição de dados em vários discos e utilização da técnica de espelhamento, porém, sem o uso do mecanismo de paridade é:
***
RAID 0;
***
RAID 1;
***
RAID 5;
***
RAID 10;
***
RAID 50.
***
D
****
(CESPE / Técnico em Programação / SERPRO – 2013) Replicação de dados é uma técnica de armazenamento de dados para manter automaticamente a disponibilidade dos dados, a despeito das falhas do servidor.
***
C
****
(FGV / DPE/MT – 2013) O processo de armazenamento que permite a leitura de um arquivo simultaneamente por diversas unidades, aumentando o desempenho e segurança, é denominado:
***
hashing.
***
RAID.
***
CD-ROM.
***
MO.
***
zoneamento.
***
B
****
(IFPB / IFPB – 2013) Algumas placas-mãe possuem um modo que permite que duas ou mais unidades de armazenamento idênticas sejam configuradas para trabalharem em paralelo com o objetivo de aumentar o desempenho, ou então que elas sejam configuradas de modo que a segunda unidade seja uma cópia em tempo real da primeira. Esse modo é chamado de:
***
SLC.
***
CIDR.
***
DNS.
***
RAID.
***
SSHD.
***
D
****
(CS/UFG / CS/UFG – 2015) O significado da sigla RAID e a função da tecnologia que leva esse nome são, respectivamente:
***
Redundant Array of Inexpensive Disks ou conjunto redundante de discos baratos; melhorar o desempenho e a tolerância a falhas do armazenamento de dados em discos rígidos.
***
Ready-Access Internet Device ou dispositivo de acesso imediato à Internet; melhorar a velocidade de acesso a páginas Web e outros conteúdos da Internet.
***
Remote Access to Internet Disks ou acesso remoto para discos na Internet; tornar mais conveniente o acesso a dispositivos de armazenamento de dados na nuvem.
***
Remote Array of Interoperable Disks ou conjunto remoto de discos interoperáveis; permitir o uso conjunto de diferentes tecnologias de discos rígidos para armazenamento de dados em nuvem.:
***
A
****
(FUNDEP / UFVJM/MG– 2015) Com o surgimento de grandes arquivos e dados, gerou-se a necessidade de HDs mais rápidos ou com uma capacidade muito maior de armazenamento.
Assinale a alternativa que apresenta corretamente o sistema que agrega a capacidade e desempenho de vários HDs:
***
RAID
***
NTFS
***
SATA
***
RAM
***
A
****
(AOCP / FUNDASUS – 2015) Uma tecnologia de armazenamento bastante usada é o RAID (Redundant Array of Independent Drives). Sabendo disso, uma matriz que contém dois discos rígidos em que os dados entre os dois são espelhados em tempo real é conhecida como:
***
RAID 10.
***
RAID 5.
***
RAID 3.
***
RAID 1.
***
RAID 0.
***
D
****
(FGV / COMPESA – 2016) RAID é uma solução computacional que permite combinar vários discos rígidos, fazendo com que o sistema operacional enxergue o conjunto de discos rígidos como uma única unidade de armazenamento, independentemente da quantidade de discos rígidos em uso. O nível de RAID que duplica uma unidade de disco, ou seja, faz uma cópia da primeira unidade para outra unidade de disco rígido, é o nível:
***
0.
***
1.
***
3.
***
4.
***
5.
***
B
****
(VUNESP / TJ/SP – 2014) Com relação aos sistemas RAID0 e RAID1, é correto afirmar que:
***
ambos suportam tolerância a falhas.
***
nenhum dos dois suporta tolerância a falhas.
***
apenas o RAID0 suporta tolerância a falhas.
***
RAID1 resulta em espaço de armazenamento maior que RAID0.
***
apenas o RAID1 suporta tolerância a falhas.
***
E
****
(FGV / SEFAZ/RJ – 2014) Atualmente existem placas-mãe de microcomputadores que oferecem níveis RAID ("Redundant Arrays of Independent Disks"), para tornar o sistema de disco mais rápido e mais seguro. No que diz respeito à tolerância a falhas, um dos níveis, conhecido por espelhamento, se caracteriza pelos seguintes fatos:
I. O conteúdo de um disco rígido é inteiramente copiado para outro. Se ocorrer qualquer pane no disco rígido principal, o segundo entra em ação. Assim, o espelhamento constitui um backup automático feito por hardware, executado automaticamente pela placa-mãe, aumentando a segurança, não sendo necessário nenhum tipo de configuração no sistema operacional para que seja realizado.
II. O processo não precisa ser feito no momento da formatação do disco rígido e instalação do sistema operacional. No momento da configuração, que é feito por um setup próprio, o conteúdo do disco rígido principal será copiado para o disco rígido de backup.
Em consequência, consegue-se a redundância dos dados nos discos, pois os dois conterão as mesmas informações. Caso um dos discos pare, o outro, por armazenar o mesmo conteúdo, manterá todo o sistema operacional. Esse nível de tolerância a falhas é denominado:
***
RAID-5.
***
RAID-4.
***
RAID-3.
***
RAID-1.
***
RAID-0.
***
D
****
(VUNESP / TJ/SP – 2015) Na configuração de um servidor físico que possui 4 discos rígidos idênticos e uma controladora array, deseja-se obter um arranjo de um sistema RAID que proporcione requisitos de tolerância à falha e, também, resulte no melhor aproveitamento no espaço de armazenamento (do arranjo) e desempenho. Esses 4 discos devem ser configurados como arranjo:
***
RAID0
***
RAID1
***
RAID50 (5+0)
***
RAID5
***
RAID10 (1+0)
***
D
****
(CESPE / ANAC – 2016) O RAID 5 é similar ao RAID 4, mas armazena informação ECC (Error Correcting Code), de controle de erros, no lugar da paridade:
***
E
****
(VUNESP / TJ/SP – 2015) Um servidor possui 8 discos físicos idênticos de 1TB (cada disco) e uma controladora array. O administrador pretende configurar os 8 discos com RAID5 ou RAID10 (1+0). Na configuração com RAID5, resultará em espaço total de armazenamento _________ TB e, na configuração RAID10 (1+0), resultará em espaço total de armazenamento ________ TB.
Assinale a alternativa que completa, correta e respectivamente, as lacunas do texto.
***
8 ... 6
***
7 ... 4
***
6 ... 4
***
7 ... 6
***
8 ... 7
***
B
****
(FGV / ALERJ – 2017) Aumentar a confiabilidade e o desempenho do sistema de armazenamento de dados é um requerimento de infraestrutura comumente observado pelas empresas. Uma forma de atingir esse objetivo é por meio da estratégia de distribuir os dados em vários discos combinada com a utilização da técnica de espelhamento, porém, sem o uso do mecanismo de paridade. Essa estratégia é denominada:
***
RAID 0;
***
RAID 1;
***
RAID 5;
***
RAID 10;
***
RAID 50.
***
D
****
(FGV / IBGE – 2017) Para melhorar o desempenho e a segurança do disco rígido do sistema computacional de uma organização foi decidido utilizar um mecanismo que implementa o espelhamento de disco. Por meio deste mecanismo, todos os dados do sistema são gravados em dois discos diferentes. Caso um setor de um dos discos falhe é possível recuperá-lo copiando os dados contidos no segundo disco. Esse mecanismo de espelhamento de disco é denominado:
***
RAID 0;
***
RAID 1;
***
RAID 2;
***
RAID 5;
***
RAID 10.
***
B
****
(IBFC / PC-RJ – 2013) Frequentemente usado como uma solução para o conceito de Conjunto Redundante de Discos Independentes, superando alguns dos problemas mais comuns sofridos por esse tipo. As informações sobre paridade para os dados do array são distribuídas ao longo de todos os discos do array, ao invés de serem armazenadas num único disco, oferecendo assim mais desempenho, e simultaneamente, tolerância a falhas:
***
RAID 5
***
RAID 3
***
RAID 0
***
RAID 10
***
RAID 100
***
A
****
(IBFC / PC-RJ – 2013) RAID (Redundant Array of Independent Disks) ou arranjo redundante de discos independentes é um meio de se criar um sub-sistema de armazenamento composto por vários discos individuais, com a finalidade de ganhar segurança e desempenho. O nível de RAID que implementa a espelhamento de disco, também conhecido como mirror é o:
***
RAID 4.
***
RAID 1.
***
RAID 0.
***
RAID Linear.
***
RAID 5.
***
B
****
(FGV / TCE-SE – 2015) Para aumentar a confiabilidade e o desempenho do sistema de armazenamento de dados da empresa, você recomendou combinar vários discos aplicando a técnica RAID para distribuir dados entre eles. Em relação às técnicas RAID, analise as seguintes características:
1. Todos os dados são sempre gravados em dois discos, garantindo redundância da informação.
2. Para obter melhor desempenho, os dados devem ser distribuídos em vários discos.
3. A informação de paridade não é distribuída nos discos do grupo RAID.
A configuração RAID que atende a essas características é:
***
RAID 0;
***
RAID 1;
***
RAID 5;
***
RAID 10;
***
RAID 50.
***
D
****
(QUADRIX / SERPRO – 2014) Os discos da matriz são divididos em 2 grupos. Na escrita, os dados são gravados igualmente nos 2 grupos. Na leitura, os dados podem ser lidos de qualquer um dos grupos. Normalmente, ela é feita alternando-se os discos, processo conhecido por round robin, mas pode haver um disco preferencial para leitura, no caso de haver um disco mais rápido que outro. Não há geração de paridade, mas sim uma redundância completa dos dados. Esse método tem se tornado popular pela sua simplicidade e praticidade em caso de falha de um dos discos. Porém, possui as desvantagens de utilizar apenas metade da capacidade total de discos, além de não trazer nenhum aumento de performance:
***
RAID 3.
***
RAID 5.
***
RAID 10.
***
RAID 1.
***
RAID 0.
***
D
****
(IBFC / EBSERH – 2016) O nível de RAID (RedundantArray oflnexpensive Drives) que implementa os recursos de mirroring e de striping simultaneamente, aliando performance e redundância, e exigindo no mínimo quatro discos rígidos é o:
***
RAID 8
***
RAID 2
***
RAID 4
***
RAID 10
***
RAID 3
***
D
****
(IBFC / EBSERH – 2016) Na implementação de um RAID (Redundant Array of Independent Disks) que permita que os dados sejam segmentados através de grupos de discos espelhados, isto é, os dados são primeiro espelhados para depois serem segmentados é a solução denominada:
***
RAID 20 (ou RAID 2+0) 
***
RAID 02 (ou RAID 0+2) 
***
RAID 10 (ou RAID 1+0) 
***
RAID 50 (ou RAID 5+0) 
***
RAID 01 (ou RAID 0+1) 
***
C
****
(FUNECE / UECE – 2017 Identifique, dentre as alternativas a seguir, aquela que contém somente níveis válidos do sistema de armazenamento RAID (Redundant Array of Independent Disks, ou Conjunto Redundante de Discos Independentes).
***
RAID 0 e RAID1
***
RAID++ e RAID--
***
xRAID 2.7 e xRAID 4.7 
***
RAID2015 e RAID2016 
***
A
****
(CESGRANRIO / BNDES – 2013) RAID (Redundant Array of Inexpensive Disks) é uma tecnologia de armazenamento que permite combinar vários discos individuais com o objetivo de fornecer maior segurança e/ou desempenho. Considere um sistema de armazenamento formado por 6 discos iguais (com capacidade total de 12TB) e que utilize a tecnologia RAID.
Qual será a capacidade total disponível estimada para armazenamento de dados significativos de acordo com a tecnologia especificada?
Dado
No desenvolvimento da resolução do problema considere os bits de paridade como dados não significativos.
***
RAID 6 - 10TB
***
RAID 6 - 8TB
***
RAID 6 - 6TB
***
RAID 5 - 8TB
***
RAID 5 - 6TB
***
B
****
(IBFC / TRE-AM – 2014) “O __________ implementa o espelhamento de disco, também conhecido como mirror, para esta implementação são necessários no mínimo________ discos”.
Assinale a alternativa que completa correta e respectivamente as lacunas:
***
RAID 0 - dois
***
RAID 1 - dois
***
RAID 3 - três
***
RAID 5 - três
***
B