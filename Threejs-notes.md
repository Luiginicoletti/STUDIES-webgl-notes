# Three.js notes

Ao observarmos um objeto 3D, estamos, na realidade, contemplando uma representação visual composta por vários elementos essenciais. Esses elementos, encapsulados em estruturas específicas, trabalham em conjunto para criar a aparência tridimensional que percebemos. Aqui estão os principais componentes desse processo:

Mesh (Malha):

Geometry (Geometria): Define a estrutura básica do objeto, especificando seus vértices (pontos no espaço), arestas (conexões entre vértices) e faces (superfícies).
Material (Material): Determina as propriedades visuais do objeto, incluindo cor, textura, transparência, refletividade e outros atributos visuais.
Material (Material):

Type (Tipo): Classifica o material, podendo ser difuso, especular, emissivo, entre outros.
Color (Cor): Estabelece a cor do objeto.
Texture (Textura): Aplica mapas de textura para detalhes visuais adicionais.
Transparency (Transparência): Controla o nível de transparência do material.
Reflectivity (Refletividade): Indica a capacidade do material de refletir luz.
Normals (Normais): Vetores que orientam a direção da superfície, cruciais para cálculos de iluminação.
Side (Lado): Determina como o material reage à iluminação de diferentes lados (frente ou verso).
Geometry (Geometria):

Vertices (Vértices): Pontos no espaço que compõem a estrutura da malha.
Edges (Arestas): Conexões entre vértices.
Faces (Faces): Polígonos formados pelos vértices, definindo a superfície visível do objeto.
Normals (Normais): Vetores que indicam a orientação da superfície em cada ponto, essenciais para cálculos de iluminação.
UV Coordinates (Coordenadas UV): Mapeamento que permite a aplicação adequada de texturas na malha.
