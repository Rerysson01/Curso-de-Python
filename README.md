# Crie um programa usando o while que pergunte se chegou nova
# mensagem (S ou N) e só pare quando a resposta for "N".

nova_mensagem = 'S'

while True:
    nova_mensagem = input('Chegou nova mensagem? (S/N): ').upper()

    if nova_mensagem == 'S':
        continue
    elif nova_mensagem == 'N':
        break
    else:
        print('Escolha inválida. Digite somente "S" ou "N".')

print('Encerrando programa.')
