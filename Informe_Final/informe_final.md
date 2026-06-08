# INFORME FINAL DE SEGURIDAD

## 1. Introducción

En la presente actividad se aplicaron diferentes mecanismos de seguridad informática utilizando Linux, Git y GitHub. El objetivo fue proteger la información, controlar los cambios realizados en los archivos y garantizar la integridad de las evidencias almacenadas durante el desarrollo de las prácticas.

## 2. Amenazas Identificadas

### 2.1 Acceso no autorizado

Una de las principales amenazas es el acceso de personas no autorizadas a los archivos o repositorios. Esto podría permitir la visualización, copia o modificación de información sensible.

### 2.2 Robo de credenciales

Las credenciales de acceso, como contraseñas o claves SSH, pueden ser robadas mediante ataques o por una mala gestión de la información. Esto permitiría a terceros acceder a sistemas y repositorios.

### 2.3 Modificación de archivos

Los archivos pueden ser alterados de forma accidental o maliciosa, afectando la integridad de la información y generando resultados incorrectos.

### 2.4 Divulgación de información

La publicación accidental de datos sensibles, claves privadas o información confidencial puede generar riesgos de seguridad y pérdida de privacidad.

## 3. Medidas Implementadas

### 3.1 Permisos Linux

Se utilizaron permisos de Linux para controlar el acceso a archivos y directorios, permitiendo que únicamente los usuarios autorizados puedan realizar modificaciones.

### 3.2 ACL (Access Control Lists)

Las listas de control de acceso permiten asignar permisos específicos a diferentes usuarios, proporcionando un control más detallado sobre los recursos del sistema.

### 3.3 Hash SHA-256

Se generaron hashes SHA-256 para verificar la integridad de los archivos. Esto permite detectar cualquier modificación realizada después de la creación del hash original.

### 3.4 Git

Se empleó Git como sistema de control de versiones para registrar cambios, mantener un historial de modificaciones y facilitar la recuperación de versiones anteriores.

### 3.5 GitHub Privado

El repositorio fue configurado como privado para restringir el acceso únicamente a usuarios autorizados y evitar la exposición pública de las evidencias.

### 3.6 SSH

Se generó y configuró una clave SSH para establecer conexiones seguras con GitHub, evitando el uso constante de contraseñas y aumentando la seguridad de la autenticación.

### 3.7 Autenticación de Dos Factores (2FA)

Se habilitó la autenticación de dos factores en GitHub para agregar una capa adicional de seguridad y reducir el riesgo de accesos no autorizados.

## 4. Conclusiones

La implementación de mecanismos de seguridad como permisos Linux, ACL, Git, GitHub privado, SSH, hashes SHA-256 y autenticación de dos factores permitió fortalecer la protección de la información. Estas herramientas ayudan a garantizar la confidencialidad, integridad y disponibilidad de los datos, reduciendo significativamente los riesgos asociados a la gestión de evidencias digitales.

