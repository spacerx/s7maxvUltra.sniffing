<!-- ############################################################################################ -->
# app_get_dryer_setting ???
**Einstellungen->Einstellungen der Dockingstation->???**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":435082,\"method\":\"app_get_dryer_setting\",\"params\":[]}"},"t":1691340723}
    dps debug: {"id":435082,"result":{"status":0,"on":{"cliff_on":1,"cliff_off":1,"count":10,"dry_time":10800},"off":{"cliff_on":2,"cliff_off":1,"count":10}}}
**set:**

    Decoded sniffing message: { ???
    dps debug: { ???

**params:**
<table><thead><tr><th colspan=3 align="left">status</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>?</td><td>?</td></td>
</tr></tbody></table>
<hr>

<!-- ############################################################################################ -->
# dust_collection_mode
**Einstellungen->Einstellungen der Dockingstation->Entleerungsmodus**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":59163,\"method\":\"get_dust_collection_mode\",\"params\":[]}"},"t":1691351766}
    dps debug: {"id":59163,"result":{"mode":0}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":59178,\"method\":\"set_dust_collection_mode\",\"params\":{\"mode\":1}}"},"t":1691351796}
    dps debug: {"id":59178,"result":["ok"]}

**params:**
<table><thead><tr><th colspan=3 align="left">mode</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>Smart</td><td>Wählt den Besten Modus (Automatik)</td></td>
<tr><td align="center">1</td><td>Leicht</td><td>Für saubere oder kleine Wohnung</td>
<tr><td align="center">2</td><td>Mittel</td><td>Für mittlere Wohnung, ausgewogene Geschwindigkeit/Leistung</td>
<tr><td align="center">4</td><td>Max</td><td>Für schmutzige oder große Wohnung</td>
</tr></tbody></table>
<hr>

<!-- ############################################################################################ -->
# dust_collection_switch_status
**Einstellungen->Einstellungen der Dockingstation->Automatische Entleerung**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":435081,\"method\":\"get_dust_collection_switch_status\",\"params\":[]}"},"t":1691340723}
    dps debug: {"id":435081,"result":{"status":1}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":59145,\"method\":\"set_dust_collection_switch_status\",\"params\":{\"status\":1}}"},"t":1691351735}
    dps debug: {"id":59145,"result":["ok"]}

**params:**
<table><thead><tr><th colspan=3 align="left">status</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>off</td><td>Automatische Entleerung ausgeschalten</td></td>
<tr><td align="center">1</td><td>on</td><td>Automatische Entleerung eingeschalten</td>
</tr></tbody></table>
<hr>

<!-- ############################################################################################ -->
# smart_wash_params
**Einstellungen->Einstellungen der Dockingstation->Moppwäsche-Interwal**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":59046,\"method\":\"get_smart_wash_params\",\"params\":{}}"},"t":1691351553}
    dps debug: {"id":59046,"result":{"smart_wash":0,"wash_interval":1200}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":59062,\"method\":\"set_smart_wash_params\",\"params\":{\"smart_wash\":1,\"wash_interval\":1200}}"},"t":1691351583}
    dps debug: {"id":59062,"result":["ok"]}

**params:**
<table><thead><tr><th colspan=3 align="left">smart_wasch</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>Per Raum</td><td>Organisiert die Moppwäsche nach Räumen um Kreuzkontaminierung zu vermeiden</td></td>
<tr><td align="center">1</td><td>Per Zeit</td><td>Moppwäsche-Interval einstellbar mit param <b>wash_interval<b></td>
</tr></tbody></table>
<br>
<table><thead><tr><th colspan=3 align="left">wash_interval</th>
</tr></thead><tbody>
<tr><td align="center">1200</td><td>in Sekunden</td><td>Zeit zwischen den Moppwäschen</td>
</tr></tbody></table>
<hr>

<!-- ############################################################################################ -->
# wash_towel_mode
**Einstellungen->Einstellungen der Dockingstation->Moppwäsche-Modus**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":435098,\"method\":\"get_wash_towel_mode\",\"params\":{}}"},"t":1691340753}
    dps debug: {"id":435098,"result":{"wash_mode":1}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":435115,\"method\":\"set_wash_towel_mode\",\"params\":{\"wash_mode\":0}}"},"t":1691340782}
    dps debug: {"id":435115,"result":["ok"]}

**params:**
<table><thead><tr><th colspan=3 align="left">wasch_mode</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>Wassersparend</td><td>Für sauber Umgebung, reduzierter Wasserverbrauch</td></td>
<tr><td align="center">1</td><td>Mittel</td><td>mittlere Reinigungsgeschw. und Leistung</td>
<tr><td align="center">0</td><td>Intensiv</td><td>Für gelegendlich Tiefenreinigung, hoher Wasserverbrauch<b></td>
</tr></tbody></table>
<hr>

<!-- TEMPLATE
<!-- ############################################################################################ -->
# template
**Einstellungen->EINSTELLUNG->UNTERPUNKT**

**get:**

    Decoded sniffing message: {
    dps debug: {

**set:**

    Decoded sniffing message: {
    dps debug: {

**params:**
<table><thead><tr><th colspan=3 align="left">PARAMS</th>
</tr></thead><tbody>
<tr><td align="center">WERT</td><td>MENUPUNKT</td><td>BESCHREIBUNG</td></td>
<tr><td align="center">WERT</td><td>MENUPUNKT</td><td>BESCHREIBUNG</td>
<tr><td align="center">WERT</td><td>MENUPUNKT</td><td>BESCHREIBUNG</td>
</tr></tbody></table>
<hr>

<!-- Bis hier kopieren -->
