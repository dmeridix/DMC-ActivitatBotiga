# DMC-ActivitatBotiga

Generar un controlador REST a partir del controlador actual de l’aplicació web, afegint algunes noves funcionalitats.
Canviar l’ús de les entitats al controlador per DTO’s i mapejos fent servir MapStruct.
Provar l’API amb swagger.


1 REST API
Controllers
12 Endpoints

1 DTOS MAPPERS
dependencies
properties
entitats - JPA
- Categoria
	Posar camps correctes
- Subcategoria
	Posar camps
	Relacio
		1 to N Categoria - Subcategoria
- Producte
	Afegir Categoria
	Afegir Subcategoria
	Relacions entre Categoria
		N to 1 Producte - Categoria
DTOS
- Camps entitats menys ids i timestamps creacio i actualitzacio
Mapper
- Interficie 
Repository
Services - Opció B
Implementacions
Adaptacio cap a DTO
