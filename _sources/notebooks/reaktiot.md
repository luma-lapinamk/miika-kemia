# {index}`Reaktiokinetiikka`
Kinetiikka tutkii kemiallisen reaktion kulkua, reaktiomekanismeja ja reaktionopeuksia. Kemialliset reaktiot ovat tarkalleen ottaen elektronien siirtoreaktioita, joissa lähtöaineiden kemialliset sidokset katkeavat ja syntyy uusia sidoksia.

<p><a href="https://commons.wikimedia.org/wiki/File:Combustion_reaction_of_methane.jpg#/media/File:Combustion_reaction_of_methane.jpg"><img src="https://upload.wikimedia.org/wikipedia/commons/7/7c/Combustion_reaction_of_methane.jpg" alt="Combustion reaction of methane.jpg" height="229" width="512"></a><br>Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=24953730">Link</a></p>

- Lähtöaineiden vahvojen sidosten katkeaminen vaatii aina energiaa. Tämän energian suuruutta kuvastaa reaktion **{index}`aktivoitumisenergia`**, tai **aktivaatiokynnys**. Jotta reaktio saadaan aikaan, kynnys on ylitettävä tuomalla systeemiin lisäenergiaa esimerkiksi tarpeeksi suuren lämpötilan avulla, jotta reagoivat aineet törmäävät toisiinsa riittävän suurella energialla.
- **{index}`Aktivoitu kompleksi`** tarkoittaa välituotetta, joka syntyy yhdisteiden törmättyä ja sidosten rikkouduttua. Tämän jälkeen atomit tai ionit alkavat sitoutua uudella tavalla.
- Kun uusia sidoksia syntyy, vapautuu energiaa.
- Jos vapautunut energia on suurempi, kuin vaadittu energia sidosten katkeamiselle, reaktion sanotaan olevan **{index}`eksoterminen reaktio`**. Yleensä energiaa vapautuu aineiden ympäristöön lämpönä, mutta usein vapautunut energia voidaan havaita myös valona, äänenä ja syntyneiden kaasujen liike-energiana.
- Muussa tapauksessa vapautunut energia jää pienemmäksi kuin aktivoitumisenergia, jolloin reaktio sitoo energiaa ympäristöstään mm. lämpönä tai sähkömagneettisena säteilynä (UV-säteily, näkyvä valo tai infrapunasäteily).
- Reaktiossa vapautunutta tai sitoutunutta energiaa kutsutaan nimellä **{index}`reaktiolämpö`**, $\Delta H$ eli entalpiamuutos.
    - Eksotermiselle reaktiolle $\Delta H < 0$
    - Endotermiselle reaktiolle $\Delta H > 0$
```{figure-md} energiakaaviot
<img src="../images/aktivaatioenergia.jpg" alt="Ekso- ja endotermisen reaktion energiakaaviot." class="bg-primary mb-1" width="1000px" align="center">

Ekso- ja endotermisen reaktion energiakaaviot. Kuvan alkuperäinen tekijä: <a href="https://openstax.org/books/biology/pages/1-introduction" target="_blank">CNX OpenStax</a>, lähde: <a href="https://commons.wikimedia.org/wiki/File:Figure_06_03_03.jpg" target="_blank">Wikipedia</a>
```

## {index}`Entalpia`
Aineen sisältämää kemiallista energiaa sanotaan entalpiaksi. Entalpiaa merkitään tunnuksella *H* ja yksikkönä on joule, *J*. Entalpian suuruutta eli aineen energiasisältöä ei voida mitata mutta sen muutos on mahdollista määrittää joko kokeellisesti tai tunnettujen osareaktioiden avulla. Kokeellisesti reaktiossa vapautuvan tai sitoutuvan lämpöenergian määrä voidaan mitata **kalorimetrisin mittauksin** mittaamalla lämpötilamuutoksia eristetyssä, suljetussa systeemissä. Laskennallinen **{index}`entalpianmuutos`** *(ΔH)* eli reaktiolämpö määritellään reaktiotuotteiden ja lähtöaineiden entalpioiden kautta. ∆H ilmoitetaan kertoimien ilmoittamia moolimääriä kohti, joka on vakiopaineessa sama kuin reaktiotuotteiden ja lähtöaineiden välinen entalpiaero:

