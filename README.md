# DictaClick — dictado por voz en español para Windows

Instaladores oficiales de **[DictaClick](https://dictaclick.com)**, un programa de dictado por voz para Windows 10 y 11: presionas **Ctrl + Espacio**, hablas y el texto aparece donde está el cursor, en cualquier aplicación (Word, Gmail, WhatsApp Web, Outlook, ChatGPT…). La transcripción ocurre **en tu computador**, así que funciona **sin internet** y tu voz no sale del equipo.

👉 **[Descargar DictaClick](https://dictaclick.com/descargar)** · [Última versión en este repositorio](https://github.com/stevenpardoo/dictaclick-releases/releases/latest)

Este repositorio contiene únicamente los instaladores, sus firmas y checksums. El código fuente no vive aquí.

## Qué es DictaClick

- **Dictado local:** el reconocimiento de voz corre en tu computador. Funciona sin conexión.
- **Pensado para español:** reconoce 28 idiomas y detecta solo en cuál hablas.
- **Escribe en cualquier programa** de Windows, no en una ventana aparte.
- **Vocabulario propio:** nombres, marcas y siglas de tu trabajo, escritos tal cual.
- **Precio en pesos colombianos:** $19.900 COP al mes o $199.000 al año, por Mercado Pago (tarjeta, PSE o Efecty), con garantía de 7 días. [Ver planes](https://dictaclick.com/planes).

## Guías

- [Alternativa a Wispr Flow en español para Windows](https://dictaclick.com/alternativa-a-wispr-flow): precio en pesos, uso sin internet y qué opciones hay.
- [DictaClick vs Wispr Flow, Win+H y Dragon](https://dictaclick.com/comparativa)
- [Dictado por voz sin internet](https://dictaclick.com/blog/dictado-por-voz-sin-internet)
- [Cómo escribir con la voz en Windows, en cualquier programa](https://dictaclick.com/blog/como-escribir-con-la-voz-en-windows)
- [Win+H: el dictado que trae Windows, y cuándo no alcanza](https://dictaclick.com/blog/dictado-de-windows-win-h)
- [Cómo dictar en Word, Gmail y WhatsApp Web](https://dictaclick.com/blog/dictar-en-word-gmail-whatsapp)

## Verificar la descarga

Cada versión publica el **SHA-256** del instalador en sus notas. Para comprobar que el archivo que bajaste es exactamente el que publicamos, abre PowerShell en la carpeta de descargas y corre:

```powershell
Get-FileHash .\DictaClick_<versión>_x64-setup.exe -Algorithm SHA256
```

El resultado debe coincidir, letra por letra, con el de las notas de esa versión. Si no coincide, no lo instales.

## Sobre la advertencia de Windows

El instalador `.exe` todavía no tiene un certificado comercial de firma de código, así que Windows SmartScreen puede mostrar *"Windows protegió su PC"*. Es una advertencia por falta de firma, no por detección de amenaza: **Más información → Ejecutar de todas formas**. Verificar el SHA-256 confirma que el archivo es legítimo.

## Soporte

- Preguntas frecuentes: https://dictaclick.com/faq
- Contacto: https://dictaclick.com/soporte · soporte@dictaclick.com
