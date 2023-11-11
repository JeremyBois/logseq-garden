- tags::
  link::
  [[Nov 7th, 2023]]
  ***
- # Normes et standards
	- Gérés en partie par l'association [IPC - Institute of Printed Circuits](https://www.ipc.org/)
		- Permet d'avoir un ensemble de règles en communs pour les différents fabricants de PCB
		- Permet un partage des bonnes pratiques
	- **Utiliser des bords arrondis pour les pads**
		- Évite des problèmes de tolérance lors de la gravure (plus adapté au processus de fabrication)
		- Évite à la pâte à souder de rester coincé dans le *stencil*
		- Meilleur support pour la soudure sans plomb
		- Gain de place + meilleur alignement des composants
		- Bonnes pratiques:
			- Rayon ~25% de la longueur du plus petit coté
			- Rayon maximum de 10mil (0.254mm)
	- Paires différentielles (USB D+/D-, ...)
		- Espacement de ~5 fois la largeur des traces avec les autres traces
		- Éviter une courbure de plus de 135° (formation d'une forme de U)
		- Éviter de s'approcher / couper des lignes à haute fréquences (horloge)
		- Assurer un angle de 90° avec les autres lignes si un croissement est nécessaire
		- Contrôler
			- que l'impédance est adaptée au signal
			- que la longueur des traces est
	-
- # Astuces
	- [Prévoir des connections cassables](https://wiki.ai03.com/books/pcb-design/page/breakaway-tabs)
	-
	-