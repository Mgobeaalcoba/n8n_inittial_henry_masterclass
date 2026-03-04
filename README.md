# Masterclass: Tu Primer Robot con IA 🤖

## Automatización de Procesos para No-Programadores

¡Bienvenido al repositorio de la Masterclass de AI Automation! Este proyecto contiene el material necesario para construir un flujo de trabajo inteligente que utiliza IA para analizar sentimientos y automatizar respuestas.

## 🚀 Objetivo de la Sesión

Demostrar la potencia de la automatización con IA mediante la construcción en vivo de un flujo de trabajo inteligente, robusto y escalable, eliminando la barrera del código.

## 🛠️ Stack Tecnológico

- **n8n**: Orquestador de la automatización.
- **OpenAI (via OpenRouter)**: Cerebro de IA para análisis de sentimiento.
- **Slack**: Canal de notificaciones inteligentes.
- **Airtable**: Base de datos para registro estructurado.
- **Google Sheets**: Registro de errores y observabilidad.

## 📂 Estructura del Repositorio

- `workflows/`: Contiene el export JSON del flujo de n8n.
- `docs/`: Guía detallada de la masterclass y documentación de apoyo.

## 📋 Requisitos Previos

1. Una cuenta en [n8n](https://n8n.io/) (Cloud o Self-hosted).
2. API Key de [OpenRouter](https://openrouter.ai/) o OpenAI.
3. Workspace de Slack y una Base de Airtable configurada.

## ⚙️ Instalación del Workflow

1. Descarga el archivo `workflows/n8n-automation.json`.
2. En tu n8n, crea un nuevo flujo.
3. Importa el archivo descargado (`Import from File`).
4. Configura tus credenciales en los nodos de Slack, Airtable, OpenRouter y Google Sheets.

## 🛡️ Resiliencia y Manejo de Errores

Este workflow no solo une aplicaciones; incluye un sistema de **Fallback** y **Observabilidad** para asegurar que el proceso sea profesional y robusto ante fallos de la IA.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

---

Creado para la comunidad de Henry por Antigravity AI.
