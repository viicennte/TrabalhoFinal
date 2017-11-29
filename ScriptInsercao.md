--CURSO
INSERT INTO Curso VALUES (1,'SI','Sistemas de Informa��o');
INSERT INTO Curso VALUES (2,'BD','Banco de Dados');
INSERT INTO Curso VALUES (3,'RC','Redes de Computadores');
INSERT INTO Curso VALUES (4,'ADS','Analise e Desenvolvimento de Sistemas');
INSERT INTO Curso VALUES (5,'JD','Jogos Digitais');

--GRADECURRICULAR
INSERT INTO GradeCurricular VALUES (1,5, 2016,4);
INSERT INTO GradeCurricular VALUES (2,3, 2016,1);
INSERT INTO GradeCurricular VALUES (3,4, 2016,2);
INSERT INTO GradeCurricular VALUES (4,2, 2016,3);
INSERT INTO GradeCurricular VALUES (5,1, 2016,5);

--PERIODO
INSERT INTO Periodo VALUES (1,1, 1);
INSERT INTO Periodo VALUES (2, 3, 1);
INSERT INTO Periodo VALUES (3,3, 3);
INSERT INTO Periodo VALUES (4,5, 1);
INSERT INTO Periodo VALUES (5,5, 2);
INSERT INTO Periodo VALUES (6,5, 3);
INSERT INTO Periodo VALUES (7,7, 3);
INSERT INTO Periodo VALUES (8,9, 1);
INSERT INTO Periodo VALUES (9,9, 3);
INSERT INTO Periodo VALUES (10,2, 1);
INSERT INTO Periodo VALUES (11,2, 2);
INSERT INTO Periodo VALUES (12, 2, 3);

