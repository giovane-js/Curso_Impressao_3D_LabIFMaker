# Glossário de Termos Técnicos de Impressão 3D

Na impressão 3D, a maior parte dos softwares (como o UltiMaker Cura) e painéis de máquinas utiliza termos em inglês. Guarde esta página como guia de consulta rápida.

| Termo | Tradução / Significado Prático |
| :--- | :--- |
| **ABS** | *Acrilonitrila Butadieno Estireno*. Termoplástico derivado do petróleo, resistente ao calor e a impactos, mas que exige impressora fechada para não empenar. |
| **Anisotropia** | Propriedade de peças FDM terem resistência mecânica diferente conforme a direção da força (são muito mais fortes ao longo das camadas XY do que puxadas no eixo Z). |
| **Bed / Mesa Aquecida** | Plataforma onde a peça é construída. O aquecimento ajuda o plástico a grudar e reduz o choque térmico. |
| **Bowden** | Sistema de extrusão onde o motor que empurra o filamento fica preso na estrutura da impressora, enviando o plástico por um tubo de PTFE até o bico. |
| **Brim** | "Aba" de linhas finas impressas ao redor da base da peça para aumentar a área de contato e evitar que os cantos descolem da mesa. |
| **CAD** | *Computer-Aided Design*. Softwares de desenho técnico 3D usados para criar peças (ex.: SolidWorks, Inventor, Fusion 360, Tinkercad). |
| **Direct Drive** | Sistema de extrusão onde o motor fica montado diretamente em cima do conjunto de aquecimento (*hotend*), oferecendo controle mais preciso de retração. |
| **FDM / FFF** | *Fused Deposition Modeling* (Modelagem por Deposição Fundida). Tecnologia que derrete um fio de plástico (filamento) e deposita camada por camada. |
| **G-Code** | Arquivo de texto com coordenadas e comandos de temperatura/velocidade gerado pelo fatiador. É a "receita" exata que a impressora lê no cartão SD ou pendrive. |
| **Hotend** | Conjunto quente na cabeça de impressão composto por dissipador, garganta (*heatbreak*), bloco aquecedor, termistor e bico (*nozzle*). |
| **Infill** | Preenchimento interno da peça (normalmente de 15% a 20% para protótipos visuais e 40%+ para peças mecânicas). |
| **Layer Height** | Altura de cada camada depositada no eixo Z. Define o equilíbrio entre acabamento visual (camadas finas) e tempo de impressão (camadas grossas). |
| **Nozzle (Bico)** | Ponta metálica por onde o filamento derretido sai. O padrão mais comum é **0,4 mm**; bicos maiores (como **0,8 mm**) imprimem muito mais rápido. |
| **Overhang** | Saliência ou parte da peça que fica "no ar" sem apoio por baixo. Acima de 45° normalmente exige suporte. |
| **PETG** | *Polietileno Tereftalato Glicol*. Filamento intermediário que combina boa resistência mecânica/química com facilidade de impressão (não precisa de câmara fechada). |
| **PLA** | *Ácido Polilático*. Bioplástico derivado de fontes renováveis (como milho). Mais fácil de imprimir, ideal para iniciantes e protótipos dimensionais. |
| **Raft** | Base espessa (uma espécie de "jangada" descartável) impressa abaixo de toda a peça para compensar mesas irregulares ou peças de base muito pequena. |
| **Retraction (Retração)** | Movimento rápido que puxa o filamento de volta para dentro do bico durante deslocamentos sem extrusão, evitando fios soltos. |
| **Set Point** | Conjunto de parâmetros calibrados e validados (temperatura, velocidade, retração) definidos como padrão confiável para uma combinação de máquina + material. |
| **Skirt** | Linha de contorno impressa ao redor da peça **sem tocá-la**, usada apenas para limpar o bico e conferir o nivelamento antes da peça começar. |
| **Slicer (Fatiador)** | Programa (como o UltiMaker Cura) que converte o modelo 3D (`.STL`/`.3MF`) em camadas e gera o código `.gcode`. |
| **STL / 3MF** | Formatos de arquivo de malha 3D gerados por softwares CAD ou baixados da internet para serem abertos no fatiador. |
| **Stringing** | Defeito visual parecido com "teias de aranha" (fios finos de plástico entre duas torres ou paredes da peça), geralmente causado por temperatura alta ou pouca retração. |
| **Warping** | Empenamento ou levantamento das quinas da peça devido à contração desigual do plástico durante o resfriamento. Muito comum no ABS. |

---

[⬅️ Sobre o Curso](01-sobre-o-curso-e-regras.md) | [🏠 Início](../README.md) | [Próximo: Módulo 1 — Manufatura Aditiva e FDM ➡️](../01-nocoes-introdutorias/1.1-manufatura-aditiva-e-fdm.md)
