
import random

contador = 0 

entrada = input('Deseja jogar "Guess The Number"? [s]im ou [n]ão: ').lower()

while True:

    if entrada == 's':

        top_of_range = input('Digite o "range" desejado: ')


        if top_of_range.isdigit():
            top_of_range = int(top_of_range)

            if top_of_range <= 0:
                print("Digite um número maior que 0 (ZERO).")
                continue   

        else:
            print('Por favor, digite um NÚMERO inteiro e válido!')
            continue
            
        

        random_number = (random.randrange(0, top_of_range))
        random_number = int(random_number)

        while True:
            guess = input('Escolha um número: ')
            guess = int(guess)


            if guess == random_number:
                contador += 1

                print(f'Parabéns, você ACERTOU!!!! \
            Número de tentativas = {contador}')
                again = input('Deseja jogar novamente com o mesmo "range"? [S]im ou [N]ão: ').lower()

                if again == 's':
                    print(entrada)
                    contador= 0 

                else:
                    break

            elif guess > random_number:
                print('O número escolhido deve ser MENOR ')
                contador += 1

            elif guess < random_number:
                print('O número escolhido deve ser MAIOR ')
                contador += 1

            

    if entrada == 'n':
        print('Até mais :)')
        break     



        

  
    



