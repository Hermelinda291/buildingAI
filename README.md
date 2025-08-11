# 📊 HabitAI: Analizador de Hábitos con IA

**Final project for the Building AI course**

---

## 📝 Summary
**HabitAI** es una aplicación web que analiza tus hábitos diarios mediante inteligencia artificial y ofrece recomendaciones personalizadas para mejorar tu productividad y bienestar.  
Utiliza *machine learning* para identificar patrones en tus actividades y sugerir optimizaciones basadas en datos reales.

---

## 💡 Background

**Problemas identificados:**
1. Muchas personas luchan por mantener hábitos saludables por falta de retroalimentación objetiva.
2. Las aplicaciones existentes solo registran datos, pero no ofrecen *insights* accionables.
3. El estrés y la baja productividad son problemas frecuentes en entornos laborales modernos.

**Motivación:**  
Mi inspiración proviene de mi propia lucha con la gestión del tiempo como desarrollador.  
Pequeños cambios en los hábitos pueden tener un impacto significativo en la calidad de vida.

---

## 🚀 How is it used?

Los usuarios registran sus actividades diarias (trabajo, ejercicio, ocio) a través de una interfaz sencilla.  
La IA analiza estos datos para:

- 📈 **Identificar patrones** (horas más productivas, distracciones frecuentes).
- 💡 **Generar recomendaciones personalizadas**.
- 🔔 **Alertar sobre posibles mejoras**.

**Ejemplo de interfaz:**

<img src="https://via.placeholder.com/600x400" width="300" alt="Interfaz de HabitAI">

**Ejemplo de código:**
```python
def analyze_habits(user_data):
    # Modelo de IA para detectar patrones
    patterns = detect_patterns(user_data)
    return generate_recommendations(patterns)
