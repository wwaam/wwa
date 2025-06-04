Exercice 2 : Palindrome Récupérer un mot saisi par l'utilisateur. Afficher s'il s’agit d’un palindrome ou non. Aide : • Le mot "radar" est un palindrome, le mot "voiture" ne l'est pas. • La fonction longueur(m) permet de récupérer le nombre de caractère du mot m.

Début
    Lire mot
    mot_inverse <- ""

    Pour i de longueur(mot)-1 à 0 pas -1
        mot_inverse <- mot_inverse + mot[i]
    FinPour

    Si mot = mot_inverse Alors
        Afficher "C'est un palindrome"
    Sinon
        Afficher "Ce n'est pas un palindrome"
    finsi
fin

