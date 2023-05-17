
                                         Résumé
Les intervalles de confiance pour les proportions sont couramment utilisés dans de nombreux
domaines, tels que la santé publique, la recherche marketing, la sociologie et la politique, pour
évaluer les taux de réussite, les préférences des consommateurs, les opinions publiques et les
résultats des élections. Ils peuvent également être utilisés pour comparer les proportions entre
différents groupes ou pour évaluer les changements dans les proportions au fil du temps.
En somme, l’intervalle de confiance d’une proportion est une mesure clé pour comprendre
l’incertitude associée à l’estimation de la proportion. Il est essentiel pour la prise de décision
et pour évaluer la fiabilité des résultats obtenus à partir d’un échantillon. Beaucoup sont les
chercheurs qui ont passé du temps à l’étude de l’intervalle de confiance d’une proportion. On
se limite à quatre fameux méthodes, nous les avons étudié avec soin et voici les résultats qu’on
a trouvé :

                                        1. Méthode de Wald : 
Cette méthode approxime la loi binomiale à la loi normale via le
TCL auto-normalisé. Elle utilise l’estimation de la proportion p pour calculer l’intervalle
de confiance. Cependant, cette méthode peut donner des intervalles de confiance qui ne
recouvrent pas la vraie proportion avec une probabilité inférieure au niveau nominal.

                                        2. Méthode de Wilson : 
Cette méthode part sur l’idée de WALD en corrigeant le centrage
de l’intervalle. Elle utilise également une correction pour éviter les intervalles de confiance
qui dépassent les limites de [0,1]. Cette méthode donne généralement de bons résultats, avec
des probabilités de recouvrement qui fluctuent tout au tour du niveau nominal.

                                        3. Méthode d’Agresti-Coull : 
Cette méthode est une amélioration de la méthode de Wilson.
Elle ajoute un nombre fixe de succès et d’échecs artificiels à l’échantillon pour augmenter la
précision de l’estimation de la proportion. Cette méthode peut donner des résultats similaires
à la méthode de Wilson, mais elle présenter des oscillations plus fortes dans les probabilités
de recouvrement qui beaucoup sont au dessus du niveau nominal.

                                         4. Méthode de Clopper-Pearson : 
Cette méthode utilise la distribution exacte de la loi
de probabilité binomiale via la loi bêta pour calculer l’intervalle de confiance. Elle garantit
que la vraie proportion est incluse dans l’intervalle de confiance avec une probabilité de
couverture égale ou supérieure au niveau nominal. Cependant, cette méthode peut donner
des intervalles de confiance plus larges que les autres méthodes.

                                          A retenir:
l est important de noter que le choix de la méthode d’intervalle de confiance dépend de la
situation particulière et des objectifs de l’analyse. Nous verrons ainsi que le choix de la taille
de l’échantillon à un impact sur les résultats, plus la taille de l’échantillon est grande plus
l’intervalle de confiance est précis. Nous verrons la partie 2.2.7 qui éclaircie une comparaison
simultanée des différentes méthodes avec quelques tailles d’échantillons qui varient.
