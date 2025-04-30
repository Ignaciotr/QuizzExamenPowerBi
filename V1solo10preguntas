#Juego Python: "¿Quién quiere ser experto en Power BI?"

import random  # Para mezclar las preguntas

# Lista de preguntas y respuestas

preguntas = [
    {
        "pregunta": "¿Cuál es el objetivo principal de Power BI?",
        "opciones": {
            "a": "Editar documentos de texto",
            "b": "Crear modelos de aprendizaje automático",
            "c": "Visualizar y analizar datos",
            "d": "Diseñar sitios web"
        },
        "respuesta": "c"
    },
    {
        "pregunta": "¿Qué componente de Power BI se usa para crear informes interactivos?",
        "opciones": {
            "a": "Power BI Desktop",
            "b": "Power BI Gateway",
            "c": "Power Apps",
            "d": "Power Automate"
        },
        "respuesta": "a"
    },
    {
        "pregunta": "¿Qué función DAX se usa para calcular la suma de una columna?",
        "opciones": {
            "a": "COUNT",
            "b": "SUM",
            "c": "AVERAGE",
            "d": "MIN"
        },
        "respuesta": "b"
    },
    {
        "pregunta": "¿Qué tipo de visualización se usa mejor para mostrar una tendencia a lo largo del tiempo?",
        "opciones": {
            "a": "Gráfico de dispersión",
            "b": "Gráfico circular",
            "c": "Tarjeta",
            "d": "Gráfico de líneas"
        },
        "respuesta": "d"
    },
    {
        "pregunta": "¿Qué se requiere para publicar un informe en Power BI Service?",
        "opciones": {
            "a": "Una cuenta de OneDrive",
            "b": "Una cuenta de Microsoft Teams",
            "c": "Una cuenta de Power BI",
            "d": "No se necesita cuenta"
        },
        "respuesta": "c"
    },
    {
        "pregunta": "¿Qué permite hacer Power Query en Power BI?",
        "opciones": {
            "a": "Crear presentaciones",
            "b": "Automatizar flujos de trabajo",
            "c": "Transformar y limpiar datos",
            "d": "Diseñar gráficos 3D"
        },
        "respuesta": "c"
    },
    {
        "pregunta": "¿Qué significa ETL en el contexto de Power BI?",
        "opciones": {
            "a": "Extract, Transform, Load",
            "b": "Export, Transfer, Load",
            "c": "Evaluate, Test, Learn",
            "d": "Enable, Track, Link"
        },
        "respuesta": "a"
    },
    {
        "pregunta": "¿Qué componente permite programar actualizaciones automáticas de datos?",
        "opciones": {
            "a": "Power BI Gateway",
            "b": "Power Apps",
            "c": "PowerShell",
            "d": "Excel Online"
        },
        "respuesta": "a"
    },
    {
        "pregunta": "¿Cuál es una limitación de Power BI Free?",
        "opciones": {
            "a": "No permite crear visualizaciones",
            "b": "No permite importar datos",
            "c": "No permite compartir informes",
            "d": "No permite transformar datos"
        },
        "respuesta": "c"
    },
    {
        "pregunta": "¿Qué relación permite unir tablas en Power BI?",
        "opciones": {
            "a": "Relación de rango",
            "b": "Relación de índice",
            "c": "Relación uno a uno / uno a varios",
            "d": "Relación cruzada"
        },
        "respuesta": "c"
    }
]

# Mezclamos el orden de las preguntas usando random.shuffle
random.shuffle(preguntas)

# Contadores
puntaje = 0
correctas = 0
incorrectas = 0

# Saludo inicial (Utilizo emojis de "emojipedia.org" para una mejor experiencia)
print("✨ Bienvenido a 🎺🎺🎺 '¿Quién quiere ser experto en Power BI?'🏆")


nombre = input("Escribí tu nombre: ").title().strip()
print(f"\nComencemos, {nombre}. Tenés 10 preguntas. ¡Exitos!\n")

# Preguntas una por una:
for i, q in enumerate(preguntas, start=1):
    print(f"🔹 Pregunta {i}: {q['pregunta']}")
    for letra, opcion in q['opciones'].items():
        print(f"   {letra}) {opcion}")

    respuesta = input("Tu respuesta (a/b/c/d): ").lower()

    if respuesta == q['respuesta']:
        puntaje += 10
        correctas += 1
        print("✅ ¡Tu respuesta es CORRECTA!\n")
    else:
        incorrectas += 1
        print(f"❌ Respuesta INCORRECTA. Tomá nota, La respuesta correcta era: {q['respuesta']}) {q['opciones'][q['respuesta']]}\n")

# Resultado final
print("📊 Finalizaste el juego!")
print(f"✔️ Respuestas correctas: {correctas}")
print(f"❌ Respuestas incorrectas: {incorrectas}")
print(f"🏆 Puntaje final: {puntaje}/100")

# Comentario según resultado
if puntaje == 100:
    print("🎉 ¡Perfecto! ¡Sos el verdadero crack de Power BI!")
elif puntaje >= 70:
    print("💪 Muy bien, estás listo para rendir tu certificacion.")
elif puntaje >= 40:
    print("👍 Vas por buen camino, seguí practicando.")
else:
    print("📘 Te falta repasar un poquito más. ¡A seguir!")
