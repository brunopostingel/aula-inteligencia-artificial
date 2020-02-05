# GRAFOS

Resumo sobre grafos

Grafos são compostos por Vértices e Arestas
	Vértices: São representados na forma de um círculo. 

	Arestas:Representadas na forma de setas uni ou multidirecional
			unidirecional (--->)
			multidirecional (<------>)
		Podem também conter ou não um peso, número em cima da Aresta

Nos Grafos temos algumas propriedades, como:
	
	Valência(Grau de um Vértice)
		Representa o número de arestas incidentes no vértice.

	Caminho
		Direção em que se pode ir de um vértice a outro com relação as
		arestas(direção)
		O seu tamanho é dado pelo nº de arestas e seu custo é dado pela
		somatória dos pesos das arestas.
	
	Ciclo
		Um ciclo é um caminho, com pelo menos uma aresta, cujos
		vértices de início e fim são iguais.
	
	Adjacêcia
		Um vértice (A) é ajacente a outro (B) quando existe uma aresta
		direcional de A para B, EX:  A ----> B

Maneiras de Representar um Grafo
	Matriz: *SEMPRE QUADRADAS*
		Linhas e colunas são definidas pelo número de vértices
		Quando não se tem uma aresta entre vértices, utiliza-se um valor numerico que
		não exista naquele Grafo
		EXEMPLO:
			
			| 0 3 8 0 |
			| 0 0 0 4 |
			| 0 0 6 0 |
			| 0 4 0 0 |

	Lista: 
		O vetor tem tamanho igual ao número de vértices
		Cada posição do vetor representa um vértice do grafo e aponta
		para uma lista ligada que representa os vértices adjacêntes
		Cada elemento da lista ligada tem três valores: um indicador
		de vértice, um indicador de valor e um campo “próximo”
		As listas são terminadas com apontadores nulos
