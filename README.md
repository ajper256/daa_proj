# Descripción
Exploraremos el problema de packing de texturas: dado un conjunto de imagenes (texturas), cuál es la mejor manera de empaquetarlas todas en una única imagen, o en unas pocas? Decimos "mejor manera" en abstracto porque lo "mejor" depende del contexto. Puede ser, por ejemplo: restringirse a empaquetar en una sola imagen y reducir el area de la misma; o decidir empaquetar en imagenes de tamaño fijo y reducir la cantidad de imagenes usadas; o reducir el tamaño en bytes de la imagen (cuantización de color u otras opciones de compresión sin pérdida); o dado que se conoce qué texturas se usan junto a qué otras, optimizar para aprovechar la caché de la GPU (localidad espacial). 
