
# Gestión de Conexiones Remote Desktop con SQLite3

Este script permite administrar una base de datos SQLite3 para gestionar conexiones de Remote Desktop (RDP).  

## Funcionalidades
- **Guardar** nuevas conexiones.  
- **Actualizar** registros existentes.  
- **Conectarse** a las sesiones almacenadas.  
- **Eliminar** conexiones de la base de datos.  

## Requisitos
1. Tener Python instalado:  
   ```bash
   sudo apt install python3
   ```
2. Instalar `rdesktop`:  
   ```bash
   sudo apt install rdesktop
   ```

## Cómo usarlo
Ejecuta el script con el siguiente comando:  
```bash
python3 init.py
```