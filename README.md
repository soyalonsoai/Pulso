<div align="center">

```
██████╗ ██╗   ██╗██╗     ███████╗ ██████╗ 
██╔══██╗██║   ██║██║     ██╔════╝██╔═══██╗
██████╔╝██║   ██║██║     ███████╗██║   ██║
██╔═══╝ ██║   ██║██║     ╚════██║██║   ██║
██║     ╚██████╔╝███████╗███████║╚██████╔╝
╚═╝      ╚═════╝ ╚══════╝╚══════╝ ╚═════╝ 
```

### El Arquitecto — Skill para Claude Code

*Construye productos digitales deterministas y auto-reparables con un solo comando.*

[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet?style=for-the-badge&logo=anthropic)](https://claude.ai/code)
[![Protocolo](https://img.shields.io/badge/Protocolo-P.U.L.S.O-ff6b35?style=for-the-badge)](#-el-protocolo-pulso)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-22c55e?style=for-the-badge)](LICENSE)

</div>

---

## ¿Qué es Pulso?

**Pulso** convierte a Claude Code en un **Arquitecto de software disciplinado**.

En vez de generar código a ciegas, Pulso te guía por un protocolo estructurado de 5 fases — desde la idea hasta el deploy — garantizando que cada producto que construyas sea confiable, documentado y mantenible.

> *"Le pedí a Claude que me hiciera una app, escribió mil líneas de código, y al final no entendía lo que yo quería."*

Con Pulso eso no pasa. **Primero se entiende. Después se construye.**

---

## ⚡ Instalación rápida

1. Descarga el archivo [`pulso.skill`](./pulso.skill)
2. Abre **Claude Code**
3. Ve a **Settings → Skills → Install from file**
4. Selecciona `pulso.skill`

Listo. Ya tienes al Arquitecto disponible.

---

## 🚀 Uso

Actívalo con el comando:

```
/pulso
```

O simplemente dile lo que quieres construir — Claude lo detecta solo:

```
quiero construir una app donde mis clientes vean el estado de sus pedidos
```
```
necesito un dashboard de métricas para mi equipo de ventas
```
```
haz una herramienta que procese mis facturas en PDF y las meta a Google Sheets
```

Claude te hará **una pregunta a la vez** hasta tener todo claro. Sin suposiciones. Sin código que tirar a la basura.

---

## 🏗️ El Protocolo P.U.L.S.O.

Cinco fases. Cero suposiciones.

```
P  →  Planeación    Visión clara antes de escribir una sola línea
U  →  Unión         Verificar que todas las conexiones funcionen
L  →  Lógica        Construcción modular en 3 capas (A.N.T.)
S  →  Superficie    UI/UX profesional y validación con el usuario
O  →  Operación     Deploy limpio + documentación de mantenimiento
```

### Arquitectura A.N.T. — 3 capas

| Capa | Directorio | Responsabilidad |
|------|-----------|----------------|
| **A**rquitectura | `architecture/` | SOPs técnicos en Markdown |
| **N**avegación | *(razonamiento)* | Secuencia de construcción modular |
| **T**ools | `tools/` + `src/` | Código determinista y testeable |

### Estructura de proyecto generada

```
tu-proyecto/
├── claude.md          ← Constitución del Proyecto (esquemas, reglas, arquitectura)
├── .env               ← Credenciales y variables de entorno
├── architecture/      ← SOPs técnicos por módulo
├── src/               ← Código fuente
├── tools/             ← Scripts auxiliares (seeds, migraciones, utilidades)
└── .tmp/              ← Archivos temporales y logs
```

---

## 🛠️ Principios

**Confiabilidad sobre velocidad**
Un producto que siempre funciona vale más que uno que funciona rápido una vez.

**Data-First**
El esquema de datos vive en `claude.md` antes de escribir cualquier componente. Construir sin esquema claro es la causa número uno de rewrites costosos.

**Una pregunta a la vez**
Preguntar todo junto produce respuestas superficiales. Una pregunta a la vez construye un modelo mental compartido — y reduce los rewrites a casi cero.

**Auto-Reparación**
Cuando algo falla: Analizar → Parchear → Probar → Documentar. Sin parches genéricos. Sin adivinar.

---

## 📋 ¿Por qué `claude.md` y no `gemini.md`?

Pulso usa `claude.md` como la **Constitución del Proyecto** — el archivo que define esquemas de datos, reglas de negocio e invariantes arquitectónicos. Es el único archivo que nunca se borra y siempre refleja la realidad del sistema.

---

## 🤝 Contribuir

¿Tienes mejoras al protocolo, nuevos casos de uso o quieres adaptarlo a tu stack?

1. Haz fork del repo
2. Edita `SKILL.md` con tus cambios
3. Abre un Pull Request

---

<div align="center">

Hecho con Claude Code · by **[@soyalonsoai](https://github.com/soyalonsoai)**

</div>
