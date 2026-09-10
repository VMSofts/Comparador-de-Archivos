# SyncCompareFiles

Aplicación de escritorio para Windows que compara y sincroniza archivos y carpetas
verificando su contenido real, no solo su fecha o su tamaño.

---

## Funciones

- **Comparación por hash SHA-256**: dos archivos se consideran iguales solo si su
  contenido es idéntico
- **Sincronización con búferes de hasta 128 MB** para transferencias rápidas
- **Varios pares de rutas** procesados en una misma operación
- **Emparejamiento flexible**: uno a uno, muchos a uno o combinaciones completas
- **Evita la suspensión** del equipo durante operaciones largas
- Configuración guardada entre sesiones

---

## Tecnología

- **C#** con **.NET Framework 4.8**
- Windows Forms

---

## Compilación

Abrir `ComparadorArchivos.csproj` en Visual Studio y compilar en modo `Release`.

---

## Licencia

MIT. Consulta el archivo [LICENSE](LICENSE).

---

Creado por VMSofts
