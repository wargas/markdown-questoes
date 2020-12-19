(FUNDEP / UFVJM-MG / 2017) Qual comando SQL é necessário para listar os itens na tabela de PRODUTOS ordenados por NOME, começando pelo final do alfabeto?
***
SELECT * FROM PRODUTOS ORDER BY NOME 
***
SELECT ALL FROM PRODUTOS ORDER BY NOME 
***
SELECT * FROM PRODUTOS ORDER BY NOME INVERT 
***
SELECT * FROM PRODUTOS ORDER BY NOME DESC.
***
D
****
(AOCP / EBSERH – 2017) Usando como referência o padrão SQL-92, assinale a alternativa que exemplifica corretamente um comando de inserção de dados em uma tabela usando a linguagem SQL.
***
INSERT SALDO SET CONTA = 25 AND CLIENTE = 12 
***
INSERT INTO CONTA (ID_CONTA, ID_CLIENTE, SALDO) VALUES (1, 12, 993.56) 
***
INSERT CONTA WHERE SALDO < 12.01 
***
CREATE REGISTER CONTA FROM VALOR = 598.01 AND ID = 58 
***
UPDATE CONTA SET CLIENTE = 31 AND SALDO = 554,32 
***
B
****
(AOCP / EBSERH – 2017) A linguagem SQL é subdividida em subconjuntos, conforme a especificação das operações realizadas em um Banco de Dados (BD). Dentre essas subdivisões, temos a DML (Data Manipulation Linguage), que é responsável por realizar exclusões, inclusões, atualizações e consultas aos dados presentes do BD. Assinale a alternativa que exemplifica um comando de exclusão de registro.
***
DELETE SALDO SET CONTA = 25 
***
ALTER CONTA SET SALDO < 12.01 
***
DELETE CONTA FROM VALOR = 598.01 AND ID = 58 
***
DELETE FROM CONTA WHERE CLIENTE = 31 AND SALDO = 554,32 
***
DROP TABLE CONTA FROM ID = 33 AND CLIENTE = 12
***
D
****
(FCM / IF Farroupilha/RS - 2016) O comando SELECT da linguagem Structured Query Language (SQL) permite acessar dados de um banco de dados.
Uma consulta em linguagem SQL que exiba somente as colunas id_aluno e nome da tabela ALUNO apresenta-se abaixo em:
***
SELECT * FROM ALUNO 
***
SELECT id_aluno, email FROM ALUNO 
***
SELECT id_aluno, nome FROM ALUNO 
***
SELECT email, datacasdastro FROM ALUNO 
***
SELECT nome as nome_aluno FROM ALUNO 
***
C
****
(IBFC / EBSERH - 2016) Com base no comando SQL abaixo assinale a alternativa que tenha a interpretação técnica correta:
DELETE FROM func WHERE tipo IN (‘X’,’Y’);
***
apaga registros de uma tabela tipo que contenha no campo func caracteres iguais a ‘X’ e ‘Y’ 
***
apaga o campo tipo nos registros de uma tabela func que contenham os caracteres iguais a ‘X’ e ‘Y’
***
apaga registros de uma tabela func que contenha no campo tipo caracteres iguais a ‘X’ e ‘Y’ 
***
apaga o campo func nos registros de uma tabela tipo que contenham os caracteres iguais a ‘X’ e ‘Y’
***
apaga qualquer registro de uma tabela func que contenha o campo tipo com caracteres iguais a ‘XY’
***
C
****
(IF-SE / IF-SE – 2016) Em relação aos conceitos de linguagem SQL, avalie as afirmações abaixo:
I. São exemplos de DCL (Linguagem de Controle de Dados): grant e revoke.
II. São exemplos de DML (Linguagem de Manipulação de Dados): select, insert, update e drop.
III. São exemplos de DDL (Linguagem de Definição de Dados): create user, alter table e delete table.
***
Apenas a I é verdadeira 
***
Apenas a II é verdadeira.
***
Apenas a III é verdadeira.
***
As três são verdadeiras.
***
A
****
(FCC / TST – 2017) Um Programador:
I. criou uma tabela e uma view em um banco de dados relacional.
II. alterou a estrutura da tabela.
III. incluiu registros na tabela.
***
DDL − DML − DDL.
***
DML − DML − DDL.
***
DML − DDL − DDL.
***
DDL − DML − DML.
***
DDL − DDL − DML.
***
E
****
(BIO-RIO / IF-RJ - 2015) “A linguagem SQL é do tipo declarativa e constituída das três sublinguagens a seguir:
(1) ____ - inclui os comandos SELECT, INSERT, UPDATE e DELETE;
(2) ____ - inclui os comandos CREATE, ALTER e DROP;
(3) ____ - inclui os comandos GRANT e REVOKE.” As siglas que completam corretamente as lacunas do fragmento acima são respectivamente:
***
DML, DCL e DDL.
***
DML, DDL e DCL.
***
DCL, DDL e DML.
***
DDL, DML e DCL.
***
DDL, DCL e DML.
***
B
****
(FUNRIO / IF-BA – 2016) Um dos mecanismos de segurança em um sistema de banco de dados é o subsistema de autorização, que permite a usuários que têm privilégios específicos concederem de forma seletiva e dinâmica esses privilégios a outros usuários e, subsequentemente, revogarem esses privilégios, se desejarem. Os comandos SQL que permitem a um usuário conceder privilégios a outros usuários e revogar privilégios concedidos a outros usuários são, respectivamente:
***
INSERT PRIVILEGES e DELETE PRIVILEGES.
***
CREATE ROLE e DROP ROLE.
***
CONCEDE e EXCLUDE.
***
GRANT e REVOKE.
***
ALLOW e DISALLOW.
***
D
****
(IBFC / EBSERH – 2016) Relacione as duas colunas quanto aos comandos SQL:
(1) Linguagem de Definição (2) Linguagem de Manipulação (A) INSERT
(B) CREATE
(C) DROP
(D) UPDATE
***
1AD-2BC
***
1BC-2AD
***
1AB-2CD
***
1CD-2AB
***
1AC-2BD
***
B
****
(CESPE / TRE/MT – 2015) Assinale a opção que apresenta a sintaxe correta para se obter, empregando-se a cláusula select em um banco de dados, uma lista com nomes não repetidos dos cargos de uma empresa.
***
select * from cargos 
***
select nome from cargos 
***
select distinct nome from cargos 
***
select codigo, cargo fro cargos where codigo m>1 
***
select nome from cargos order by nome asc 
***
C
****
(FGV / PGE-RO – 2015) No SQL, a outorga de privilégios sobre objetos de um banco de dados é efetuada por meio do comando:
***
CREATE;
***
GRANT;
***
LICENSE;
***
PERMIT;
***
REVOKE.
***
B
****
(Gestão Concurso / EMATER MG – 2018) Para se implementar um banco de dados relacional, bem como para armazenar os dados e posteriormente recuperá-los, faz-se uso da linguagem:
***
DDL.
***
DML.
***
SQL.
***
SGBD.
***
C
****
(FCC / TRT-19 - 2011) Considere as linguagens inseridas no contexto SQL: DML, DDL, DTL, DCL e DQL. Desta forma, Grant, Commit, Update, Delete e Alter, correspondem, respectivamente, a:
==43737==
***
DCL, DCL, DDL, DDL e DDL.
***
DTL, DCL, DML, DDL e DQL.
***
DCL, DTL, DML, DML e DDL.
***
DML, DTL, DCL, DQL e DML.
***
DQL, DDL, DML, DML e DDL.
***
C
****
(FCC / TRE-PI – 2009) Na linguagem SQL, considere os comandos relativos à Linguagem de Definição de Dados ? DDL e à Linguagem de Manipulação de Dados ? DML:
a. ALTER
b. CREATE
c. DELETE
d. DROP
e. INSERT
f. SELECT
g. SET
A associação entre os comandos e suas respectivas linguagens de definição e manipulação de dados está correta em:
***
DDL - abcd // DML - efg.
***
DDL - bfg // DML - acde.
***
DDL - abf // DML - cdeg.
***
DDL - abd // DML - cefg.
***
DDL - acg // DML - bdef.
***
D
****
(ESPP / MPE-PR – 2013) Ao se utilizar a linguagem SQL, aceitamos o conjunto de relações como dado que deve ser especificado no sistema gerenciador de banco de dados por meio de uma linguagem. A linguagem_______________permite não só a especificação de um conjunto de relações, como também informações acerca de cada uma das relações, incluindo: o esquema de cada relação, o domínio dos valores associados a cada atributo, as regras de integridade, o conjunto de índices para manutenção de cada relação, informações sobre segurança e autoridade sobre cada relação e a estrutura de armazenamento físico de cada relação. Assinale a alternativa que completa corretamente a lacuna.
***
DDL
***
DSL
***
DTL
***
DQL
***
DCL
***
A
****
(Instituto Ânima/ Companhia Águas de Joinville – 2010) Para manipular dados em um banco de dados, usamos uma linguagem de consulta estruturada. A SQL (Structured Query Language) é a linguagem usada pela maioria dos bancos de dados. Esta é composta de três outras linguagens, quais são elas?
***
DML, DDL e DLL.
***
DML, DDL e DCL.
***
MLL, DLL e CLL.
***
SQL, LQL e CQL.
***
DDL, DCL e DGL
***
B
****
(FCC / TCM-PA – 2010) Na linguagem SQL são, respectivamente, expressões DDL e DML:
***
UPDATE e DROP INDEX.
***
UPDATE e INSERT INTO.
***
ALTER DATABASE e UPDATE.
***
ALTER TABLE e CREATE INDEX.
***
INSERT INTO e DELETE.
***
C
****
(EXATUS / BANPARÁ – 2015) É um comando do tipo DDL (Data Definition Language) no SQL:
***
SELECT.
***
CREATE.
***
DELETE.
***
INSERT.
***
UPDATE.
***
B
****
(CESPE / TRE/BA - 2010) A instrução GRANT que altera as permissões em objetos-esquema, é uma instrução de DDL (data definition language).
***
E
****
(CCV-UFC / UFC – 2013) Assinale a alternativa em que são apresentados dois comandos da linguagem de definição de dados (DDL).
***
CREATE e ALTER
***
CREATE e GRANT
***
INSERT e DELETE
***
GRANT e REVOKE
***
GRANT e ROLLBACK
***
A
****
(CESGRANRIO / EPE – 2012) A DDL (Data Definition Language) ou linguagem de definição de dados é um conjunto de comandos SQL responsável pela definição das estruturas de dados em um SGBD. Qual comando faz parte da DDL?
***
Select
***
Update
***
Create
***
Delete
***
Insert
***
C
****
(CETRO / AMAZUL – 2015) A linguagem SQL é dividida em subconjuntos de acordo com as operações que se deseja efetuar sobre um banco de dados. Um desses subconjuntos é a DDL.
Assinale a alternativa que apresenta apenas comandos de DDL.
***
Select e Insert.
***
Create e Drop.
***
Update e Select.
***
Revoke e Alter.
***
Delete e Truncate.
***
B
****
(FCC / TRE/SE – 2007) Em SQL-ANSI, Count:
***
é um comando de intersecção no contexto da DML.
***
é uma função de agregação no contexto da DML.
***
é um operador de conjunto no contexto da DDL.
***
é uma função de restrição no contexto da DML.
***
é uma expressão de seleção no contexto da DDL.
***
B
****
(FCC / METRÔ-SP – 2010) O SQL (Structured Query Language) é uma linguagem de pesquisa declarativa para banco de dados relacional. A DDL permite ao usuário definir tabelas novas e elementos associados. A sigla DDL significa:
***
Data Definition List.
***
Data Default Language.
***
Data Definition Language.
***
Data Default List.
***
Definition Data Language.
***
C
****
(CONSULPLAN / TSE – 2012) Ao contrário das linguagens tradicionais, que são procedimentais, SQL é uma linguagem declarativa, que integra três sublinguagens: Data Manipulation Language (DML), Data Definition Language (DDL) e Data Control Language (DCL). Um comando DML e outro DDL são, respectivamente, 
***
Drop e Grant.
***
Grant e Delete.
***
Delete e Update.
***
Update e Drop.
***
D
****
(FGV / TJ-AM – 2013) A SQL é constituída pela Data Control Language (DCL), a Data Definition Language (DDL) e a Data Manipulation Language (DML).
Assinale a alternativa que apresenta os três comandos que são parte integrante da DDL:
***
REVOKE, GRANT e DELETE 
***
GRANT, DELETE e UPDATE 
***
DELETE, UPDATE e CREATE 
***
CREATE, ALTER e DROP 
***
ALTER, DROP e REVOKE 
***
D
****
(FCC / TER/RS – 2010) São declarações SQL, associadas, respectivamente, a três declarações DML (Data Manipulation Language) e a três declarações DDL (Data Definition Language):
***
UPDATE, INSERT, SELECT, DROP INDEX, ALTER TABLE, CREATE VIEW.
***
DROP VIEW, DROP INDEX, UPDATE, DELETE, ALTER TABLE, INSERT.
***
CREATE, UPDATE, DELETE, DROP VIEW, INSERT, SELECT.
***
CREATE INDEX, CREATE VIEW, DROP VIEW, UPDATE, DELETE, INSERT.
***
INSERT, DELETE, DROP INDEX, ALTER INDEX, UPDATE, SELECT.
***
A
****
(CESPE / STJ – 2008) O comando CREATE INDEX, usado para criar um parâmetro relacionado com uma tabela para buscar dados mais rapidamente, é considerado como DDL.
***
C
****
(CESPE / STM – 2011) Os comandos do grupo DDL (data definition language) do SQL permitem gerar os dados das tabelas que formam um banco de dados.
***
C
****
(FUMARC / TJ-MG – 2012) A linguagem SQL possui comandos de definição de dados (DDL - Data Defnition Language), dos quais faz parte o seguinte comando:
***
SELECT
***
DELETE
***
ALTER
***
UPDATE
***
C
****
(FAFIPA / UFFS – 2014) Os comandos SQL podem ser divididos basicamente em três categorias: DML, DDL e DCL. Assinale a alternativa que apresenta um comando DCL:
***
SELECT
***
INSERT
***
ALTER
***
GRANT
***
DROP
***
D
****
(IBFC / EBSERH – 2016) Relacione os subconjuntos do SQL da coluna da esquerda com os seus respectivos comandos da coluna da direita:
(1) DDL
(2) DML
(A) UPDATE
(B) CREATE
(C) INSERT
(D) DROP.
***
1A - 1C - 2B - 2D 
***
1A - 1B - 2C - 2D 
***
1C - 1D - 2A - 2B 
***
1B - 1C - 2A - 2D 
***
1B - 1D - 2A - 2C
***
E
****
(AOCP / EBSERH – 2015) De acordo com o conceito da DDL – Linguagem de definição de dados – quais comandos são utilizados na linguagem SQL?
***
SELECT, GRANT, DENY, REVOKE.
***
INSERT, UPDATE, GRANT, DROP.
***
CREATE, ALTER, DROP.
***
ALTER, DENY, GRANT.
***
GRANT, DENY, REVOKE.
***
C
****
(FUNCAB / PRODAM-AM – 2014) Se trata de um comando considerado parte da linguagem de definição de dados (DDL) e um comando considerado parte da linguagem de manipulação de dados (DML) do SQL, respectivamente:
***
CREATE e DROP
***
DROP e UPDATE
***
DELETE e CREATE
***
INSERTe UPDATE
***
SELECT e TRUNCATE 
***
B
****
(FCC / TRF-4ª Região – 2010) DROP é um comando utilizado para apagar um objeto do banco de dados e é parte integrante do subconjunto da linguagem SQL denominado:
***
DML - Linguagem de Manipulação de Dados.
***
DTL - Linguagem de Transação de Dados.
***
DCL - Linguagem de Controle de Dados.
***
DDL - Linguagem de Definição de Dados.
***
DQL - Linguagem de Consulta de Dados.
***
D
****
(NUCEPE / SEDUC-PI – 2015) O SQL é uma linguagem de manipulação de banco de dados.
Assinale a alternativa CORRETA sobre os subconjuntos do SQL:
***
DML – Linguagem de Transação de Dados.
***
DDL – Linguagem de Controle de Dados.
***
DCL – Linguagem de Definição de Dados.
***
DTL – Linguagem de Manipulação de Dados.
***
DQL – Linguagem de Consulta de Dados.
***
E
****
(FCC / MPE-SE – 2010) Em relação às linguagens de definição e de manipulação de dados no SQL, é correto afirmar:
***
no grupo DDL, apagar tabelas e índices da base de dados é função do comando DROP.
***
no grupo DML, conceder acesso à base de dados e aos seus objetos é função do comando ALTER.
***
no grupo DDL, o comando SELECT é utilizado para extrair e alterar dados da base de dados.
***
o grupo DDL contém os comandos para criar e alterar novas tuplas no banco de dados.
***
o comando ALTER, do grupo DML, tem como função alterar linhas já existentes no banco de dados.
***
A
****
(FCC / MANAUSPREV – 2015) A linguagem SQL é dividida em subconjuntos de acordo com as operações que se deseja efetuar sobre um banco de dados. Considere os grupos de comandos:
I. CREATE, ALTER, DROP.
II. GRANT, REVOKE.
III. DELETE, UPDATE, INSERT.
Os comandos listados em 
***
I correspondem à Data Control Language - DCL e II à Data Definition Language - DDL.
***
I correspondem à Data Manipulation Language - DML e III à Data Control Language - DCL.
***
II correspondem à Data Manipulation Language - DML e III à Data Control Language - DCL.
***
I correspondem à Data Definition Language - DDL e III à Data Manipulation Language - DML.
***
II correspondem à Data Control Language - DCL e III à Data Definition Language - DDL.
***
D
****
(CEPERJ / CEPERJ – 2013) A linguagem SQL para bancos de dados, é constituída das sublinguagens “Data Manipulation Language – DML”, “Data Definition Language – DDL” e “Data Control Language – DCL”. Fazem parte da DCL os seguintes comandos:
***
SELECT e DROP
***
DROP e GRANT
***
GRANT e REVOKE
***
REVOKE e DELETE
***
DELETE e SELECT
***
C
****
(IF-RJ / IF-RJ– 2010) A linguagem SQL possui sublinguagens. Dentre elas, destacamos a DDL, de definição de dados; a DML, de manipulação de dados e a DCL, de controle de dados.
Marque a alternativa que possui um comando de cada sublinguagem.
***
Create, Drop, Select 
***
Create, Insert, Alter 
***
Select, Insert, Update 
***
Insert, Revoke, Update 
***
Create, Delete, Grant 
***
E
****
(CESPE / MEC – 2015) A DML utiliza o comando CREATE para inserir um novo registro na tabela de dados.
***
E
****
(IBFC / EBSERH – 2013) Relacione os comandos típicos utilizados em cada Linguagem conforme tabela abaixo:
(A) UPDATE
(B) GRANT
(C) CREATE
(D) Linguagem de definição de dados (DDL) 
(E) Linguagem de manipulação de dados (DML) 
(F) Linguagem de controle de dados (DCL) 
***
AD - BE - CF
***
AD - BF - CE
***
AE - BD - CF
***
AE - BF - CD
***
D
****
(IFB / IFB – 2017) Considerando-se a descrição sobre SQL (Structured Query Language), assinale a única alternativa onde a sequência de comandos SQL (da esquerda para a direita) está associada corretamente à sequência de categorias {comando DML, comando DDL, comando TCL}.
***
{CREATE, UPDATE, ROOLBACK} 
***
{DELETE, COMMIT, INSERT} 
***
{UPDATE, ALTER, COMMIT} 
***
{CREATE, REVOKE, COMMIT} 
***
{INSERT, DROP, GRANT} 
***
C
****
(IBFC / TRE-AM – 2014) Relacione as duas colunas, quanto aos comandos SQL e os respectivos subconjuntos da linguagem SQL:
(1) GRANT (A) DCL
(2) DROP (B) DML
(3) COMMIT (C) DDL 
(4) UPDATE (D) DTL 
Assinale a alternativa correta:
***
1A-2C-3D-4B
***
1A-2D-3C-4B
***
1B-2C- 3D- 4A
***
1C-2A-3D-4B
***
A
****
(CEPERJ / PROCON-RJ – 2012) SQL representa uma linguagem declarativa, não procedural, que permite interação com bancos de dados, sendo constituída de três sublinguagens, a Data Manipulation Language (DML), a Data Definition Language (DDL) e a Data Control Language (DCL). Como comandos DCL, um permite conceder determinado privilégio a um usuário e outro permite retirar o privilégio concedido. Esses comandos são, respectivamente:
***
GET e PUT
***
CREATE e DROP
***
SELECT e DELETE
***
GRANT e REVOKE
***
INSERT e REMOVE
***
D
****
(SUGEP - UFRPE / UFRPE – 2018) A respeito da linguagem SQL, analise as proposições abaixo.
1) Um dos comandos do DML (Data Manipulation Language) é o INSERT.
2) CREATE e DELETE são comandos da DDL (Data Definition Language).
3) Dois comandos do DCL (Data Control Language) são UPDATE E DROP.
Está(ão) correta(s), apenas:
***
1.
***
1 e 2.
***
2 e 3.
***
3.
***
1 e 3.
***
A
****
48.(IESES / CRF-SC – 2012) Relacione a primeira coluna com a segunda e em seguida identifique a alternativa que apresenta a ordem correta dos números de cima para baixo:
(1) – DDL ( ) - É um subconjunto de comandos SQL que serve para a definição das estruturas de dados de um banco de dados, como por exemplo, criar tabelas, índices, views, etc.
(2) – DML ( ) - É um subconjunto de comandos SQL que permite a DBAs controlar o acesso aos dados de um banco de dados.
(3) – DCL ( ) - É um subconjunto de comandos SQL que serve para acesso, inclusão, alteração e exclusão dos dados de um banco de dados.
***
1 – 3 – 
***
3 – 1 – 
***
1 – 2 – 
***
2 – 3 – 
***
A
****
(COSEAC / UFF – 2017) Na linguagem de manipulação de dados DML, os comandos que permitem remover linhas existentes em uma tabela e mudar os valores de dados em uma ou mais linhas da tabela existente são, respectivamente:
***
DELETE e UPDATE.
***
DROP e ALTER TABLE.
***
REVOKE e UPDATE.
***
DELETE e CREATE.
***
DROP e ALTER INDEX.
***
A
****
(CESPE / STJ – 2008) O comando DELETE, capaz de excluir dados de um banco de dados, é considerado como DDL.
***
E
****
(UFBA / UNILAB – 2014) Os comandos commit e rollback são utilizados, respectivamente, para confirmar e desfazer instruções do tipo DML e DDL em um banco de dados.
***
E