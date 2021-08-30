---
description: En este apartado te mostraremos toda la configuración del comando ban.
---

# Ban

## Mensaje personalizado

Tolva tiene la capacidad de personalizar el mensaje a la hora de prohibir a un usuario del servidor. Para complementar lo anterior, el bot tiene una lista de variables para poder mostrar información que puede ser de interés en el mensaje. 

### Mensaje de confirmación

```javascript
t!setbanreply confirm [Mensaje]
```

![](../../.gitbook/assets/image%20%2813%29.png)

### Mensaje privado

```javascript
t!setbanreply userdm [Mensaje]
```

![](../../.gitbook/assets/image%20%2818%29.png)

{% hint style="success" %}
**Variables:** 

* **Variables de usuario:** 
  * {user} - Mención al usuario sancionado. \(Ej: @Pizza\) 
  * {usertag} - Tag del usuario sancionado. \(Ej: Pizza\#7625\)
  * {username} - Nombre del usuario sancionado. \(Ej: Pizza\)
  * {userid} - ID del usuario sancionado. \(Ej: 550711245225984022\)
* **Variables de moderador:**
  * {moderator} - Mención al moderador causante de la acción. \(Ej: @MarcosYoshi\)
  * {moderatortag} - Tag del moderador causante de la acción. \(Ej: MarcosYoshi\#0001\)
  * {moderatorname} - Nombre del moderador causante de la acción. \(Ej: MarcosYoshi\)
  * {moderatorid} - ID del moderador causante de la acción. \(Ej: 527057273219186698\)
* {reason} - La razón adjuntada a la acción. \(Ej: Romper los términos y condiciones\)
* {server} - El nombre del servidor donde se ha tomado la acción. \(Ej: TolvaCity\)
{% endhint %}

