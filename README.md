## Generování věty náhodného textu
Naprogramujeme funkci, která vrátí větu složenou ze zadaného počtu náhodných slov.
Při řešení využijeme známý princip dekompozice. Nejprve vytvoříme funkci, která zajistí vygenerování slova složeného z náhodného počtu náhodných písmen. Tuto funkci budeme opakovaně volat z funkce pro sestavení věty. 

Hlavičky deklarací funkcí:
function generujSlovo(pocetPismen) : vrátí string
function generujVetu(pocetSlov) : vrátí string

Opakovaným voláním této funkce (např. 10x) dojde k následujícímu konzolovému výstupu:

<img width="474" alt="image" src="https://github.com/user-attachments/assets/c7336274-89d8-43dd-b24f-36690a27a425" />

