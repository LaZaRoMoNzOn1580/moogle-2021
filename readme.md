# Moogle-2021 (Rehabilitación 2026)

## Requisitos

- .NET SDK 6.0 o superior
- **ASP.NET Core Runtime 6.0 o superior**
- Carpeta `Content` con tus archivos `.txt`
- Archivo `sinonimos.json` en la raíz del proyecto

## Instalación

- Descarga e instala el SDK y el Runtime desde: [https://dotnet.microsoft.com/download/dotnet](https://dotnet.microsoft.com/download/dotnet)
- Comprueba que tienes ambos con:
  ```bash
  dotnet --list-sdks
  dotnet --list-runtimes
  ```

## Ejecución

```bash
dotnet restore
dotnet build
dotnet run --project MoogleServer
```

Abre tu navegador en [http://localhost:5000](http://localhost:5000) o en la dirección que indique la consola.

### Apagar el servidor

- Si el servidor está en ejecución en la terminal o consola, **presiona Ctrl + C** para finalizarlo.
- Si usas Visual Studio, pulsa **Stop** o **Shift + F5**.

