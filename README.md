## Programa de Mentoria Entre Alunos DSA – Turma 2 - Temporada 2021
Repositório direcionado para o programa de mentoria da Data Science Academy
### Grupo:
- Fábio Célio Carneiro da Silva Borges (Mentor)
- André Forte Sepúlveda (Membro)
- Carlos Alberto Merlo (Membro)
- Joäo Paulo Braum (Membro)

# Sistema de Recomendação para o cidadão e empresas às melhores formas de acesso à justiça

### Problema a ser Resolvido
Recomendações úteis sobre o acesso a seus direitos, com informações qualificadas, direcionamento para melhores práticas, ou seja, oferecendo possíveis soluções preliminaries, conforme o cidadão questiona seus direitos.

### Definição do Problema:
A automação das tarefas linguísticas dentro do contexto jurídico brasileiro pode diminuir os problemas de acesso a justiça. Nesse sentido, já existem dois precedentes consultados, a geração de ontologias legais (V Richard Benjamins, 2005), e as aplicações de processamento linguístico (Enrico Francesconi, et al,2010).

Para o melhor entendimento do problema de negócio e aprofundamento na definição deste, extraímos dados dos fóruns utilizando um script para webscrapping: 
- https://forumjuridico.org/
- https://www.perguntedireito.com.br/
- https://jus.com.br/duvidas/


### Pré-processamento:
#### Foram executadas as tarefas seguintes:
<ol>
<li>Remoção de dados indesejados</li>
<li>Ajuste de capitalização</li>
<li>Lematização e Stemização</li>
<li>Remoção de Stop-Words</li>
<li>Filtragem de textos</li>
<li>Geração de representações</li>
</ol>


(continua)


### Referências Consultadas:

Enrico Francesconi, Simonetta Montemagni, Wim Peters e Daniela Tiscornia. Semantic processing of legal texts: Where the language of law meets the law of language. Vol. 6036. Springer, 2010.

Felipe Ribas Serras. Algoritmos baseados em atenção neural para a automação da classificação multirrótulo de acórdãos jurídicos. Instituto de Matemática e Estatística da Universidade de São Paulo, 2021.

V Richard Benjamins, Pompeu Casanovas, Joost Breuker e Aldo Gangemi. Law and the semantic web: legal ontologies, methodologies, legal information retrieval, and applications. Vol. 3369. Springer, 2005.
