## K-Nearest Neighbor (KNN) (k vizinhos mais próximos)
Seu objetivo é após termos os dados classificados(Dados de treino) quando inserimos o dado que queremos saber a qual grupo ele pertence temos que mandar o dado e o k (k significa o número de  vizinhos que o novo dado está mais próximo) ele vai calcular a distância do novo ponto inserido para todos os outros pontos e vai guardar este cálculo após isso ele vai pegar as k menores distancia e vai colocar o dado na classe predominante.Quanto menor o k estamos mais sujeitos a ruídos mas perdemos um pouco da precisão para encontrar um k bom devemos fazer varios teste para ver se o modelo está se comportando melhor ou se o algoritmo está se saindo mal com o k maior.
Para o algoritmo do knn funcionar perfeitamente precisamos normalizar os dados.

Ex:Se  tiver k=3 e as classes da cor vermelha e azul ele ele vai calcular a distância do novo ponto para todos os dados das classes e logo após este cálculo ele vai verificar quais são os 3 dados com a menor distância dele e vai verificar qual tem maior predominância se deste 3 dados forem 2 do vermelho então o novo ponto vai ir para a classe vermelha.

