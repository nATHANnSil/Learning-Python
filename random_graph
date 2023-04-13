import random

# Gerar um grafo aleatório com 100 arestas e o maior número possível de vértices
num_arestas = 100
arestas = set()
while len(arestas) < num_arestas:
    # Gerar uma nova aresta aleatória (n², nesse caso, 100²)
    u = random.randint(1, 1000)
    v = random.randint(1, 1000)
    # Garantir que a aresta não se conecta a um vértice a si mesmo
    if u != v:
        arestas.add((u, v))

# Imprimir o grafo gerado
print("Grafo gerado com", len(arestas), "arestas e com o maior número possível de vértices:")
for u, v in arestas:
    print(u, v) 
