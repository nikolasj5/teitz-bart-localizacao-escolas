# teitz-bart-localizacao-escolas
Código com a implementação da heurística Teitz e Bart no trabalho: Localização de escolas para oferta de educação em tempo integral: uma aplicação do modelo das p-medianas com uso de ferramentas de GIS.

## Desenvolvido por:
Candace Quezia Andrade Vasconcelos 
Nikolas Jonathan Makiya Vichi

Alunos de mestrado no Programa de Pós-Graduação em Pesquisa Operacional oferecido em associação da Universidade Federal de São Paulo (UNIFESP) e o Instituto Tecnológico de Aeronáutica (ITA).

## Apresentado em:
1. Projeto da disciplina PO-201 (Introdução à Pesquisa Operacional) lecionado pelo Prof. Edson Senne no 1º semestre de 2023.
2. Pôster aprovado no LV Simpósio Brasileiro de Pesquisa Operacional.

## Resumo:
A implementação da oferta de educação em tempo integral nas escolas públicas é um dos principais objetivos do Plano Nacional de Educação, que tem como meta disponibilizar essa modalidade de ensino em, pelo menos, 50% das escolas públicas e atender, no mínimo, 25% dos alunos da educação básica. Para que essa meta seja alcançada com sucesso, é imprescindível a disponibilidade de uma infraestrutura adequada, que proporcione uma educação de qualidade. Assim, o presente trabalho tem como objetivo definir a alocação de escolas públicas em São José dos Campos para oferecer educação em tempo integral no ensino fundamental, utilizando o modelo das p-medianas capacitado (PMC). O PMC é um problema NP-dificil, mas algoritmos exatos e heuristicos podem ser usados para resolvê-lo em tempo satisfatório. O problema foi resolvido por meio da programação matemática e da Heurística de Teitz e Bart, para avaliar o desempenho na busca da solução ótima. Também foi realizada uma simulação com pontos artificiais, em maior instância, para comparar a diferença de desempenho. Como esperado, o resultado exato teve melhor desempenho, com relação à função-objetivo, mas maior custo em tempo para instâncias menores; contudo, diferente do previsto, a heurística teve um desempenho ruim em termos de tempo de execução para a instância superior. O emprego de ferramentas de GIS auxiliou na obtenção da demanda de cada nó, utilizando dados do censo IBGE e do repositório de educação da Fundação Seade, com pré-processamento necessário. Foi possível, ainda, uma melhor análise dos resultados por meio da visualização espacial.