# Arquitectura del Sistema - Aplicación Móvil

## 1. Visión General
La aplicación está desarrollada con React Native utilizando un enfoque de arquitectura cliente-servidor basado en servicios REST API.

## 2. Componentes Clave
* **Capa de Presentación (UI):** Componentes visuales construidos con React Native y React Native Paper (`Card`, `AssetExample`).
* **Capa de Red / Servicios:** Encargada del envío de peticiones HTTP en formato JSON a la API Backend.
* **Servicios Backend:** Servidor API que procesa la lógica de negocio y gestiona la persistencia en la Base de Datos.