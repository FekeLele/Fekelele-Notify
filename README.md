##  FEKELELE NOTIFY

---

###  Required Dependencies

* `es_extended`

---

\:wrench: **For support or information, open a ticket  Discord  https://discord.gg/VnANeHYP

---

**Development Team**

*  Front-end (CSS/HTML) → *Mr.Psycho*
*  Back-end (Lua/JS) → *Fekelele*

---

### Usage examples with exports

```lua
exports['Fekelele_Notify']:notify("Notification test", "info", 5000)
exports['Fekelele_Notify']:notify("Notification test", "error", 5000)
exports['Fekelele_Notify']:notify("Notification test", "success", 5000)
```

---

### Example integration with es\_extended (client/functions.lua line 60)

```lua
function ESX.ShowNotification(message, type, title, length)
    TriggerEvent('Fekelele_notify:showw', message, type or 'info', length or 5000)
end

```

