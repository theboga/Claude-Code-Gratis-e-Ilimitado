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


<table >
<colgroup>
<col />
<col />
<col />
</colgroup>
<thead>
<tr>
<th><h1 id="family">Family</h1></th>
<th><h1 id="model">Model</h1></th>
<th><h1 id="score">Score</h1></th>
</tr>
<tr>
<th><h1 id="kimi">Kimi</h1></th>
<th><h1 id="k2.5">k2.5</h1></th>
<th><h1 id="section-1">121/125 (97%)</h1></th>
</tr>
<tr>
<th rowspan="6"><h1 id="qwen3.5">Qwen3.5</h1></th>
<th><h1 id="b">0.8b</h1></th>
<th><h1 id="section-2">31/125 (24%)</h1></th>
</tr>
<tr>
<th><h1 id="b-1">2b</h1></th>
<th><h1 id="section-3">81/125 (65%)</h1></th>
</tr>
<tr>
<th><h1 id="b-2">4b</h1></th>
<th><h1 id="section-4">77/125 (62%)</h1></th>
</tr>
<tr>
<th><h1 id="b-3">9b</h1></th>
<th><h1 id="section-5">100/125 (80%)</h1></th>
</tr>
<tr>
<th><h1 id="b-4">35b</h1></th>
<th><h1 id="section-6">111/125 (88%)</h1></th>
</tr>
<tr>
<th><h1 id="b-5">397b</h1></th>
<th><h1 id="section-7">120/125 (96%)</h1></th>
</tr>
<tr>
<th rowspan="5"><h1 id="qwen3">Qwen3</h1></th>
<th><h1 id="b-6">0.6b</h1></th>
<th><h1 id="section-8">—</h1></th>
</tr>
<tr>
<th><h1 id="b-7">1.7b</h1></th>
<th><h1 id="section-9">42/125 (34%)</h1></th>
</tr>
<tr>
<th><h1 id="b-8">4b</h1></th>
<th><h1 id="section-10">94/125 (75%)</h1></th>
</tr>
<tr>
<th><h1 id="b-9">8b</h1></th>
<th><h1 id="section-11">85/125 (68%)</h1></th>
</tr>
<tr>
<th><h1 id="b-10">30b</h1></th>
<th><h1 id="section-12">103/125 (82%)</h1></th>
</tr>
<tr>
<th rowspan="2"><h1 id="gemma4">Gemma4</h1></th>
<th><h1 id="e4b">e4b</h1></th>
<th><h1 id="section-13">34/125 (27%)</h1></th>
</tr>
<tr>
<th><h1 id="b-11">31b</h1></th>
<th><h1 id="section-14">105/125 (84%)</h1></th>
</tr>
<tr>
<th rowspan="4"><h1 id="gemma3">Gemma3</h1></th>
<th><h1 id="b-12">1b</h1></th>
<th><h1 id="section-15">—</h1></th>
</tr>
<tr>
<th><h1 id="b-13">4b</h1></th>
<th><h1 id="section-16">37/125 (30%)</h1></th>
</tr>
<tr>
<th><h1 id="b-14">12b</h1></th>
<th><h1 id="section-17">77/125 (62%)</h1></th>
</tr>
<tr>
<th><h1 id="b-15">27b</h1></th>
<th><h1 id="section-18">73/125 (58%)</h1></th>
</tr>
<tr>
<th rowspan="3"><h1 id="llama">Llama</h1></th>
<th><h1 id="b-16">3.2:1b</h1></th>
<th><h1 id="section-19">—</h1></th>
</tr>
<tr>
<th><h1 id="b-17">3.2:3b</h1></th>
<th><h1 id="section-20">26/125 (20%)</h1></th>
</tr>
<tr>
<th><h1 id="b-18">3.1:8b</h1></th>
<th><h1 id="section-21">60/125 (48%)</h1></th>
</tr>
<tr>
<th rowspan="3"><h1 id="mistral">Mistral</h1></th>
<th><h1 id="small3.2">small3.2</h1></th>
<th><h1 id="section-22">72/125 (57%)</h1></th>
</tr>
<tr>
<th><h1 id="ministral-3">ministral-3</h1></th>
<th><h1 id="section-23">51/125 (40%)</h1></th>
</tr>
<tr>
<th><h1 id="large-3">large-3</h1></th>
<th><h1 id="section-24">59/125 (47%)</h1></th>
</tr>
<tr>
<th><h1 id="devstral">Devstral</h1></th>
<th><h1 id="section-25">2</h1></th>
<th><h1 id="section-26">60/125 (48%)</h1></th>
</tr>
<tr>
<th><h1 id="minimax">MiniMax</h1></th>
<th><h1 id="m2.7">M2.7</h1></th>
<th><h1 id="section-27">120/125 (96%)</h1></th>
</tr>
<tr>
<th><h1 id="phi">Phi</h1></th>
<th><h1 id="phi4">phi4</h1></th>
<th><h1 id="section-28">58/125 (46%)</h1></th>
</tr>
<tr>
<th><h1 id="gpt-oss">GPT-OSS</h1></th>
<th><h1 id="b-19">20b</h1></th>
<th><h1 id="section-29">94/125 (75%)</h1></th>
</tr>
<tr>
<th rowspan="2"><h1 id="olmo2">OLMo2</h1></th>
<th><h1 id="b-20">7b</h1></th>
<th><h1 id="section-30">13/125 (10%)</h1></th>
</tr>
<tr>
<th><h1 id="b-21">13b</h1></th>
<th><h1 id="section-31">47/125 (38%)</h1></th>
</tr>
<tr>
<th><h1 id="cogito">Cogito</h1></th>
<th><h1 id="b-22">3b</h1></th>
<th><h1 id="section-32">10/125 (8%)</h1></th>
</tr>
<tr>
<th rowspan="2"><h1 id="glm">GLM</h1></th>
<th><h1 id="flash">4.7-flash</h1></th>
<th><h1 id="section-33">102/125 (82%)</h1></th>
</tr>
<tr>
<th><h1 id="section-34">5</h1></th>
<th><h1 id="section-35">120/125 (96%)</h1></th>
</tr>
<tr>
<th><h1 id="nemotron">Nemotron</h1></th>
<th><h1 id="super">3-super</h1></th>
<th><h1 id="section-36">49/125 (39%)</h1></th>
</tr>
<tr>
<th rowspan="3"><h1 id="gemini">Gemini</h1></th>
<th><h1 id="flash-1">2.5-flash</h1></th>
<th><h1 id="section-37">—</h1></th>
</tr>
<tr>
<th><h1 id="flash-2">3.1-flash</h1></th>
<th><h1 id="section-38">—</h1></th>
</tr>
<tr>
<th><h1 id="pro">3.1-pro</h1></th>
<th><h1 id="section-39">—</h1></th>
</tr>
<tr>
<th rowspan="2"><h1 id="claude">Claude</h1></th>
<th><h1 id="sonnet">4.6-sonnet</h1></th>
<th><h1 id="section-40">—</h1></th>
</tr>
<tr>
<th><h1 id="haiku">4.5-haiku</h1></th>
<th><h1 id="section-41">—</h1></th>
</tr>
<tr>
<th><h1 id="gpt">GPT</h1></th>
<th><h1 id="mini">5-mini</h1></th>
<th><h1 id="section-42">—</h1></th>
</tr>
<tr>
<th rowspan="2"><h1 id="deepseek">DeepSeek</h1></th>
<th><h1 id="chat">chat</h1></th>
<th><h1 id="section-43">—</h1></th>
</tr>
<tr>
<th><h1 id="reasoner">reasoner</h1></th>
<th><h1 id="section-44">—</h1></th>
</tr>
</thead>
<tbody>
</tbody>
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
