# KTimer

**Temporizador de apagado gratuito para Windows: cuando se acaba el tiempo que fijó, apaga el PC o lo pone en suspensión.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · Español · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> Este documento es una traducción. Si hay alguna diferencia, la [versión en coreano](README.ko.md) es la que prevalece.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-2.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/ktimer?lang=es)

![Pantalla de KTimer](images/ktimer-en.webp)

## Descripción general

Quedarse dormido viendo una película, o dejar una descarga o una copia de seguridad larga en marcha mientras se ausenta: a veces solo quiere que el PC se apague solo cuando termine.

Con KTimer, ajuste el tiempo con unos pocos botones y pulse **Ejecutar**. Un reloj de tarjetas cuenta hasta cero y luego el PC se apaga. En lugar de apagarlo, también puede enviarlo a **hibernación o suspensión**.

Justo antes de apagar, KTimer **captura la pantalla y se la muestra la próxima vez que encienda el PC.** Por la mañana verá de un vistazo si la descarga terminó y qué ventanas estaban abiertas.

## Funciones principales

- **Apagado programado** — De 1 minuto a 7 horas; el PC se apaga cuando se acaba el tiempo.
- **Hibernación · Suspensión** — Ponga el PC a dormir en lugar de apagarlo. KTimer elige lo que admita este PC.
- **Ver la última pantalla** — La pantalla justo antes del apagado se guarda y se muestra en el navegador al siguiente inicio.
- **Reloj de tarjetas** — El tiempo restante aparece en grandes tarjetas de horas : minutos : segundos que se leen de un vistazo.
- **Tiempo con botones** — `−5` `−1` `+1` `+5` suman y restan; `5` `10` `30` fijan el valor directamente.
- **Nada que configurar** — Sin ventana de ajustes ni permisos de administrador; un único ejecutable.
- **9 idiomas** — Coreano · inglés · japonés · chino · ruso · italiano · francés · español · árabe. Sigue el idioma de Windows.

## Descarga / Instalación

