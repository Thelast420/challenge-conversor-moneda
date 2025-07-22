# 💱 Conversor de Monedas

Aplicación de consola en Java que permite convertir montos entre distintas monedas usando datos en tiempo real desde la API de [ExchangeRate API](https://www.exchangerate-api.com/).

## 📌 Funcionalidades

- Convertir entre:
  - Dólar ⇄ Peso Argentino
  - Dólar ⇄ Real Brasileño
  - Dólar ⇄ Peso Colombiano
- Consultar tasas de cambio actualizadas al instante.

## 🚀 Cómo ejecutar

1. Asegúrate de tener Java 17 o superior instalado.
2. Clona o descarga este repositorio.
3. Agrega la dependencia de **Gson** en tu proyecto (si usas un IDE como IntelliJ o Eclipse, o puedes usar Maven/Gradle).
4. Ejecuta la clase `Principal.java`.

## 🔧 Dependencias

- Java 17+
- Librería `Gson` de Google para procesar JSON.

Puedes añadirla con Maven:
```xml
<dependency>
  <groupId>com.google.code.gson</groupId>
  <artifactId>gson</artifactId>
  <version>2.10.1</version>
</dependency>
