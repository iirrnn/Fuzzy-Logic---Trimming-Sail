# Fuzzy Logic - Trimming Sail

En este proyecto, se quiere controlar el trimado de la vela dada la fuerza del viento y el rumbo del velero. 
Las reglas son las siguientes:
- **Si** el rumbo es de *ceñida* con un viento *ligero* **entonces** escota *largada*.
-	**Si** se tiene viento *moderado* o *fuerte* con navegación de *ceñida* **entonces** escota *cazada al máximo*.
-	**Si** la navegación es de *través/largo* y el viento *moderado* **entonces** escota *largada al máximo*.
-	**Si** el viento es *flojo* o *fuerte* con un rumbo de *través/largo* **entonces** escota *largada*.
-	**Si** la navegación es *de popa* con independencia de la fuerza del viento **entonces** escota *cazada*.