| Tipo | Enlace |
|---|---|
| Instalador | [Descargar](https://down.kilho.net/ktimer?lang=es) |
| Portable (ZIP) | [Descargar](https://down.kilho.net/ktimer?lang=es&nosetup) |

Con el instalador, KTimer se abre en cuanto termina la instalación y se añade al menú Inicio. Para la versión portable, descomprima el ZIP y ejecute `KTimer.exe`.

## Uso

### Primeros pasos

1. Inicie KTimer. La ventana se abre en el centro de la pantalla con el reloj preparado en **00 : 05 : 00** (5 minutos).
2. Ajuste el tiempo con los botones. Por ejemplo: `30` → 30 minutos; `30` y luego `+5` seis veces → 1 hora.
3. Mire el icono de encendido para ver qué ocurrirá. El **símbolo de encendido** significa apagar; púlselo una vez para cambiar a la **luna** y suspender.
4. Pulse **Ejecutar**. El reloj baja segundo a segundo y los puntos entre los dígitos parpadean para indicar que está contando.
5. Al llegar a cero, el botón cambia a **Apagando…** (o **Hibernando…** / **Suspendiendo…**) y el PC se apaga o se duerme. KTimer se cierra con él.

### Distribución de la pantalla

| Elemento | Qué hace |
|---|---|
| Reloj de tarjetas | Tiempo restante (horas : minutos : segundos). Los puntos parpadean mientras cuenta |
| `−5` `−1` `+1` `+5` | Restan o suman esos minutos |
| `5` `10` `30` | Fijan el tiempo directamente en esos minutos |
| Icono de encendido | Cada clic alterna **Apagar** (símbolo de encendido) ↔ **Suspensión** (luna). Pase el ratón por encima para ver su nombre |
| **Ejecutar** / **Detener** | Iniciar / detener la cuenta atrás |

- Mientras cuenta, los botones de tiempo y el icono de encendido se ocultan y solo queda **Detener**, así el tiempo no cambia por accidente.
- El intervalo es de **1 minuto a 7 horas**. Si intenta bajar o subir más, se queda en el límite.

### Qué hacer cuando…

**Quedarse dormido con una película o música**
Una película suele durar unas 2 horas. Pulse `30`, añada margen con `+5`, pulse **Ejecutar** y a dormir. El PC se apaga más o menos cuando termina.

**Dejar una descarga, copia de seguridad o conversión de vídeo en marcha**
Programe el tiempo que debería tardar la tarea, con un poco de margen (hasta 7 horas). La próxima vez que encienda el PC se abrirá la última pantalla antes del apagado, para comprobar enseguida si la tarea terminó de verdad.

**Ver qué había en pantalla justo antes del apagado**
Cuando KTimer apaga el PC, guarda la pantalla del **monitor donde estaba el ratón**. La próxima vez que encienda el PC e inicie sesión, se abre el navegador predeterminado y muestra esa pantalla. No tiene que hacer nada.
- Con varios monitores, deje el ratón en el monitor con la ventana que quiere comprobar.
- Esto solo ocurre con **Apagar**. Con la suspensión, la pantalla sigue ahí al despertar el PC, así que no hace falta.

**Tiene documentos sin guardar**
Cuando llega la hora, otros programas no pueden retener el apagado: el PC se apaga con seguridad. Nunca se queda toda la noche encendido en un aviso de "¿Guardar cambios?", pero **lo que no esté guardado no se conserva**, así que guarde antes de pulsar Ejecutar.

**Poner el PC a dormir en lugar de apagarlo**
Antes de pulsar Ejecutar, pulse el icono de encendido para cambiarlo a la **luna**. Pase el ratón por encima para ver qué hará realmente este PC.
- **Hibernación** — Guarda las ventanas abiertas y el trabajo y luego apaga. Al volver a encenderlo, todo queda como estaba.
- **Suspensión** — Espera consumiendo muy poca energía. Se despierta rápidamente.
Los PC que admiten hibernación hibernan; los demás se suspenden. KTimer vuelve a comprobarlo justo antes de actuar, así que si cambia la configuración de energía mientras espera, la sigue.

**Cancelar o cambiar la programación**
Pulse **Detener** para pausar la cuenta atrás y recuperar los botones de tiempo. Ajuste el tiempo y pulse **Ejecutar** para volver a contar desde ese tiempo. Para cancelar del todo, basta con cerrar la ventana: al cerrarla se cancela la programación.

**La ventana estorba**
**Minimícela**: sigue contando en segundo plano. Ábrala de nuevo desde la barra de tareas cuando quiera ver el tiempo restante.

**No encuentro la ventana**
Ejecute KTimer otra vez. En lugar de abrir una nueva, la ventana que ya está contando pasa al frente (solo hay una programación a la vez).

**Trucos para ajustar el tiempo rápido**
- Para los habituales 5 · 10 · 30 minutos, pulse ese botón una vez.
- 1 hora es `30` y luego `+5` seis veces; 45 minutos es `30` y luego `+5` tres veces.
- Afine minuto a minuto con `+1` · `−1`. Por mucho que pulse `−1`, nunca baja de 1 minuto.

## Configuración

No hay ventana de ajustes y no se guarda nada. Cada inicio empieza así:

| Elemento | Valor inicial |
|---|---|
| Tiempo | 5 minutos |
| Acción | Apagar |
| Aspecto | Tema oscuro |
| Idioma | Idioma de Windows (inglés si no es compatible) |

## Requisitos

- Windows 10 · Windows 11 (64 bits)
- No requiere permisos de administrador ni runtime adicional para ejecutar el programa.
- La vista de la última pantalla se abre en el navegador predeterminado. La conexión a Internet solo se usa para esa vista y para los avisos de nueva versión.

## Actualizaciones

KTimer **no** se actualiza solo. Al iniciarse comprueba si hay una versión nueva y muestra un aviso; al pulsar **Sí** se abre la página de descarga y el programa se cierra. Las nuevas versiones se publican manualmente tras una verificación interna y se anuncian en la [página de KTimer](https://kilho.net/ktimer). Consulte el [aviso sobre la política de actualizaciones](https://en.kilho.net/archives/notice/2940).

**Historial de versiones**

| Versión | Fecha | Cambios |
|---|---|---|
| 2.0.0 | 2026-09-23 | Renovación completa: diseño de reloj de tarjetas, tiempo ajustable directamente con botones, apagado o suspensión elegidos con un icono, colores y fuente numérica pensados para la interfaz oscura, más ligero y fluido |
| 1.3.2 | 2026-08-21 | Menús y comportamiento adaptados a la compatibilidad con hibernación, mejor cambio a suspensión, mejoras en el inicio automático y en la comprobación de actualizaciones |
| 1.3.1 | 2024-11-16 | Añadidos italiano · francés · ruso · chino |
| 1.3.0 | 2024-11-03 | Compatibilidad con hibernación, impide ejecutarlo dos veces, mejoras multilingües y en los avisos de actualización |

## Licencia

KTimer es **freeware**. Puede usarlo gratis y sin restricciones en cualquier lugar — empresa, casa, organismos públicos, escuela — y redistribuirlo libremente.

## Enlaces

- Sitio web: <https://kilho.net/ktimer>
- Foro: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
