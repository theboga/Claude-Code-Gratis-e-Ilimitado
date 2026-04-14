# Claude Code Gratis e Ilimitado
Claude Code Local Gratis Ilimitado con modelos locales con Ollama

# 🚀 Claude Code + Ollama: Guía para Programar Gratis e Ilimitado

### **Edición Apple Silicon M4/M1**

¿Cansado de ver cómo vuela tu saldo de Anthropic? ¿Quieres que tu **Mac
Mini M4** trabaje de verdad mientras tú te tomas un café? Bienvenido al
tutorial donde conectamos la interfaz de **Claude Code** con modelos
locales mediante **Ollama**.

Poder ilimitado, privacidad total y \$0 en la factura. ¡Vamos a ello!

## 🧐 ¿Por qué hacer esto? (El Factor "Ninja")

Claude Code es un agente de terminal increíble, pero suele pedir permiso
a la nube de Anthropic. Al usarlo con **Ollama** y **LiteLLM**, hacemos
un "truquito" maestro: Claude Code cree que habla con la nube, pero en
realidad está susurrándole a un modelo que corre localmente en tu Mac.

### El Ranking de los "Cracks" (Basado en Benchmarks)

Mirando las tablas de rendimiento, estas son tus mejores opciones para
local:

1.  **GLM 5 (96% Score):** 🏆 La bestia absoluta para tareas complejas.

2.  **Qwen 3.5 35b (88% Score):** El Rey para tu **Mac Mini M4 (16GB)**.

3.  **GLM 4.7-flash (82% Score):** Una joya oculta que brilla en
    velocidad.

4.  **Qwen 3.5 9b (80% Score):** La opción equilibrada, perfecta para el
    **M1 (8GB)**.

5.  **Qwen 3.5 2b (65% Score):** Ideal para tareas rápidas sin calentar
    el Mac.


<table>
<tr><th>Family</th><th>Model</th><th>Score</th></tr>
<tr><td><b>Kimi</b></td><td>k2.5</td><td><b>121/125 (97%)</b></td></tr>
<tr><td rowspan="6"><b>Qwen3.5</b></td><td>0.8b</td><td>31/125 (24%)</td></tr>
<tr><td>2b</td><td>81/125 (65%)</td></tr>
<tr><td>4b</td><td>77/125 (62%)</td></tr>
<tr><td>9b</td><td><b>100/125 (80%)</b></td></tr>
<tr><td>35b</td><td><b>111/125 (88%)</b></td></tr>
<tr><td>397b</td><td><b>120/125 (96%)</b></td></tr>
<tr><td rowspan="5"><b>Qwen3</b></td><td>0.6b</td><td>—</td></tr>
<tr><td>1.7b</td><td>42/125 (34%)</td></tr>
<tr><td>4b</td><td><b>94/125 (75%)</b></td></tr>
<tr><td>8b</td><td>85/125 (68%)</td></tr>
<tr><td>30b</td><td><b>103/125 (82%)</b></td></tr>
<tr><td rowspan="2"><b>Gemma4</b></td><td>e4b</td><td>34/125 (27%)</td></tr>
<tr><td>31b</td><td><b>105/125 (84%)</b></td></tr>
<tr><td rowspan="4"><b>Gemma3</b></td><td>1b</td><td>—</td></tr>
<tr><td>4b</td><td>37/125 (30%)</td></tr>
<tr><td>12b</td><td>77/125 (62%)</td></tr>
<tr><td>27b</td><td>73/125 (58%)</td></tr>
<tr><td rowspan="3"><b>Llama</b></td><td>3.2:1b</td><td>—</td></tr>
<tr><td>3.2:3b</td><td>26/125 (20%)</td></tr>
<tr><td>3.1:8b</td><td>60/125 (48%)</td></tr>
<tr><td rowspan="3"><b>Mistral</b></td><td>small3.2</td><td>72/125 (57%)</td></tr>
<tr><td>ministral-3</td><td>51/125 (40%)</td></tr>
<tr><td>large-3</td><td>59/125 (47%)</td></tr>
<tr><td><b>Devstral</b></td><td>2</td><td>60/125 (48%)</td></tr>
<tr><td><b>MiniMax</b></td><td>M2.7</td><td><b>120/125 (96%)</b></td></tr>
<tr><td><b>Phi</b></td><td>phi4</td><td>58/125 (46%)</td></tr>
<tr><td><b>GPT-OSS</b></td><td>20b</td><td>94/125 (75%)</td></tr>
<tr><td rowspan="2"><b>OLMo2</b></td><td>7b</td><td>13/125 (10%)</td></tr>
<tr><td>13b</td><td>47/125 (38%)</td></tr>
<tr><td><b>Cogito</b></td><td>3b</td><td>10/125 (8%)</td></tr>
<tr><td rowspan="2"><b>GLM</b></td><td>4.7-flash</td><td><b>102/125 (82%)</b></td></tr>
<tr><td>5</td><td><b>120/125 (96%)</b></td></tr>
<tr><td><b>Nemotron</b></td><td>3-super</td><td>49/125 (39%)</td></tr>
<tr><td rowspan="3"><b>Gemini</b></td><td>2.5-flash</td><td>—</td></tr>
<tr><td>3.1-flash</td><td>—</td></tr>
<tr><td>3.1-pro</td><td>—</td></tr>
<tr><td rowspan="2"><b>Claude</b></td><td>4.6-sonnet</td><td>—</td></tr>
<tr><td>4.5-haiku</td><td>—</td></tr>
<tr><td><b>GPT</b></td><td>5-mini</td><td>—</td></tr>
<tr><td rowspan="2"><b>DeepSeek</b></td><td>chat</td><td>—</td></tr>
<tr><td>reasoner</td><td>—</td></tr>
</table>


