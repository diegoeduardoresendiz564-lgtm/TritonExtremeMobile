# TritonExtremeMobile — prototipo inicial

Proyecto Android nativo en Kotlin para comenzar el desarrollo de un sintetizador móvil inspirado en el Korg Triton Extreme de 61 teclas.

## Estado actual
- Interfaz de prueba en orientación horizontal.
- Teclado táctil de 24 teclas visibles.
- Generador de tono sinusoidal para probar la respuesta táctil.

## Importante
Este prototipo **no** contiene muestras PCM del Korg Triton Extreme, no reproduce todavía sus sonidos originales y aún no implementa MIDI. La interfaz tampoco es una reproducción exacta del panel físico. Es una base técnica para continuar el desarrollo.

## Compilar
Requiere JDK 17 y Gradle 8.9:
`gradle assembleDebug`

El APK de depuración se genera en `app/build/outputs/apk/debug/app-debug.apk`.

## GitHub Actions
El flujo de trabajo incluido compila el APK automáticamente al subir cambios a la rama principal.
