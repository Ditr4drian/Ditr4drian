# README.md — Adrián en Ditra

Hola, soy Adrián.

Si estás leyendo esto, probablemente eres parte del equipo de devs, estás stalkeando mi GitHub, o te mandaron este perfil como evidencia en algún incidente.

Actualmente trabajo en **Ditra**, donde mi rol oficial es algo como:

> Ingeniero de Desarrollo Master

Pero mi rol real cambia dependiendo del día, del error y de quién haya dicho:

> "Es un cambio rápido, no debería romper nada."

---

## 🛠️ Qué hago realmente

| Actividad | Herramienta | Por qué |
|---|---|---|
| Desarrollo paneles | **Laravel** + **Filament** | Para que la información se vea bonita y no como resultado directo de un `SELECT *` |
| Creo módulos de automatización | **Python** | Para automatizar cosas que antes alguien hacía a mano, seguramente con Excel, fe y sufrimiento |
| Mantengo playbooks | **Ansible** | Porque aparentemente decirle a 40 servidores qué hacer uno por uno no era una forma aceptable de vivir |
| Administro automatizaciones | **AWX** | Que es como Ansible, pero con interfaz, historial y más formas de descubrir que algo falló |
| Levanto y mantengo clusters | **Kubernetes** | Porque nada dice "estabilidad emocional" como ver pods reiniciándose a las 9:17 a.m. |
| Reviso de todo | Servidores, logs, configs | Permisos, errores raros y decisiones del pasado que nadie quiere reclamar |

---

## 📅 Mi día promedio

```bash
git pull
composer install
php artisan migrate
ansible-playbook deploy.yml
kubectl get pods
```

Luego pasan una de dos cosas:

| Escenario | Salida | Probabilidad |
|---|---|---|
| El ideal | `Todo salió bien.` | O sea, mentira |
| El real | `ERROR: algo falló, pero el mensaje no ayuda porque sería demasiado fácil.` | Normalmente pasa esto |

---

## 💪 Habilidades principales

| # | Habilidad |
|---|---|
| 1 | Convertir errores ambiguos en errores ligeramente menos ambiguos |
| 2 | Decir "déjame revisar logs" mientras acepto mi destino |
| 3 | Saber cuándo usar `sudo` y cuándo mejor no provocar al servidor |
| 4 | Identificar si algo es bug, feature, configuración, permisos o martes |
| 5 | Hacer commits con nombres serios mientras por dentro estoy diciendo: "por favor jala" |
| 6 | Sobrevivir a YAML, que no es lenguaje de configuración, es un examen psicológico |
| 7 | Ver un `CrashLoopBackOff` y no llorar inmediatamente |

---

## 🧰 Tecnologías con las que convivo

| Categoría | Stack |
|---|---|
| Backend | Laravel, Filament, Python |
| Infraestructura | Ansible, AWX, Kubernetes, Linux |
| Bases de datos | MySQL / PostgreSQL |
| Herramientas | Git, Bash |
| Extras no opcionales | Logs eternos, tickets que empiezan con "solo es revisar" |

---

## 🗣️ Frases que digo demasiado

| Frase | Contexto |
|---|---|
| "Eso está raro." | Diagnóstico inicial |
| "En local sí funciona." | Defensa clásica |
| "¿Quién movió eso?" | Investigación forense |
| "No era permisos... bueno sí era permisos." | Siempre era permisos |
| "Dame chance, voy a revisar el pod." | Kubernetes siendo Kubernetes |
| "El problema no era el código, era la realidad." | Aceptación |
| "Voy a hacer un cambio mínimo." | Palabras famosas antes del desastre |
| **"Ya casi queda."** | ⚠️ La más peligrosa |

---

## 🔥 Mi relación con producción

Producción y yo tenemos una relación basada en respeto, miedo y monitoreo constante.

| Parte | Compromiso |
|---|---|
| Yo | No la molesto |
| Ella | No me tira errores |

Ese es el acuerdo.

A veces producción rompe el acuerdo.

---

## 🧠 Mi filosofía como dev

| Paso | Regla |
|---|---|
| 1 | Si una tarea se repite tres veces, se automatiza |
| 2 | Si una automatización falla, se automatiza el diagnóstico |
| 3 | Si el diagnóstico falla, se culpa al ambiente |
| 4 | Si el ambiente está bien, se revisa el código |
| 5 | Si el código está bien, se revisa otra vez porque claramente no está bien |
| 6 | Si todo parece estar bien y sigue fallando, probablemente es DNS |

También creo que ningún sistema está realmente documentado hasta que alguien nuevo pregunta:

> "¿Y esto por qué se hace así?"

Y todos guardan silencio.

---

## 🙏 Cosas que me mantienen humilde

| Cosa | Nivel de humildad que genera |
|---|---|
| YAML | █████████░ |
| Permisos de Linux | ████████░░ |
| Errores intermitentes | █████████░ |
| Deploys "pequeños" | ████████░░ |
| Dependencias que ayer instalaban | ███████░░░ |
| Certificados vencidos | ████████░░ |
| Kubernetes diciendo `Pending` sin elaborar | ██████████ |
| Un playbook que falla solo en un servidor, pero no en los otros 39 | ██████████ |
| El clásico: "No le movimos nada." | ██████████ |

---

## 📋 En resumen

Soy dev en Ditra.

Desarrollo, automatizo, despliego, arreglo, documento cuando hay tiempo y finjo tranquilidad cuando aparece un error nuevo en producción.

Mi objetivo profesional es simple:

> Que las cosas funcionen, que nadie tenga que hacer procesos manuales horribles y que los servidores dejen de tener personalidad propia.

Si algún día ves un commit mío que dice:

```bash
fix: ajuste menor
```

No preguntes.

Solo acepta que hubo una batalla.