# langchain-class

Clase sobre el Framework LangChain

one enjout coding

token medir la entrada palabras caracteres

mas de 3 dimensiones es dificil de ver

word 2 vect

red neutonales 

se genera una nube y a partir de ahí se sacan los emeding 

producto punto con los 

nube - courpus | hija del rey | princesa | unidos porque están relacionados con el contexto

similitud coseno con los vectores 

perdía la memoria que tenía al inicio de la converasacion

es una arquitectura que impl el mecanismo de atencion 

codificador / decodificador

dada una oracion se preguntan entre todas  (permite paralelimos)

en las RNN se hacía de una en euna 

mecanimos dice que palabra tiene mas atención/peso una entre otra 

[La niña]   [niña reina] la 2da tiene mas peso y generaria un vector mas cerca de la otra persona 

sampling genera texto alternativo pero muy parecido y con relación 

GPT Generate Pretraing Transformer

luego

se traslada a un almacen que puede almacenar los ambeding


https://python.langchain.com/docs/modules/data_connection/document_loaders/how_to/pdf

1. stuff
bueno para contexto cortos -> une el contexto con el prompt
8 hojas es poco 

2. refine 
contexto largo 
comprime la informacion y dato especifico no va a poder respoder porque esta comprimido 

3. map reduce
pasa por un filtro y envía la información 
comprime la información --> resume la informacion
genera varios docs y lo concatena al prompt y lo envia al model 
realiza varias peticiones al modelos de Lenguaje para comprimir 
preguntas especificas no puede

4. map re rank
asigna scores 
respuesta con score mas alto es la correcta 

CHROMA
Almacen de vectores

RetrievalQA
Hacer preguntas y obtener las respuestas

tiktoken librería que permite el proceso de tokenizacion es propio de OpenAI

Los modelos usan probabilidad entonces no pueden manejar bien los números 

Pregunta en inglés respuesta en español -> proceso llamado LHF Aprendizaje Reforzado por FeedBack Humano
Learning Human FeedBack 

No toda la información es importante, hay mucha basura (tóxica)

Se utiliza basura con LLM si se entrena con malas palabras responde con lo mismo

LHF lo que hace es generar 4 respuestas y las personas califican estas respuestas y las rankean según sea la más correcta y esa respuesta se usa para entrenar el siguiente modelo 

RLHF
El modelo es un monstruo y se filtran :) para que responda posi 

FASTAPI
Para enviar el PDF, crear el cliente para poder interacturar con ambos servicios

Instalar FastAPI y el motor

Al aplicativo que hicimos la prueba debemos integrar y ponerlo en nuestro aplicativo, subir pdf
Proximo día viernes 



