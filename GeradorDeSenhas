import random
import string

def generate_password(length):
    """Função que gera uma senha aleatória de comprimento 'length'."""
    letters = string.ascii_letters + string.digits + string.punctuation
    return ''.join(random.choice(letters) for i in range(length))

length = int(input("Digite o comprimento da senha: "))
password = generate_password(length)
print("A senha gerada é:", password)