$\mathrm{ΔH_{reaktio} = H_{reaktiotuotteet} - H_{lähtöaineet}}$

### {index}`Muodostumislämpö`
Aineen muodostumislämmöllä tarkoitetaan sitä entalpiamuutosta, joka syntyy, kun **yksi mooli ainetta syntyy alkuaineistaan** olosuhteissa T = 298.15 K ja p = 101.325 kPa. Alkuaineen pysyvimmän muodon entalpia on annetuissa olosuhteissa 0 kJ/mol.

:::{admonition} Esimerkki: asetyleenin (etyynin) reaktiolämpö
:class: tip

Määritetään asetyleenin (C<sub>2</sub>H<sub>2</sub>) palamisen reaktiolämpö ∆H. Oletettavasti reaktio on eksoterminen, joten vastauksen tulisi olla negatiivinen.

Muodostetaan ensin asetyleenin (eteenin) palamisen tasapainotettu reaktioyhtälö.

$\mathrm{2 \ C_2H_2 \ (g) + 5 \ O_2 \ (g) \longrightarrow 4 \ CO_2 \ (g) + 2 \ H_2O \ (g)}$

<a href="https://luma-lapinamk.github.io/miika-kemia/notebooks/taulukoita.html#muodostumislampoja" target="_blank">Muodostumislämpötaulukon</a> mukaan

$\mathrm{2 \ C \ (s) + H_2 \ (g) \longrightarrow C_2H_2 \ (g); \ \Delta H_1=+226.7 \ kJ}$<br>
Happikaasu on vapaa alkuaine, joten sen $\Delta H_2=0$.<br>
$\mathrm{C \ (s) + O_2 \ (g) \longrightarrow CO_2 \ (g); \ \Delta H_3=-393.5 \ kJ}$
$\mathrm{H_2 \ (g) + \frac{1}{2} O_2 \ (g) \longrightarrow H_2O \ (g); \ \Delta H_4=-241.8 \ kJ}$<br>

Reaktiolämmöksi saadaan reaktiotuotteiden ja lähtöaineiden välisenä entalpiaerona

$\begin{align}ΔH_{reaktio} &= H_{reaktiotuotteet} - H_{lähtöaineet} \\ \\
&=4\Delta H_3 + 2\Delta H_4 - (2\Delta H_1 + 5\Delta H_2) \\ \\
&=[4 \cdot (-393.5) + 2 \cdot (-241.8) - (2 \cdot 226.7 + 5 \cdot 0)] \ kJ \\ \\
&=-2511 \ kJ\end{align}$

Koska ΔH < 0, reaktio on eksoterminen ja arvo -2511 kJ on määritelmän mukaisesti moolia kohden.
:::

### {index}`Hessin laki`
Entalpiamuutos eli reaktiolämpö on riippumaton siitä, tapahtuuko reaktio suoraan vai välivaiheiden (osareaktioiden) kautta. Hessin lain mukaan reaktion entalpia voidaan laskea osareaktioiden avulla. Lain avulla voidaan täten määrittää minkä tahansa reaktion reaktiolämpö, jos kokonaisreaktion osareaktioiden reaktiolämmöt tunnetaan.

$\begin{equation*}
\begin{array}{ c c c }
\mathrm{Lähtöaineet} & \xrightarrow[]{\Delta H} & \mathrm{Reaktiotuotteet} \\
\uparrow & & \uparrow \\
\Delta H_{lähtöaineet} & & \Delta H_{tuotteet} \\
& \mathrm{Aineet} & \\
\end{array}
\end{equation*}$

:::{admonition} Esimerkki: metaanin muodostumislämpö
:class: tip

Metaania syntyy lähtöaineistaan hiilestä ja vetykaasusta alla olevan reaktion mukaisesti sen verran hitaasti, että sen muodostumislämmön kalorimetrinen määritys on hankalaa.

