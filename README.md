# bolo-de-chocolate
senha_nova = "mar"
hash_novo = calcula_hash(senha_nova)
dicionario_novo = "abcdefghijklmnopqrstuvwxyzABC123!@#$"
for combinacao in itertools.product(caracteres, repeat=len(senha_nova)):
if calcula_hash(combinacao) == hash_novo:
    print(combinacao)
    break
