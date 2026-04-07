# NoLA Network Automation Hub 🚀

Este repositorio contiene las herramientas de automatización para la gestión de infraestructura Cisco en la región NoLA.

## 🛠 Proyectos Incluidos
1. **Cisco Inventory:** Extracción masiva de Hostname, Modelo y Serial vía Netmiko.
2. **AI MoP Generator:** Generación de Method of Procedures mediante OpenAI para actualizaciones de red.

## 📋 Prerrequisitos
- Python 3.9+
- Bibliotecas: `netmiko`, `pandas`, `openai`, `openpyxl`.
- Acceso SSH a los dispositivos de red.

## 🚀 Estándar de Ejecución
Para mantener la consistencia en NoLA, el flujo de ejecución es:
1. Configurar `config/Lista.xlsx` con los objetivos.
2. Ejecutar el script desde el entorno virtual:
   ```bash
   python src/main.py

