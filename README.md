# Descargas de Dictalo

Instaladores oficiales de **[Dictalo](https://dictalo.pages.dev)** — dictado por voz para Windows, en español, que funciona sin conexión.

👉 **[Descargar la última versión](https://github.com/stevenpardoo/dictalo-releases/releases/latest)**

Este repositorio contiene únicamente los instaladores y sus checksums. El código fuente no vive aquí.

## Verificar la descarga

Cada versión publica el **SHA-256** del instalador. Para comprobar que el archivo que bajaste es exactamente el que publicamos, abre PowerShell en la carpeta de descargas y corre:

```powershell
Get-FileHash .\Dictalo_0.9.0_x64-setup.exe -Algorithm SHA256
```

El resultado debe coincidir, letra por letra, con el que aparece en las notas de esa versión. Si no coincide, no lo instales.

## Sobre la advertencia de Windows

El instalador todavía **no está firmado con un certificado de código**, así que Windows SmartScreen puede mostrar *"Windows protegió su PC"*. Es una advertencia por falta de firma, no por detección de amenaza.

Para continuar: **Más información → Ejecutar de todas formas**.

Verificar el SHA-256 de arriba es la forma de confirmar que el archivo es legítimo mientras la firma llega.

## Soporte

- Preguntas frecuentes: https://dictalo.pages.dev/faq
- Contacto: https://dictalo.pages.dev/soporte
