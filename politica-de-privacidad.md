# Política de Privacidad de FlickMatch

**Última actualización:** [FECHA]

Esta Política de Privacidad explica qué datos recolecta FlickMatch ("la App", "nosotros"), cómo los usamos y qué derechos tenés sobre ellos.

## 1. Qué datos recolectamos

- **Correo electrónico**: si te registrás con correo y contraseña, Apple ID o Google.
- **Identificador de usuario (UID)**: generado por Firebase Authentication para identificar tu cuenta.
- **Datos de uso de la App**: swipes (me gusta/no me gusta) sobre películas y series, matches encontrados, salas creadas o a las que te uniste, cantidad de swipes diarios (para aplicar límites de la versión gratuita).
- **Idioma preferido de tu dispositivo**: para mostrarte el catálogo de películas/series en tu idioma.
- **Estado de suscripción**: si tenés FlickMatch Plus activo o no.

No recolectamos tu nombre real, foto de perfil, ubicación geográfica ni contactos de tu dispositivo.

## 2. Cómo recolectamos estos datos

- A través de **Firebase Authentication** (Google) cuando creás una cuenta o iniciás sesión.
- A través de **Firebase Firestore** (Google), donde se almacenan tus salas, swipes y matches.
- A través de **Firebase Cloud Functions** (Google), que procesan la lógica de matches, límites y eliminación de cuenta.

## 3. Con quién compartimos tus datos (terceros)

- **Google Firebase** (Authentication, Firestore, Cloud Functions, Hosting): actúa como nuestro proveedor de infraestructura y procesamiento de datos.
- **The Movie Database (TMDB)**: usamos su API para obtener información de películas y series. No enviamos tus datos personales (correo, UID) a TMDB; solo se realizan consultas de catálogo (género, idioma, búsqueda de títulos).
- **Sign in with Apple** y **Google Sign-In**: si elegís estos métodos de inicio de sesión, procesan tu autenticación según sus propias políticas de privacidad.
- **Apple App Store**: procesa los pagos de la suscripción FlickMatch Plus. No accedemos a tus datos de pago (tarjeta, facturación); Apple los administra directamente.
- **RevenueCat** (cuando esté integrado): gestiona el estado de tu suscripción.

No vendemos tus datos a terceros ni los usamos con fines publicitarios de terceros.

## 4. Por qué usamos tus datos

- Para permitirte crear y unirte a salas de votación de películas/series.
- Para calcular y mostrar tus matches.
- Para aplicar límites de uso según tu plan (Free o Plus).
- Para mostrarte el catálogo en tu idioma.
- Para procesar tu suscripción, si la tenés.

## 5. Retención de datos

- Los matches "ganadores" de una sala se guardan con una expiración automática de 2 días (borrado automático vía TTL de Firestore).
- Los datos de tu cuenta (correo, UID, historial de swipes/matches) se conservan mientras tu cuenta esté activa.
- Si eliminás tu cuenta desde la sección Perfil, se borran de forma permanente e inmediata: tu documento de usuario, las salas donde participaste, tus matches guardados y tu cuenta de autenticación. Esta acción no se puede deshacer.

## 6. Tus derechos

Podés en cualquier momento:
- **Acceder** a tus datos, contactándonos por correo.
- **Eliminar tu cuenta y tus datos** directamente desde la App (Perfil > Eliminar cuenta).
- **Solicitar corrección** de datos incorrectos, escribiéndonos.

## 7. Menores de edad

FlickMatch no está dirigida a menores de 13 años y no recolectamos intencionalmente datos de menores de esa edad. Si creés que un menor de 13 años nos proporcionó datos personales, contactanos para eliminarlos.

## 8. Seguridad

Usamos Firebase Authentication y reglas de seguridad de Firestore para proteger tus datos. Ningún sistema es 100% seguro, pero tomamos medidas razonables para proteger tu información.

## 9. Cambios a esta Política

Podemos actualizar esta Política ocasionalmente. Te notificaremos cambios significativos mediante la App.

## 10. Contacto

Para consultas sobre privacidad o para ejercer tus derechos, escribinos a: [TU EMAIL DE SOPORTE]
