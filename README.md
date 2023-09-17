#  lab1game
 snek game pt lab1 c++
 Snek creste cand mananca $, joaca se pierde daca colizioneaza snek cu coada sa. Snek se controleaza cu WASD, pentru a iesi din joc se apasa pe X.

1.Setup Function:

Initializeaza variabilele si pozitiile.
Seteaza directia initiala la STOP.
Genereaza pozitia initiala pentru $.

2.Draw Function:

curata consola si afiseaza elementele.
utilizeaza loops pt desenarea peretilor, sneku si $.
formeaza si afiseaza coada snekului.

Input Function:

verifica daca vreo tasta e presata cu _kbhit() si o obtine cu ajutorul _getch().
schimba directia in functie de input (a - left, d - right, w - up, s - down, x - exit).

Logic Function:

Organizeaza logica evenimentelor in joaca, miscarea snekului, cresterea cozii, detectarea coliziunilor.
face asa ca daca snek atinge peretele, snek apare pe partea opusa.

Main Function:

apeleaza Setup() pentru initializarea scenei.
apeleaza Draw(), Input(), Logic() intr-un loop, loop-ul sfarseste cand GameOver = true.

Sleep Function:
intarzie loop-ul cu o cantitate de timp indicata in milisecunde pt a controla viteza jocului.