$\mathrm{C \ (s) + 2 \ H_2 \ (g) \longrightarrow CH_4 \ (g)}$

Käytetään avuksi Hessin lakia, kun hiilidoksidin ja divetyoksidin (eli veden) muodostumislämmöt tunnetaan. Taulukon mukaan

$\mathrm{C \ (s) + O_2 \ (g) \longrightarrow CO_2 \ (g); \ \Delta H_1=-393.5 \ kJ}$
$\mathrm{2 \ H_2 \ (g) + O_2 \ (g) \longrightarrow 2 \ H_2O \ (l); \ \Delta H_2=2 \cdot -285.8 \ kJ = -571.6 \ kJ}$

Lisäksi käytetään avuksi tunnettua arvoa metaanin palamisen reaktiolämmölle, joka on mitattu kalorimetrisesti.

$\mathrm{CH_4 \ (g) + 2 \ O_2 \ (g) \longrightarrow CO_2 \ (g) + 2 \ H_2O \ (l); \ \Delta H_3=-890 \ kJ}$

Lasketaan annetut kolme reaktioyhtälöä puolittain yhteen niin, että kaikki muu supistuu pois ja vain metaanin muodostumisreaktio jää jäljelle. Tämä onnistuu, kun kolmas reaktio käännetään ensin toisin päin eli

$\mathrm{CO_2 \ (g) + 2 \ H_2O \ (l) \longrightarrow CH_4 \ (g) + 2 \ O_2 \ (g); \ -\Delta H_3=+890 \ kJ}$

Saadaan täten

$\mathrm{C \ (s) + O_2 \ (g) + 2 \ H_2 \ (g) + O_2 \ (g) + CO_2 \ (g) + 2 \ H_2O \ (l) \longrightarrow CO_2 \ (g) + 2 \ H_2O \ (l) + CH_4 \ (g) + 2 \ O_2 \ (g)}$

joka supistettuna on 

$\mathrm{C \ (s) + 2 \ H_2 \ (g) \longrightarrow CH_4 \ (g)}$

ja metaanin muodostumislämmöksi saadaan lopulta

$\mathrm{\Delta H_1 + \Delta H_2 + (-\Delta H_3) = (-393.5-571.6+890) \ kJ = -75.1 \ kJ}$
:::

### Olomuodon muutokset ja entalpia
<p><a href="https://commons.wikimedia.org/wiki/File:Physics_matter_state_transition_1_en.svg#/media/File:Physics_matter_state_transition_1_en.svg"><img src="https://upload.wikimedia.org/wikipedia/commons/8/8f/Physics_matter_state_transition_1_en.svg" alt="Physics matter state transition 1 en.svg" height="192" width="640"></a><br><a href="https://creativecommons.org/licenses/by-sa/4.0" title="Creative Commons Attribution-Share Alike 4.0">CC BY-SA 4.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=15779425">Link</a></p>

## Reaktionopeuteen vaikuttavat tekijät
Kemiallisen reaktion nopeuteen vaikuttavat

- Systeemin lämpötila (törmäysenergian suuruus)
- Aineiden sekoittuminen (törmäysten todennäköisyys)
- Aineiden hienojakoisuus (kosketus- eli vuorovaikutuspinta-ala)
- Paine (törmäyksiä aikayksikössä)
- Katalyytti / Katalysaattori (muuttaa reaktiomekanismia ja alentaa siten aktivoitumisenergiaa, mutta ei itse kulu reaktiossa. Luonnon katalyytti = entsyymi)
```{figure-md} katalyytti
<img src="../images/aktivaatioenergia2.jpg" alt="Katalyytin vaikutus endotermisen reaktion aktivoitumisenergiaan." class="bg-primary mb-1" width="400px" align="center">

Katalyytin vaikutus endotermisen reaktion aktivoitumisenergiaan. Kuvan alkuperäinen tekijä: <a href="https://openstax.org/books/biology/pages/1-introduction" target="_blank">CNX OpenStax</a>, lähde: <a href="https://commons.wikimedia.org/wiki/File:Figure_06_05_01.jpg" target="_blank">Wikipedia</a>
```