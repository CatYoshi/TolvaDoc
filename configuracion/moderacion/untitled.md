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

![](../../.gitbook/assets/image%20%2811%29.png)

{% hint style="success" %}
**Variables:** 

* {user} - 
* {usertag} - 
* {userid} - 
* {moderator} - 
* {reason} -
* {server} -
{% endhint %}

{% hint style="info" %}
Si quieres saltar de línea escribe **\n** en el mensaje, como en el segundo ejemplo.
{% endhint %}

Once you're strong enough, save the world:

{% code title="hello.sh" %}
```bash
# Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```
{% endcode %}



