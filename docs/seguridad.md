# Políticas de Seguridad de la Aplicación Móvil

## 1. Almacenamiento Local Seguro
Los tokens de sesión no se guardan en texto plano; se utiliza el almacenamiento seguro del dispositivo (*EncryptedSharedPreferences* / *Keychain*).

## 2. Permisos del Dispositivo
La aplicación únicamente solicita permisos estrictamente necesarios en tiempo de ejecución (*Runtime Permissions*).