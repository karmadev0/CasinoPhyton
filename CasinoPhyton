import random

print("===================")

print("= ¡CASINO PHYTON! =")

print("===================\n")

print("version: 1.0.0")

print("""\neste es un proyecto que hize por aburrimiento

y asi desafiarme a mi mismo para ver mi potencial.

cualquier bug o algun tipo de consejo o cosas que quiere que agregue a este programa

puedes colocarmelo en mi github alla en issues, puedes colocar que quieres que coloque

creado con amor por: karmadev0 <3""")

print("\n≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈")

print("""\ntu dinero inicial sera de 1000 dolares, podras conseguir un millon de dolares apostando?, ve tu suerte en este casino imrovisado!!""")

dinero = 1000

print("\nlo primero que ves son varias opciones para poder apostar tu dinero")

while dinero < 1000000 and dinero > 1:

    

    perdistebj = 0

    opcionbj = 0

    dineroap = 0

    ganastebj = 0

    

#aqui inicia todo

    print("\n*************************************")

    print("\nhacia donde quieres ir?")

    regreso = 1

    print("""1. blackjack

2. ver dinero que tienes

3. proximamente mas juegos!""")

    opcion = int(input(">"))

### BLACJACK

    if opcion == 1:

        print("""

bienvenido a blackjack!, aqui podras apostar a base de cartas y todo es cuestion de suerte...

la forma de ganar aqui es que tu oponente pase de 21 cartas, o que tenga mas puntos de cartas que tu oponente!

buena suerte!;

""")

        print("tu dinero actual es:", dinero, "$\n")

        print("cuanto quieres apostar?")

        dineroap = int(input(">"))

        

        cartasbj = 0

        cartasbj = random.randint(7,12)

        cartasbj2 = random.randint(6,12)

        cartasbj2 += random.randint(1,12)

            

        if dineroap > dinero:

            print("\nporfavor has una opcion correcta e reinicie el programa")

            

        else:

            print("tus cartas iniciales son: ", cartasbj)

            print("las cartas de tu oponente son ", cartasbj2)

            print("quieres pedir mas cartas?")

            opcionbj =int(input("si. 1, no. 2 | "))

            # tiempo 1

            if opcionbj == 1 and not cartasbj > 21:

                cartasbj += random.randint(1,12)

                print("\nahora tienes ", cartasbj)

                print("las cartas de tu oponente serian", cartasbj2)

                opcionbj = 0

                print("quieres mas cartas?")

                opcionbj = int(input("si. 1, no. 2 | "))

                #tiempo 2

                if opcionbj == 1 and not cartasbj > 21:

                    cartasbj += random.randint(1,12)

                    print("\nahora tienes ", cartasbj)

                    print("las cartas de tu oponente serian",cartasbj2)

                    opcionbj = 0

                    print("quieres mas cartas?")

                    opcionbj = int(input("si. 1, no. 2 | "))

                    ##tiempo 3

                    if opcionbj == 1 and not cartasbj > 21:

                        print("\nse desactiva blackjack despues por mas de 3 cartas! (talvez lo arregle despues muchos codigos aa)")

                elif cartasbj > 21:

                    perdistebj = 1

            elif opcionbj == 2:

                    print("\ncartas restantes", cartasbj)

            else:

                print("\nquedaste con ", cartasbj, "puntos")

            

        # FINALMENTE SE ARREGLO ESTA MIER

        

        if cartasbj > cartasbj2 or cartasbj2 > 21 and not cartasbj > 21:

           ganastebj = 1

        elif cartasbj < cartasbj2 or cartasbj > 21:

           perdistebj = 1

        

        if perdistebj == 1:

           dinero -= dineroap

           print("\nperdiste dinero por perder!, tu dinero actual es ", dinero, "$!")

        elif ganastebj == 1:

             dinero += dineroap

             print("\nganaste dinero por ganar!, tu dinero actual es ", dinero, "$!")

        # DINERO DISPONIBLE #

    elif opcion == 2:

        print("\nTu dinero disponible es ", dinero, "$!")

    else:

        print("proximamente mas juegos y mas opciones!")

        

print("\n≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈")

   

           # # cuando pierdes todo # #

                     

if dinero < 1:

    print("\nte quedaste sin dinero!, lamentablemente perdiste :c")

    print("reinicie el programa para usar denuevo")

    

          # # cuando superas el millon # #

    

if dinero > 999999:

    print("\neres el rey de las apuestas y conseguiste un millon de dolares!")

    print("ganaste el juego por", dinero, "$!")

    print("muchas gracias por jugar :3, -karmadev0")

    print("\nsi quieres jugar denuevo, reinicie el programa")

    

## SALUDOS!

## un saludo a los consejos de homero y a waifus informaticas! xd
