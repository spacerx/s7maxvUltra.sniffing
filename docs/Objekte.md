<table align="center"><tr><td>

**[a](#A) &nbsp;&nbsp; b &nbsp;&nbsp; c &nbsp;&nbsp; [d](#D) &nbsp;&nbsp; e &nbsp;&nbsp; f &nbsp;&nbsp; g &nbsp;&nbsp; h &nbsp;&nbsp; i &nbsp;&nbsp; j &nbsp;&nbsp; k &nbsp;&nbsp; l &nbsp;&nbsp; m &nbsp;&nbsp; n &nbsp;&nbsp; o &nbsp;&nbsp; p &nbsp;&nbsp; q &nbsp;&nbsp; r &nbsp;&nbsp; [s](#S) &nbsp;&nbsp; t &nbsp;&nbsp; u &nbsp;&nbsp; v &nbsp;&nbsp; [w](#W) &nbsp;&nbsp; x &nbsp;&nbsp; y &nbsp;&nbsp; z**
</td></tr></table>

<a id="A"><!-- ********************************************************************************** -->

<!-- ############################################################################################ -->
# app_get_dryer_setting ???
**Einstellungen->Einstellungen der Dockingstation->???**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440046,\"method\":\"app_get_dryer_setting\",\"params\":[]}"},"t":1693597417}
    dps debug: {"id":440046,"result":{"status":0,"on":{"cliff_on":1,"cliff_off":1,"count":10,"dry_time":10800},"off":{"cliff_on":2,"cliff_off":1,"count":10}}}

**set:**

    Decoded sniffing message: { ???
    dps debug: { ???

**params:**
<table><thead><tr><th colspan=3 align="left">status</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>?</td><td>?</td></td>
</tr></tbody></table><p align="center"><a href="#">>top</a></p>
<hr>

<a id="B"><!-- ********************************************************************************** -->

<a id="C"><!-- ********************************************************************************** -->

<a id="D"><!-- ********************************************************************************** -->

<!-- ############################################################################################ -->
# dust_collection_mode
**Einstellungen->Einstellungen der Dockingstation->Entleerungsmodus**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440044,\"method\":\"get_dust_collection_mode\",\"params\":[]}"},"t":1693597417}
    dps debug: {"id":440044,"result":{"mode":0}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440201,\"method\":\"set_dust_collection_mode\",\"params\":{\"mode\":1}}"},"t":1693597697}
    dps debug: {"id":440201,"result":["ok"]}

**params:**
<table><thead><tr><th colspan=3 align="left">mode</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>Smart</td><td>Wählt den Besten Modus (Automatik)</td></td>
<tr><td align="center">1</td><td>Leicht</td><td>Für saubere oder kleine Wohnung</td>
<tr><td align="center">2</td><td>Mittel</td><td>Für mittlere Wohnung, ausgewogene Geschwindigkeit/Leistung</td>
<tr><td align="center">4</td><td>Max</td><td>Für schmutzige oder große Wohnung</td>
</tr></tbody></table><p align="center"><a href="#">>top</a></p>
<hr>

<!-- ############################################################################################ -->
# dust_collection_switch_status
**Einstellungen->Einstellungen der Dockingstation->Automatische Entleerung**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440189,\"method\":\"get_dust_collection_switch_status\",\"params\":[]}"},"t":1693597677}
    dps debug: {"id":440189,"result":{"status":1}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440167,\"method\":\"set_dust_collection_switch_status\",\"params\":{\"status\":0}}"},"t":1693597637}
    dps debug: {"id":440167,"result":["ok"]}

**params:**
<table><thead><tr><th colspan=3 align="left">status</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>off</td><td>Automatische Entleerung ausgeschalten</td></td>
<tr><td align="center">1</td><td>on</td><td>Automatische Entleerung eingeschalten</td>
</tr></tbody></table><p align="center"><a href="#">>top</a></p>
<hr>

<a id="E"><!-- ********************************************************************************** -->

<a id="F"><!-- ********************************************************************************** -->

<a id="G"><!-- ********************************************************************************** -->

<a id="H"><!-- ********************************************************************************** -->

<a id="I"><!-- ********************************************************************************** -->

<a id="J"><!-- ********************************************************************************** -->

<a id="K"><!-- ********************************************************************************** -->

<a id="L"><!-- ********************************************************************************** -->

<a id="M"><!-- ********************************************************************************** -->

<a id="N"><!-- ********************************************************************************** -->

<a id="O"><!-- ********************************************************************************** -->

<a id="P"><!-- ********************************************************************************** -->

<a id="Q"><!-- ********************************************************************************** -->

<a id="R"><!-- ********************************************************************************** -->

<a id="S"><!-- ********************************************************************************** -->

<!-- ############################################################################################ -->
# smart_wash_params
**Einstellungen->Einstellungen der Dockingstation->Moppwäsche-Interwal**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440058,\"method\":\"get_smart_wash_params\",\"params\":{}}"},"t":1693597437}
    dps debug: {"id":440058,"result":{"smart_wash":0,"wash_interval":1200}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440069,\"method\":\"set_smart_wash_params\",\"params\":{\"smart_wash\":1,\"wash_interval\":1200}}"},"t":1693597456}
    dps debug: {"id":440069,"result":["ok"]}

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
</tr></tbody></table><p align="center"><a href="#">>top</a></p>
<hr>

<a id="T"><!-- ********************************************************************************** -->

<a id="U"><!-- ********************************************************************************** -->

<a id="V"><!-- ********************************************************************************** -->

<a id="W"><!-- ********************************************************************************** -->

<!-- ############################################################################################ -->
# wash_towel_mode
**Einstellungen->Einstellungen der Dockingstation->Moppwäsche-Modus**

**get:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440112,\"method\":\"get_wash_towel_mode\",\"params\":{}}"},"t":1693597537}
    dps debug: {"id":440112,"result":{"wash_mode":1}}

**set:**

    Decoded sniffing message: {"dps":{"101":"{\"id\":440124,\"method\":\"set_wash_towel_mode\",\"params\":{\"wash_mode\":0}}"},"t":1693597557}
    dps debug: {"id":440124,"result":["ok"]}

**params:**
<table><thead><tr><th colspan=3 align="left">wasch_mode</th>
</tr></thead><tbody>
<tr><td align="center">0</td><td>Wassersparend</td><td>Für sauber Umgebung, reduzierter Wasserverbrauch</td></td>
<tr><td align="center">1</td><td>Mittel</td><td>mittlere Reinigungsgeschw. und Leistung</td>
<tr><td align="center">0</td><td>Intensiv</td><td>Für gelegendlich Tiefenreinigung, hoher Wasserverbrauch<b></td>
</tr></tbody></table><p align="center"><a href="#">>top</a></p>
<hr>

<a id="X"><!-- ********************************************************************************** -->

<a id="Y"><!-- ********************************************************************************** -->

<a id="Z"><!-- ********************************************************************************** -->

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
</tr></tbody></table><p align="center"><a href="#">>top</a></p>
<hr>

<!-- Bis hier kopieren -->