--DISCIPLINA
INSERT INTO Disciplina VALUES (1,'Algoritmos', 40, 5, 95, 'No��es de L�gica. Introdu��o a Algoritmos. Resolu��o de problemas utilizando
															algoritmos e racioc�nio l�gico. Tipos de Dados. Vari�veis e Constantes.
															Express�es e Operadores. Estruturas de Controle: Estruturas B�sicas,
															Estruturas Condicionais e Estruturas de Repeti��o. Estruturas B�sicas de
															Dados: Vetores, Matrizes e Registros. Arquivos. Fun��es.', 
															'Possibilitar ao aluno o desenvolvimento de formas de representa��es computacionais de
															problemas reais, atrav�s de algoritmos simples.',
															'No decorrer da disciplina ser�o trabalhadas as seguintes habilidades: - utilizar de forma correta 
															(conforme a sintaxe da linguagem) as estruturas da linguagem (declara��o de vari�veis, condicionais,
															 la�os de repeti��o) - conhecer as palavras reservadas e sua utiliza��o - trabalhar com tipos de 
															 dados primitivos (imut�veis) e tipos de dados por refer�ncia (mut�veis) - desenvolver programas 
															 seguindo o formato de programa��o procedural - compreender e utilizar a modulariza��o de 
															 algoritmos atrav�s de fun��es ou m�todos.', 
															 '� I UNIDADE � APRESENTA��O E INTRODU��O A ALGORITMOS � ALGORITMOS: VARI�VEIS, OPERADORES E CONSTANTES
															 � ALGORITMOS: ESTRUTURAS DE SELE��O � VISUALG: AULA PR�TICA � FUNDAMENTOS � ESTRUTURAS DE REPETI��O
															 � VETORES � VISUALG: AULA PR�TICA � ESTRUTURAS DE REPETI��O � II UNIDADE � VETORES � AULA PR�TICA: VETORES
															 � MODULARIZA��O DE ALGORITMOS � VISUALG: AULA PR�TICA � MODULARIZA��O � VISUALG: AULA PR�TICA � GERAL
															 � PROCESSO DE PROGRAMA��O � LINGUAGENS DE PROGRAMA��O', 
															 'Novatec Editora. ISBN 85-7522-073-X',
															 'Donald E. Knuth (1973) The Art of Computer Programming, Volume 1: Fundamental Algorithms (2� edi��o). Addison-Wesley, ISBN 0-201-03809-9 (em ingl�s)
																? CHARLES E. LEISERSON, Thomas H. Cormen, RONALD L. RIVEST, CLIFFORD STEIN , Algoritmos: teoria e pr�tica , CAMPUS - RJ, 2002 ISBN 8-535-20926-3');
INSERT INTO Disciplina VALUES (2,'Arquitetura de Computadores', 60, 10, 90, 'Estrutura b�sica de computadores. A Unidade Central de Processamento. Estruturas de barramentos. Organiza��o de mem�ria. Sistemas 
																				de entrada/sa�da. Suporte ao sistema operacional. Padr�es de arquiteturas. Introdu��o a arquiteturas dedicadas.',
																			'Identificar o funcionamento e relacionamento entre os componentes de computadores e seus perif�ricos;
																				Instalar e configurar computadores, isolados ou em redes, perif�ricos e softwares.
																				Identificar a origem de falhas no funcionamento de computadores, perif�ricos e softwares avaliando seus efeitos;',
																			'Capacitar o aluno nos conceitos gerais de administra��o de redes de computadores e
																				gest�o de recursos ',
																			' Arquitetura de von >euman. T�cnicas de Pipeline.
																				� Introdu��o �s Arquiteturas RISC e CISC.',
																			'TANENBAUM, ANDREW S. Redes de Computadores. Rio de Janeiro, Campus, quarta
																				edi��o, 2003.',
																			'SOARES, Luiz Fernando Gomes. Redes de Computadores: das LANs, MANs e WANs �s
																				redes ATM. Rio de Janeiro: Campus, 1995.');
INSERT INTO Disciplina VALUES (3,'Banco de Dados', 80, 15, 85, 'Introdu��o aos sistemas de ger�ncia de bancos de dados. Projeto de banco de dados: 
																	conceitual, l�gico e f�sico. Modelo conceitual de entidades e relacionamentos. Modelo 
																	de dados relacional. Depend�ncias funcionais e normaliza��o. Linguagens de defini��o e 
																	de manipula��o de dados. �lgebra relacional e sql. Restri��es de integridade e vis�es. 
																	Organiza��o f�sica de bancos de dados: t�cnicas de armazenamento e indexa��o.',
																'Para o exerc�cio destas atividades, o aluno deve adquirir compet�ncias em:
																	acompanhar a evolu��o das tecnologias de informa��o de forma aut�noma e independente;
																	prospectar novas tecnologias da informa��o e auxiliar sua incorpora��o �s estrat�gias, 
																	planejamentos e pr�ticas da organiza��o;
																	empreender a busca de solu��es para os desafios das organiza��es e de novas oportunidades
																	de crescimento profissional;
																	identificar problemas de ordem organizacional, operacional ou sist�mica, relacionados com 
																	dados e informa��es e propor solu��es in�ditas com base t�cnica e cient�fica ou adequar as 
																	j� existentes � realidade, sejam elas automatizadas ou manuais;
																	gerenciar projetos de desenvolvimento de sistemas de Banco de Dados envolvendo atividades em equipe.',
																'O especialista nesta �rea deve capacitar-se para solucionar problemas, por meio da constru��o de modelos
																	de dados, de sua implanta��o e administra��o. Amplamente, estas atividades envolvem habilidades em:
																	planejamento e desenvolvimento projetos de sistemas de bancos de dados;
																	pesquisa dos requisitos e os recursos necess�rios;
																	avaliar o desempenho do sistema, em processos de usu�rios ou grupos;
																	aplica��o de t�cnicas e procedimentos de trabalho, instrumentos, ferramentas convencionais e informatizadas, de acordo com especifica��es;
																	atender usu�rios administrando o banco de dados, dentro dos princ�pios de qualidade, produtividade, podendo, quando for o caso, prestar consultoria ou assessoria t�cnica;
																	conceber e coordenar a elabora��o de projetos de sistemas de bancos de dados, a partir de decis�es em grupo de trabalho;
																	controlar e coordenar acessos atrav�s da administra��o de Bancos de Dados e de Usu�rios;
																	planejar e definir recursos de armazenamento de dados.',
																'Banco de Dados e usu�rios de banco de dados. Conceitos e arquiteturas de sistema de banco de dados. Modelagem de dados. Modelos conceituais. 
																	Modelo de dados relacional. Modelo de dados relacional estendido. Depend�ncia funcional e normaliza��o. Projeto de banco de dados 
																	relacional. Metodologia de projeto de banco de dados relacional.',
																'SAY�O, L.F. Modelos te�ricos em ci�ncia da informa��o; abstra��o e m�todo cient�fico. (2001).',
																'COUGO, P. Modelagem Conceitual, 1a Edi��o, Campus, 1997.');
INSERT INTO Disciplina VALUES (4,'Computa��o Gr�fica', 100, 20, 80, 'Computa��o gr�fica: origem e defini��o. Introdu��o ao processamento de imagens. Perif�ricos. Representa��o de objetos. Visualiza��o bidimensional. Visualiza��o tridimensional.
																			Introdu��o ao realismo tridimensional. ',
																		'O cumprimento da disciplina busca dar ao aluno, ao final do semestre, condi��es de:
																			1. Dominar os conceitos b�sicos de Computa��o Gr�fica 2D e 3D;
																			2. Implementar um software que envolva t�cnicas de Computa��o Gr�fica;
																			3. Dimensionar um ambiente de trabalho que envolva perif�ricos com capacidade gr�fica.',
																		' As compet�ncias do profissional de Express�o Gr�fica compreendem uma base s�lida de conhecimentos em Geometria Plana
																			e Espacial, Normas T�cnicas da ABNT e Normas T�cnicas para desenvolvimento de Projetos que o possibilite utilizar
																			na Representa��o de Projetos Auxiliados por Computador nas diversas �reas.
																			O profissional formado dever� ser capaz de:
																			Atuar no setor produtivo, utilizando tecnologias avan�adas em equipes multidisciplinares, criando, experimentando,
																			analisando, simulando e validando os projetos, principalmente quanto ao desenho, � forma e � intera��o com o seu
																			ambiente;
																			Atuar em pesquisas direcionadas ao desenvolvimento de sistemas de inova��o nos setores industriais de diversas 
																			�reas, tais como, ind�stria automobil�stica e de autope�as, ind�stria mec�nica, ind�stria cosm�tica, embalagens,
																			constru��o civil, arquitetura e mobili�rio;
																			Representar modelos atrav�s dos conhecimentos da Express�o e Computa��o Gr�fica;
																			Agregar conhecimentos das �reas de Engenharia, Express�o Gr�fica e novas tecnologias para o desenvolvimento de
																			projetos computadorizados;
																			Utilizar ferramentas gr�ficas computacionais;
																			Simular, analisar e testas os produtos projetados utilizando as ferramentas espec�ficas dispon�veis nos softwares
																			CAD;
																			Desenvolver a capacidade de leitura, interpreta��o e express�o gr�fica;
																			Desenvolver a capacidade de s�ntese, aliada � capacidade de compreens�o e express�o oral e escrita;
																			Conduzir e interpretar resultados de atividades pr�ticas e experimentais;
																			Compreender os problemas socioecon�micos, culturais e do meio ambiente;
																			Conceber, analisar sistemas e processos utilizando a modelagem computacional gr�fica.',
																		'Introdu��o � Computa��o Gr�fica
																		Biblioteca Gr�fica OpenGL
																		Processamento de Imagens
																		Representa��o de Objetos e Cenas
																		Processo de Visualiza��o
																		Curvas e Superf�cies Param�tricas
																		Gera��o de Imagens com Realismo
																		T�picos de Computa��o Gr�fica',
																	'Tanenbaum, A., Computer Arquitecture, 4a edi��o, Prentice Hall., 1998.',
																	'Tanenbaum, A., Organiza��o Estruturada de Computadores, 4a Edi��o, 1999.');
INSERT INTO Disciplina VALUES (5,'Engenharia de Software', 120, 25,75, 'Engenharia de Software: Conceitos e objetivos. Paradigmas de desenvolvimento de software: suas fases e
																		caracter�sticas. T�picos avan�ados em Engenharia de Software.',
																	'Os assuntos ser�o apresentados em aulas expositivas. Os assuntos apresentados ser�o trabalhados em laborat�rio
																		e posteriormente os alunos ser�o convidados a apresentar semin�rio sobre os trabalhos desenvolvidos. ',
																	'Ao longo da disciplina, o aluno dever� desenvolver as seguintes habilidades: 
																		- discutir a evolu��o da engenharia de software; 
																		- diferenciar os principais paradigmas da engenharia de software; 
																		- compreender cada etapa do desenvolvimento de software; 
																		- distinguir os diversos processos de desenvolvimento de software abordados.',
																	'Introdu��o � Engenharia de Software [3 horas-aula]
																		- Evolu��o do Software
																		- Ciclo de vida',
																	'Wazlawick, R. S. An�lise e Projeto de Sistemas Orientados a Objetos. Rio de Janeiro: Campus/Elsevier, 2004.',
																	'Jacobson, I.,Booch, G.,.Rumbaugh, J. The unified software development process, Addison-Wesley, 1999.');

INSERT INTO Disciplina VALUES (6,'Gerenciamento de Projetos de Software', 140, 30, 70, 
															'No��es de L�gica. Introdu��o a Algoritmos. Resolu��o de problemas utilizando
																algoritmos e racioc�nio l�gico. Tipos de Dados. Vari�veis e Constantes.
																Express�es e Operadores. Estruturas de Controle: Estruturas B�sicas,
																Estruturas Condicionais e Estruturas de Repeti��o. Estruturas B�sicas de
																Dados: Vetores, Matrizes e Registros. Arquivos. Fun��es.', 
															'Possibilitar ao aluno o desenvolvimento de formas de representa��es computacionais de
																problemas reais, atrav�s de algoritmos simples.',
															'No decorrer da disciplina ser�o trabalhadas as seguintes habilidades: - utilizar de forma correta 
																(conforme a sintaxe da linguagem) as estruturas da linguagem (declara��o de vari�veis, condicionais,
																la�os de repeti��o) - conhecer as palavras reservadas e sua utiliza��o - trabalhar com tipos de 
																dados primitivos (imut�veis) e tipos de dados por refer�ncia (mut�veis) - desenvolver programas 
																seguindo o formato de programa��o procedural - compreender e utilizar a modulariza��o de 
																algoritmos atrav�s de fun��es ou m�todos.', 
															'� I UNIDADE � APRESENTA��O E INTRODU��O A ALGORITMOS � ALGORITMOS: VARI�VEIS, OPERADORES E CONSTANTES
																 � ALGORITMOS: ESTRUTURAS DE SELE��O � VISUALG: AULA PR�TICA � FUNDAMENTOS � ESTRUTURAS DE REPETI��O
																� VETORES � VISUALG: AULA PR�TICA � ESTRUTURAS DE REPETI��O � II UNIDADE � VETORES � AULA PR�TICA: VETORES
																� MODULARIZA��O DE ALGORITMOS � VISUALG: AULA PR�TICA � MODULARIZA��O � VISUALG: AULA PR�TICA � GERAL
																� PROCESSO DE PROGRAMA��O � LINGUAGENS DE PROGRAMA��O', 
															'Novatec Editora. ISBN 85-7522-073-X',
															'Donald E. Knuth (1973) The Art of Computer Programming, Volume 1: Fundamental Algorithms (2� edi��o). Addison-Wesley, ISBN 0-201-03809-9 (em ingl�s)
																? CHARLES E. LEISERSON, Thomas H. Cormen, RONALD L. RIVEST, CLIFFORD STEIN , Algoritmos: teoria e pr�tica , CAMPUS - RJ, 2002 ISBN 8-535-20926-3');
INSERT INTO Disciplina VALUES (7,'Intelig�ncia Artificial', 80, 30, 70, 'Estrutura b�sica de computadores. A Unidade Central de Processamento. Estruturas de barramentos. Organiza��o de mem�ria. Sistemas 
																				de entrada/sa�da. Suporte ao sistema operacional. Padr�es de arquiteturas. Introdu��o a arquiteturas dedicadas.',
																			'Identificar o funcionamento e relacionamento entre os componentes de computadores e seus perif�ricos;
																				Instalar e configurar computadores, isolados ou em redes, perif�ricos e softwares.
																				Identificar a origem de falhas no funcionamento de computadores, perif�ricos e softwares avaliando seus efeitos;',
																			'Capacitar o aluno nos conceitos gerais de administra��o de redes de computadores e
																				gest�o de recursos ',
																			' Arquitetura de von >euman. T�cnicas de Pipeline.
																				� Introdu��o �s Arquiteturas RISC e CISC.',
																			'TANENBAUM, ANDREW S. Redes de Computadores. Rio de Janeiro, Campus, quarta
																				edi��o, 2003.',
																			'SOARES, Luiz Fernando Gomes. Redes de Computadores: das LANs, MANs e WANs �s
																				redes ATM. Rio de Janeiro: Campus, 1995.');
INSERT INTO Disciplina VALUES (8,'Intera��o humano-computador', 80, 20, 80, 'Introdu��o aos sistemas de ger�ncia de bancos de dados. Projeto de banco de dados: 
																				conceitual, l�gico e f�sico. Modelo conceitual de entidades e relacionamentos. Modelo 
																				de dados relacional. Depend�ncias funcionais e normaliza��o. Linguagens de defini��o e 
																				de manipula��o de dados. �lgebra relacional e sql. Restri��es de integridade e vis�es. 
																				Organiza��o f�sica de bancos de dados: t�cnicas de armazenamento e indexa��o.',
																			'Para o exerc�cio destas atividades, o aluno deve adquirir compet�ncias em:
																				acompanhar a evolu��o das tecnologias de informa��o de forma aut�noma e independente;
																				prospectar novas tecnologias da informa��o e auxiliar sua incorpora��o �s estrat�gias, 
																				planejamentos e pr�ticas da organiza��o;
																				empreender a busca de solu��es para os desafios das organiza��es e de novas oportunidades
																				de crescimento profissional;
																				identificar problemas de ordem organizacional, operacional ou sist�mica, relacionados com 
																				dados e informa��es e propor solu��es in�ditas com base t�cnica e cient�fica ou adequar as 
																				j� existentes � realidade, sejam elas automatizadas ou manuais;
																				gerenciar projetos de desenvolvimento de sistemas de Banco de Dados envolvendo atividades em equipe.',
																			'O especialista nesta �rea deve capacitar-se para solucionar problemas, por meio da constru��o de modelos
																				de dados, de sua implanta��o e administra��o. Amplamente, estas atividades envolvem habilidades em:
																				planejamento e desenvolvimento projetos de sistemas de bancos de dados;
																				pesquisa dos requisitos e os recursos necess�rios;
																				avaliar o desempenho do sistema, em processos de usu�rios ou grupos;
																				aplica��o de t�cnicas e procedimentos de trabalho, instrumentos, ferramentas convencionais e informatizadas, de acordo com especifica��es;
																				atender usu�rios administrando o banco de dados, dentro dos princ�pios de qualidade, produtividade, podendo, quando for o caso, prestar consultoria ou assessoria t�cnica;
																				conceber e coordenar a elabora��o de projetos de sistemas de bancos de dados, a partir de decis�es em grupo de trabalho;
																				controlar e coordenar acessos atrav�s da administra��o de Bancos de Dados e de Usu�rios;
																				planejar e definir recursos de armazenamento de dados.',
																			'Banco de Dados e usu�rios de banco de dados. Conceitos e arquiteturas de sistema de banco de dados. Modelagem de dados. Modelos conceituais. 
																				Modelo de dados relacional. Modelo de dados relacional estendido. Depend�ncia funcional e normaliza��o. Projeto de banco de dados 
																				relacional. Metodologia de projeto de banco de dados relacional.',
																			'SAY�O, L.F. Modelos te�ricos em ci�ncia da informa��o; abstra��o e m�todo cient�fico. (2001).',
																			'COUGO, P. Modelagem Conceitual, 1a Edi��o, Campus, 1997.');
INSERT INTO Disciplina VALUES (9,'Linguagens de Programa��o', 80, 10, 90, 'Computa��o gr�fica: origem e defini��o. Introdu��o ao processamento de imagens. Perif�ricos. Representa��o de objetos. Visualiza��o bidimensional. Visualiza��o tridimensional.
																				Introdu��o ao realismo tridimensional. ',
																			'O cumprimento da disciplina busca dar ao aluno, ao final do semestre, condi��es de:
																				1. Dominar os conceitos b�sicos de Computa��o Gr�fica 2D e 3D;
																				2. Implementar um software que envolva t�cnicas de Computa��o Gr�fica;
																				3. Dimensionar um ambiente de trabalho que envolva perif�ricos com capacidade gr�fica.',
																			'As compet�ncias do profissional de Express�o Gr�fica compreendem uma base s�lida de conhecimentos em Geometria Plana
																				e Espacial, Normas T�cnicas da ABNT e Normas T�cnicas para desenvolvimento de Projetos que o possibilite utilizar
																				na Representa��o de Projetos Auxiliados por Computador nas diversas �reas.
																				O profissional formado dever� ser capaz de:
																				Atuar no setor produtivo, utilizando tecnologias avan�adas em equipes multidisciplinares, criando, experimentando,
																				analisando, simulando e validando os projetos, principalmente quanto ao desenho, � forma e � intera��o com o seu
																				ambiente;
																				Atuar em pesquisas direcionadas ao desenvolvimento de sistemas de inova��o nos setores industriais de diversas 
																				�reas, tais como, ind�stria automobil�stica e de autope�as, ind�stria mec�nica, ind�stria cosm�tica, embalagens,
																				constru��o civil, arquitetura e mobili�rio;
																				Representar modelos atrav�s dos conhecimentos da Express�o e Computa��o Gr�fica;
																				Agregar conhecimentos das �reas de Engenharia, Express�o Gr�fica e novas tecnologias para o desenvolvimento de
																				projetos computadorizados;
																				Utilizar ferramentas gr�ficas computacionais;
																				Simular, analisar e testas os produtos projetados utilizando as ferramentas espec�ficas dispon�veis nos softwares
																				CAD;
																				Desenvolver a capacidade de leitura, interpreta��o e express�o gr�fica;
																				Desenvolver a capacidade de s�ntese, aliada � capacidade de compreens�o e express�o oral e escrita;
																				Conduzir e interpretar resultados de atividades pr�ticas e experimentais;
																				Compreender os problemas socioecon�micos, culturais e do meio ambiente;
																				Conceber, analisar sistemas e processos utilizando a modelagem computacional gr�fica.',
																			'Introdu��o � Computa��o Gr�fica
																				Biblioteca Gr�fica OpenGL
																				Processamento de Imagens
																				Representa��o de Objetos e Cenas
																				Processo de Visualiza��o
																				Curvas e Superf�cies Param�tricas
																				Gera��o de Imagens com Realismo
																				T�picos de Computa��o Gr�fica',
																			'Tanenbaum, A., Computer Arquitecture, 4a edi��o, Prentice Hall., 1998.',
																			'Tanenbaum, A., Organiza��o Estruturada de Computadores, 4a Edi��o, 1999.');
INSERT INTO Disciplina VALUES (10,'Mecatr�nica', 80, 0, 100, 'Engenharia de Software: Conceitos e objetivos. Paradigmas de desenvolvimento de software: suas fases e
																caracter�sticas. T�picos avan�ados em Engenharia de Software.',
															'Os assuntos ser�o apresentados em aulas expositivas. Os assuntos apresentados ser�o trabalhados em laborat�rio
																e posteriormente os alunos ser�o convidados a apresentar semin�rio sobre os trabalhos desenvolvidos. ',
															'Ao longo da disciplina, o aluno dever� desenvolver as seguintes habilidades: 
																- discutir a evolu��o da engenharia de software; 
																- diferenciar os principais paradigmas da engenharia de software; 
																- compreender cada etapa do desenvolvimento de software; 
																- distinguir os diversos processos de desenvolvimento de software abordados.',
															'Introdu��o � Engenharia de Software [3 horas-aula]
																- Evolu��o do Software
																- Ciclo de vida',
															'Wazlawick, R. S. An�lise e Projeto de Sistemas Orientados a Objetos. Rio de Janeiro: Campus/Elsevier, 2004.',
															'Jacobson, I.,Booch, G.,.Rumbaugh, J. The unified software development process, Addison-Wesley, 1999.');

--PERIODODISCIPLINA
INSERT INTO PeriodoDisciplina VALUES (1,1,2);
INSERT INTO PeriodoDisciplina VALUES (2,1,4);
INSERT INTO PeriodoDisciplina VALUES (3,1,6);
INSERT INTO PeriodoDisciplina VALUES (4,1,8);
INSERT INTO PeriodoDisciplina VALUES (5,1,10);
INSERT INTO PeriodoDisciplina VALUES (6,3,1);
INSERT INTO PeriodoDisciplina VALUES (7,5,2);
INSERT INTO PeriodoDisciplina VALUES (8,7,3);
INSERT INTO PeriodoDisciplina VALUES (9,9,4);
INSERT INTO PeriodoDisciplina VALUES (10,10,5);

--DISCIPLINAOFERTADA
INSERT INTO DisciplinaOfertada VALUES (1,1,2017,'1');
INSERT INTO DisciplinaOfertada VALUES (2,2,2017,'2');
INSERT INTO DisciplinaOfertada VALUES (3,3,2017,'1');
INSERT INTO DisciplinaOfertada VALUES (4,4,2017,'2');
INSERT INTO DisciplinaOfertada VALUES (5,5,2017,'2');
INSERT INTO DisciplinaOfertada VALUES (6,6,2017,'2');
INSERT INTO DisciplinaOfertada VALUES (7,7,2017,'1');
INSERT INTO DisciplinaOfertada VALUES (8,8,2017,'1');
INSERT INTO DisciplinaOfertada VALUES (9,9,2016,'1');
INSERT INTO DisciplinaOfertada VALUES (10,10,2015,'2');

--PROFESSOR
INSERT INTO Professor VALUES (1,11001, 'Avi�o','Manuela Avila', 'avila@hotmail.com', '11988556633');
INSERT INTO Professor VALUES (2,11002, 'Rio', 'Marcelo Nilo', 'nilo@hotmail.com', '11988545265');
INSERT INTO Professor VALUES (3,11003, 'Candombl�', 'Edvaldo Brito', 'brito@hotmail.com', '11998555123');
INSERT INTO Professor VALUES (4,11004, 'Comuna', 'Daniel Almeida', 'almeida@gmail.com', '11965878723');
INSERT INTO Professor VALUES (5,11005, 'Goleiro', 'Paulo Magalh�es', 'magalhaes@hotmail.com', '11952456634');
INSERT INTO Professor VALUES (6,11006, 'Bruto', 'Raul Jungmann', 'jungmann@ig.com.br', '11954879644');
INSERT INTO Professor VALUES (7,11007, 'Neto', 'Geraldo J�lio', 'julio@gmail.com', '11978542118');
INSERT INTO Professor VALUES (8,11008, 'Cacique', 'Etore Labanca', 'labanca@hotmail.com', '11999878245');
INSERT INTO Professor VALUES (9,11009, 'Colorido', 'Fabio Branco', 'branco@ig.com.br', '11945444218');
INSERT INTO Professor VALUES (10,11010, 'Roberval', 'M�rio Kertesz', 'kertesz@hotmail.com', '11948785222');

--TURMA
INSERT INTO Turma VALUES (1,1,'Manh�',1, 1);
INSERT INTO Turma VALUES (2,2,'Tarde',2, 1);
INSERT INTO Turma VALUES (3,3,'Noite',3, 8);
INSERT INTO Turma VALUES (4,4,'Manh�',4, 7);
INSERT INTO Turma VALUES (5,5,'Noite',5, 6);
INSERT INTO Turma VALUES (6,6,'Noite',6, 2);
INSERT INTO Turma VALUES (7,7,'Noite',7, 2);
INSERT INTO Turma VALUES (8,8,'Manh�',8, 1);
INSERT INTO Turma VALUES (9,9,'Tarde',9, 5);
INSERT INTO Turma VALUES (10,10,'Manh�',10, 10);

--CURSOTURMA
INSERT INTO CursoTurma VALUES (1,1,7);
INSERT INTO CursoTurma VALUES (2,2,8);
INSERT INTO CursoTurma VALUES (3,3,7);
INSERT INTO CursoTurma VALUES (4,4,10);
INSERT INTO CursoTurma VALUES (5,5,9);
INSERT INTO CursoTurma VALUES (6,1,3);
INSERT INTO CursoTurma VALUES (7,1,4);
INSERT INTO CursoTurma VALUES (8,1,6);
INSERT INTO CursoTurma VALUES (9,4,1);
INSERT INTO CursoTurma VALUES (10,5,7);

--MATRICULA
INSERT INTO Matricula VALUES (1,1,1);
INSERT INTO Matricula VALUES (2,2,1);
INSERT INTO Matricula VALUES (3,3,1);
INSERT INTO Matricula VALUES (4,4,1);
INSERT INTO Matricula VALUES (5,5,1);
INSERT INTO Matricula VALUES (6,6,1);
INSERT INTO Matricula VALUES (7,7,1);
INSERT INTO Matricula VALUES (8,8,2);
INSERT INTO Matricula VALUES (9,9,2);
INSERT INTO Matricula VALUES (10,10,2);