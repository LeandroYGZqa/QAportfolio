🎯 Objetivos de la Prueba

🟦 Tableros (Boards)

🔹 Creación

- ✅ Verificar que el sistema permita crear tableros con nombres válidos y los registre correctamente.
- ❌ Validar que se bloqueen intentos de creación sin nombre, con exceso de caracteres o sin permisos.
- ⚠️ Confirmar que se respeten los límites de longitud y comportamiento ante nombres duplicados.

🔹 Edición

- ✅ Asegurar que los cambios en nombre y visibilidad se reflejen correctamente en la interfaz.
- ❌ Detectar errores al guardar ediciones con campos vacíos o caracteres no permitidos.
- ⚠️ Evaluar el sistema ante cambios en los extremos de longitud y restricciones de visibilidad.

🔹 Eliminación

- ✅ Comprobar que la eliminación de tableros se realice con confirmación y se refleje en la UI.
- ❌ Validar que se impida eliminar sin permisos o si se cancela la acción.
- ⚠️ Verificar el manejo de tableros ya eliminados en sesiones previas.

🟩 Tarjetas (Cards)

🔹 Creación

- ✅ Confirmar que se puedan crear tarjetas en listas válidas y que aparezcan en el orden correcto.
- ❌ Validar errores al crear sin título, en listas inexistentes o en tableros bloqueados.
- ⚠️ Probar extremos de longitud y comportamiento ante carga masiva de tarjetas.

🔹 Edición

- ✅ Verificar que se puedan editar todos los atributos de la tarjeta y que se guarden correctamente.
- ❌ Detectar errores al guardar con campos vacíos o editar en contextos inválidos.
- ⚠️ Evaluar límites de caracteres y tamaño de archivos adjuntos.

🔹 Eliminación / Archivado

- ✅ Comprobar que se pueda archivar o eliminar tarjetas con confirmación.
- ❌ Validar que se impida eliminar sin permisos o si se cancela la acción.
- ⚠️ Verificar el manejo de tarjetas ya eliminadas en sesiones anteriores.

🧪 Objetivos Transversales

- 🔄 Validar consistencia de datos entre sesiones y dispositivos.
- 👥 Probar comportamiento según tipo de usuario (free, pago, propietario, no propietario).
- 🔐 Verificar restricciones de permisos en cada acción.
- 📊 Evaluar rendimiento en escenarios de carga (stress test).
- 🧼 Confirmar que los mensajes de error y validación sean claros y consistentes.
- 📸 Documentar cada caso con evidencia visual y trazabilidad de IDs