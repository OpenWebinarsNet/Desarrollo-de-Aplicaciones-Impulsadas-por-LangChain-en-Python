## Crear un entorno Anaconda

conda create --name "langchain_course" python=3.9.15

## Instalar librerias

**Nota:** Podriamos haber utilizado un `requirements.txt`, pero queria mostrar especificamente que librerias ibamos a instalar

pip install ipykernel
pip install openai
pip install langchain
pip install tiktoken                          # Para poder contar tokens sin usar un modelo
pip install networkx                          # Para los knowledge graphs de memoria
pip install faiss-cpu                         # Tambien existe la versión "gpu"
pip install wikipedia                         # Para usar la herramienta con LangChain
pip install duckduckgo-search                 # Para usar la herramienta con LangChain
pip install langchain_experimental            # Para usar la herramienta de Shell, la cual se encuentra solo en experimental
pip install numexpr                           # Para poder usar LLMMathChain
pip install torch                             # Para el ejemplo donde diseñamos una herramienta que analiza imagenes
pip install transformers                      # Para el ejemplo donde diseñamos una herramienta que analiza imagenes
pip install pillow                            # Para el ejemplo donde diseñamos una herramienta que analiza imagenes
pip install fitz                              # Para RAG
pip install pymupdf                           # Para RAG 
pip install chromadb                          # Para RAG
pip install sentence_transformers             # Para RAG


## Comentario sobre versiones y Langchain

LangChain está en constante desarrollo asi que existe la posibilidad de que los notebooks dejen de funcionar en un tiempo y que haya que cambiar levemente el código