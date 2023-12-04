# Three.js notes

Quando observamos um objeto 3D na verdade estamos vendo

Geometry ( Vertices, Edges, Faces, Normals, UV Coordinates)
Material ( Type, Color, Texture, Transparency, Normals, Side)
Mesh ( Geometry, Material, Position, Rotation, Scale )

Geometry (Geometria): Define a estrutura básica do objeto, especificando seus vértices (pontos no espaço), arestas (conexões entre vértices) e faces (superfícies).

Material (Material): Determina as propriedades visuais do objeto, incluindo cor, textura, transparência, refletividade e outros atributos visuais.

Mesh (Malha): Combina a geometria e o material para criar o objeto tridimensional completo. A malha é a representação final do objeto no espaço 3D, resultante da aplicação da geometria para definir sua estrutura e do material para especificar suas características visuais. Ao unir esses elementos, a malha se torna a entidade visual que pode ser renderizada e exibida em um ambiente gráfico, permitindo a interação e visualização de objetos tridimensionais em aplicações como jogos, simulações ou ambientes de realidade virtual.


Primeiro cubo 3D

const geometry = new THREE.BoxGeometry(1, 1, 1)
const material = new THREE.MeshBasicMaterial({ color: 0x00ff00})
const cuve = new THREE.Mesh(geometry, material)

scene.add(cube)
