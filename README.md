
class Chien:
    def __init__(self, nom):
        self.nom = nom

    def jouer_a_la_balle(self):
        return f"{self.nom} joue à la balle avec son maître."

class Maitre:
    def __init__(self, nom):
        self.nom = nom

# Création d'instances
chien = Chien("Rex")
maitre = Maitre("John")

# Le chien joue à la balle avec son maître
resultat = chien.jouer_a_la_balle()

# Affichage du résultat
print(resultat)
