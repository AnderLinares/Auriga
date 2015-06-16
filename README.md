## Auriga

    [{
	"$project" : { "Type" : "Local Project",
		"Name" : "Auriga",
		"Description" : "Sistema de Noticias, Eventos y repositorio privado para una sección estudiantil.",
		"From" : { "$django" : { "Version" : "1.8.2"},
				   "$BSP" : {"Version" : "0.1.0"},
				 },
		"Group" : { "G" : "Public", "B" : "Private", "H" : "Deploy"},
		"_id" : 6
	},
    }]

