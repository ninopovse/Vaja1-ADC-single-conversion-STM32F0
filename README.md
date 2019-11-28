# Vaja1-ADC-single-conversion-STM32F0

b) Glede na vašo razvojno ploščico in razširitveno vezje s tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? PC0.

c) V Pinout zavihku ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? 1 pretvornik

d. -Izbrani DC pretvornik ima oznako s trikotnikom. Kaj to pomeni? Trikotnik ima ker je delno v konfliktu z drugim pinom.
   -Kaj morate storiti, da rarešite to omejitev? Opišite in jo odpravite. Pin PC0 nastavimo na Analog ADC_IN10 in izberemo IN10 pretvornik. Pine, ki jih pa ne uporabljamo pa nastavimo na reset_state.

e) Razširite razdelek ADC. Koliko je vseh vhodnih kanalov? 16 kanalov.

f) Glede na potenciometer na vaši ploščici izberete-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora ustrezno pobarvati izbrani pin v zeleno barvo. Kaj izpiše poleg pina? ADC_IN10

h) Kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
 - 6 bit;  od 0 do 64
 - 10 bit; od 0 do 1024
 - 12 bit; od 0 do 4096
