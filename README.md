# TODO List

## I. Modulateur Σ∆ d’ordre 2, à temps discrets, CIFB
- [ ] Justifier que l’architecture proposée est bien d’ordre 2, à temps discret, de topologie CIFB. Justifier
l’ordre du filtre de décimation.
- [ ] Déterminer les coefficients a1, a2, b1, b2 et g (voir cours).
- [ ] Analyser la code matlab.
- [ ] Interpréter le spectre du signal de sortie du modulateur.
- [ ] Revenir à un modulateur d’ordre 1. Justifier la présence d’harmonique dans le signal de sortie du
modulateur.
- [ ] Modifier l’ordre du filtre de décimation pour un modulateur d’odre 2. Tracer et interpréter le spectre
du signal en sortie du décimateur.
- [ ] (*) Écrire une fonction M atlab permettant de calculer le SNR (en dB et en ENOB) du signal de
sortie du modulateur.
- [ ] (*) Écrire une fonction M atlab permettant de calculer la T HD (en % et en dB).

## II. Modulateur Σ∆ d’ordre 2, à temps continus, CIFB
- [ ] Réaliser et simuler un modulateur Σ∆ équivalent mais avec des intégrateurs temps continus.

## III. Modélisation des intégrateurs temps continus
- [ ] Affiner le modèle du modulateur pour simuler le comportement du modulateur en tenant compte du
caractère non idéal des amplificateurs : Gain statique fini et bande passante finie.
- [ ] A l’aide du modèle, tracer SNR(GBW) et T HD(GBW). Conclure sur le cahier des charges des
AOs.
- [ ] Dé-normaliser le modèle pour tenir compte des alimentations qu’on prendre égale à Vcc = 3.3V /0.
Évaluer le courant de sortie maximal de chaque AO.
- [ ] Implémenter et quantifiez (SNR et/ou T HD) l’impact des autres imperfections des amplificateurs :
saturation*, offset*, bruit**, amplification de mode commun*, slew-rate**. Affiner le cahier des
charges en fonction de vos résultats.
