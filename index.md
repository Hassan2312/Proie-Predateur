![Image](https://images.radio-canada.ca/q_auto,w_1250/v1/ici-info/16x9/yukon-lynx-lievre.jpg)

# Dynamique Lynx-Lièvre


### Semaine 1
25 mars 2021

Pourquoi les proies ne disparaissent pas?

Quel est ce jeu de taux de croissance et de mortalité qui permet aux populations de proies et leurs prédateurs de demeurer inchangés?

C'est avec ces idées en tête qu'on a commencé à chercher les méthodes utilisées pour modéliser le phénomène de prédation. Et sur Wikipedia on a découvert les fameuses équations de [Lotka-Volterra](https://fr.wikipedia.org/wiki/%C3%89quations_de_pr%C3%A9dation_de_Lotka-Volterra). C'est un couple d'équations différentielles qui prennent chacune en compte l'autre. C'est ce qui permet aux deux mondes d'évoluer interchangeablement, l'un en fonction de l'autre. Dont la forme la plus générale:

![Image](https://wikimedia.org/api/rest_v1/media/math/render/svg/022e443557bb93a3a04b3bac125daeddbeba5def)


Ensuite il nous fallait trouver un moyen pour convertir ces équations différentielles en code Python. Pour cela on a commencé à regarder des sites pour chercher une piste mais il y en avait plusieurs. Certains proposaient des fonctions déjà préparées par Matplotlib et NumPy mais dont la manipulation était trop à l'aise avec. On a décidé alors de partir avec la méthode la plus basique qui serait de calculer des différences (pour la dérivation). Mais on a decidee laisser ça pour la prochaine fois et déjà finir le carnet de bord.


### Semaine 2
8 avril 2021
