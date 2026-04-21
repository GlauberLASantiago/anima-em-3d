Anima 3D (Voxels e CSV) 🎬

Uma ferramenta educacional interativa baseada na web, desenvolvida para criar, visualizar, animar e exportar modelos 3D de forma simples e intuitiva. Ideal para professores e alunos que desejam explorar conceitos de geometria espacial, matrizes de coordenadas e visualização de dados.

<img width="942" height="648" alt="image" src="https://github.com/user-attachments/assets/6b5eadb4-c9ec-4bbf-b08e-c4078d838a03" />


🚀 Funcionalidades Principais

1. Construção e Voxelização (Modo Criar)

Imagem para 3D (Voxels): Converta qualquer imagem 2D (PNG, JPG) num modelo 3D construído por blocos (voxels), mantendo a forma geométrica e as cores exatas.

Ajuste Fino: Controlos deslizantes para definir a Resolução (quantidade de blocos) e o Limiar Alfa (nível de transparência para ignorar o fundo da imagem).

Agrupamento Automático: Os voxels gerados a partir de imagens são agrupados por predefinição, permitindo mover, girar e escalar a figura inteira de uma só vez (podendo ser desagrupados para edições granulares).

Formas Geométricas: Adição de formas básicas como caixas, esferas, cilindros e cones.

Edição de Propriedades: Alteração de cores e manipulação espacial (Translação, Rotação e Escala) de cada objeto ou grupo.

2. Efeitos e Dinâmica (Modo Animar)

Padrões de Animação Subtis: Aplique efeitos visuais (Onda, Giro, Pulsação, Brilho, Flutuar, Tremor, Hélice, Salto) que dão vida aos objetos sem desfigurar a sua forma original.

Controlos de Animação: Ajuste a velocidade das animações e a rotação automática da câmara.

Teclado Reativo: Com a animação ativa (PLAY), ao premir qualquer tecla, as formas reagem emitindo brilho e dando pequenos saltos, aumentando o engajamento dos alunos.

3. Opções de Exportação Versáteis

Exportar CSV: Guarda a matriz de dados da cena (ID, Rótulo, Posições X/Y/Z, Rotações, Escala e Cor Hexadecimal). Excelente para análise matemática e reutilização noutros softwares educacionais.

Exportar SVG: Cria um ficheiro vetorial 2D (imagem "plana") do ângulo atual da câmara, perfeito para imprimir ou inserir em apresentações de slides (PowerPoint/Keynote).

Exportar Widget HTML (Animado ou Estático): Gera um ficheiro HTML leve, com fundo 100% transparente e sem controlos de edição. Desenhado para ser facilmente incorporado (<iframe>) em plataformas de ensino (Moodle, Canvas, Notion, sites).

🛠️ Tecnologias Utilizadas

HTML5, CSS3 & JavaScript (ES6+): Estrutura, estilo e lógica da aplicação, tudo num único ficheiro, sem dependências de compilação.

Three.js: Biblioteca poderosa para renderização 3D no browser usando WebGL.

SVGRenderer (Three.js addon): Motor utilizado para a captura em formato vetorial.

📖 Como Utilizar

Abra o ficheiro principal (index.html) em qualquer browser moderno (Chrome, Firefox, Edge, Safari).

No painel CRIAR, adicione formas ou carregue uma imagem para gerar um modelo em voxels.

Utilize os botões do topo (Mover, Girar, Escalar) e clique nos objetos na cena para os manipular.

Vá ao separador ANIMAR, escolha um padrão de movimento e clique em PLAY. Ajuste a velocidade conforme desejado.

Utilize os botões de exportação (Topo, lado direito) para guardar o seu trabalho ou preparar o material didático para os alunos.

💡 Casos de Uso na Educação

Matemática/Geometria: Demonstrar coordenadas tridimensionais (X, Y, Z) na prática exportando e editando os dados via CSV.

Artes/Design: Transformar desenhos 2D dos alunos em "Pixel Art 3D" (Voxels) para visualização espacial.

Produção de Conteúdo: Professores podem gerar widgets 3D interativos e sem fundo para ilustrar as suas aulas em páginas web, sem precisarem de conhecimentos complexos de programação ou modelação 3D tradicional.
