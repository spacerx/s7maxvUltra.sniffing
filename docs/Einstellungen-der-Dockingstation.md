**App->Einstellungen->Einstellungen der Dockingstation**

<table><tr>
<td align="center" width="450px">
<img src="https://github.com/spacerx/s7maxvUltra.sniffing/blob/main/screenshots/dock-einstellungen.png" width="300px"/>
</td>
<td valign="top" width="500px">

# [Moppwäsche-Interval](#moppwäsche-interval-1)
# [Moppwäsche-Modus](#moppwäsche-modus-1)
# [Automatische Entleerung](#automatische-entleerung-1)
# [Entleermodus](#entleermodus-1)
# [Automatisch trocknen](#automatisch-trocknen-1)
</td>
</tr></table>

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":435078,\"method\":\"get_wash_towel_mode\",\"params\":{}}"},"t":1691340723}
    dps debug: {"id":435078,"result":{"wash_mode":1}}

    Decoded sniffing message: {"dps":{"101":"{\"id\":435079,\"method\":\"get_smart_wash_params\",\"params\":{}}"},"t":1691340723}
    dps debug: {"id":435079,"result":{"smart_wash":0,"wash_interval":1200}}

    Decoded sniffing message: {"dps":{"101":"{\"id\":435080,\"method\":\"get_dust_collection_mode\",\"params\":[]}"},"t":1691340723}
    dps debug: {"id":435080,"result":{"mode":0}}

    Decoded sniffing message: {"dps":{"101":"{\"id\":435081,\"method\":\"get_dust_collection_switch_status\",\"params\":[]}"},"t":1691340723}
    dps debug: {"id":435081,"result":{"status":1}}

    Decoded sniffing message: {"dps":{"101":"{\"id\":435082,\"method\":\"app_get_dryer_setting\",\"params\":[]}"},"t":1691340723}
    dps debug: {"id":435082,"result":{"status":0,"on":{"cliff_on":1,"cliff_off":1,"count":10,"dry_time":10800},"off":{"cliff_on":2,"cliff_off":1,"count":10}}}

# Moppwäsche-Interval
**App->Einstellungen->Einstellungen der Dockingstation->Moppwäsche-Interval**
<table><tr>
<td align="center" width="450px">
<img src="https://github.com/SpacerX/RoborockApp.Sniffing/blob/main/screenshots/moppwasch-interval.png" width="300px"/>
</td>
<td valign="top" width="500px">

## Per Raum
## Per Zeit
## Waschinterval
<br>

### Objekt: [smart_wash_params](Objekte#smart_wash_params)
</td>
</tr></table>

# Moppwäsche-Modus
**App->Einstellungen->Einstellungen der Dockingstation->Moppwäsche-Modus**
<table><tr>
<td align="center" width="450px">
<img src="https://github.com/SpacerX/RoborockApp.Sniffing/blob/main/screenshots/moppwasch-modus.png" width="300px"/>
</td>
<td valign="top" width="500px">

## Wassersparend
## Mittel
## Intensiv
<br>

### Objekt: [wash_towel_mode]()
</td>
</tr></table>

# Automatische Entleerung

# Entleermodus

# Automatisch trocknen
