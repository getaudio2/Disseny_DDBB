# Disseny_DDBB
## Breu descripció
Aquest model relacional funciona amb les següents entitats: **Recinte**, **Grup**, **Carrer**, **Parcel·la** i **Assistent**.
Un recinte pot tenir múltiples concerts on participen múltiples grups de música. Cada grup pot sustituïr un altre grup (però no és obligatori) i un grup pot ser o no ser sustituït per un altre.
Els carrers a la zona d'acampada han de tenir parcel·les que els perteneixen. Cada parcel·la només pertany a un sol carrer.
Un assistent es el responable qui alquila una sola parcel·la. Cada assistent al festival pot accedir a múltiples recintes quan vulgui, així com cada recinte poden accedir múltiples assistents.

![dissenyDDBB](Captura_disseny.png)
