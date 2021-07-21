
Mentor Fábio Célio Carneiro da Silva Borges
Mmebros:
André Forte Sepúlveda
Carlos Alberto Merlo
Joäo Paulo Braum

Titulo: - Sistema de Recomendação para o cidadão e empresas ás melhores formas de acesso á justiça

Problema a ser Resolvido: – Recomendações úteis sobre o acesso a seus direitos, com informações qualificadas, direcionamento para melhores práticas, ou seja, oferecendo possíveis soluções preliminaries, conforme o cidadão questiona seus direitos.

Definição do Problema:
A automação das tarefas linguísticas dentro do contexto jurídico brasileiro pode diminuir os problemas de acesso a justiça. Nesse sentido, já existem dois precedentes consultados, a geração de ontologias legais (V Richard Benjamins, 2005), e as aplicações de processamento linguístico (Enrico Francesconi, et al,2010).

Para o melhor entednimento do probelma de negócio e aprofundamento na definição deste, extraímos dados dos foruns (direito trabalhista e empresarial): "https://forumjuridico.org/", "https://forumjuridico.org/forums/direito-do-trabalho.17/page-\", "https://www.perguntedireito.com.br\" e "https://www.perguntedireito.com.br/questions/direito-empresarial?start=\".

Foi desenvolvido o script webscraping (Scrapping/Scrapping.ipynb) link:-"https://github.com/AndreSepulveda/mentoriadsa/blob/main/Limpeza/classificador_juridico.ipynb).

Pré-processamento:
Foram executadas as tarefas seguintes:
1 - Remoção de dados indesejados
2 - Ajuste de capitalização
3 - Tokenização
4 - Lematização e Stemização
5 - Remoção de Stop-Words
6 - Filtragem de textos
7 - Geração de representações


(continua)



Referências Consultadas:

Enrico Francesconi, Simonetta Montemagni, Wim Peters e Daniela Tiscornia. Semantic processing of legal texts: Where the language of law meets the law of language. Vol. 6036. Springer, 2010.

Felipe Ribas Serras. Algoritmos baseados em atenção neural para a automação da classificação multirrótulo de acórdãos jurídicos. Instituto de Matemática e Estatística da Universidade de São Paulo, 2021.

V Richard Benjamins, Pompeu Casanovas, Joost Breuker e Aldo Gangemi. Law and the semantic web: legal ontologies, methodologies, legal information retrieval, and applications. Vol. 3369. Springer, 2005.