## 🛠 Requisitos Previos

- **Hardware:** Mac Mini M4 (16GB RAM) o MacBook M1 (8GB RAM).

- **Ollama:** El motor que mueve todo. [<u>Descárgalo
  aquí</u>](https://ollama.com/).

- **Node.js:** Necesario para instalar Claude Code.

- **Python:** Necesario para instalar LiteLLM.

## 📋 Cheat Sheet: Comandos de Ollama

Usa estos comandos en tu terminal para gestionar tus modelos:

**Listar modelos:** 

```
ollama list
```

**Descargar un modelo:** 

```
ollama pull qwen2.5-coder:14b
```

**Borrar un modelo:** 

```
ollama rm llama3.1:8b
```

**Probar un modelo:** 

```
ollama run qwen2.5-coder
```

## 1️⃣ Método "El Proxy Clásico" (LiteLLM)

Esta forma engaña a Claude Code para que piense que está hablando con la
API oficial.

### **Paso 1: Instala las herramientas**

```
npm install -g @anthropic-ai/claude-code\
pip install litellm
```

### Paso 2: **Levanta** el puente

Descarga tu modelo y ejecuta el servidor proxy:

```
litellm --model ollama/qwen2.5-coder:14b --proxy_config_path /dev/null
```

### Paso 3: ¡A programar!

En otra terminal, lanza Claude apuntando a tu servidor local:

```
export
ANTHROPIC_BASE_URL="\[http://0.0.0.0:4000\](http://0.0.0.0:4000)"\
export ANTHROPIC_API_KEY="sk-1234"\
claude
```

## 2️⃣ Método "Express" **(Optimizado)**

Este método es más directo y mejora la "memoria" del modelo. (Debes tener instalado Ollama App)

### El Paso Crítico: Configura el Contexto

1.  Abre **Ollama** \> **Settings**.

2.  Busca **Context Length**.

3.  Súbelo a **32k** (o 16k en el M1). Sin esto, Claude olvidará el
    código anterior rápidamente.
    <img width="603" height="452" alt="imagen" src="https://github.com/user-attachments/assets/280b20c8-476b-4e27-8bfc-cae2c92bb71e" />


### Lanzamiento Directo

\# Ejemplo usando el modelo GPT-OSS (75% score)\

```
ollama launch claude --model gpt-oss:20b
```
<img width="1423" height="565" alt="imagen" src="https://github.com/user-attachments/assets/ec2b1df7-d6b1-4c46-a89d-2ab5beaadbba" />



para que te des una idea puedes ver el siguiente tutorial de como hacerlo
https://www.youtube.com/watch?v=AKKx1PoNtnM


## 💡 Consejos para Apple Silicon (M1/M4)

- **Memoria Unificada:** Tus 16GB (M4) o 8GB (M1) son compartidos.
  Cierra Chrome antes de usar modelos pesados (14B o más).

- **El M4 es una bestia:** No tengas miedo de probar el **Qwen 3.5
  35b**, la velocidad de respuesta es espectacular.

- **Alias de Terminal:** Agrega esto a tu .zshrc para no escribir todo
  cada vez:\
  alias claude-local='export
  ANTHROPIC_BASE_URL="\[http://0.0.0.0:4000\](http://0.0.0.0:4000)" &&
  export ANTHROPIC_API_KEY="sk-123" && claude'

## ⚠️ Advertencia

Los modelos locales pueden "alucinar". Si el modelo entra en un bucle,
reinicia la sesión o prueba con uno de mayor puntaje como **GLM 5** o
**Qwen 3.5**.

*Guía optimizada para GitHub - ¡Disfruta de tu IA local!*
