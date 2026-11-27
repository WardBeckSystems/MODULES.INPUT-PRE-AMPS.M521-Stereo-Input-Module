# M521 · Input Pre Amps

Ward-Beck Systems M521, 1985|18. Wiki page: [M521 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M521.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 35 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 7 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 4 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 60 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 9 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 72 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [4 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1985 - M521 - 006.jpg](MANUALS/1985%20-%20M521%20-%20006.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivity** | -10 to +10 dBm (ref. 600 ohm source) |
| **Frequency response** | +/-0.25 dB from 30 Hz to 20 kHz |
| **Noise** | Greater than 75 to 80 dB signal to noise ratio for input sensitivities of -10 to +10 dBm. |
| **Harmonic distortion** | Less than 0.25% from 30 Hz to 20 kHz at 24 dBm output levels or less Less than 0.19 at kHz at +24 dBm output. |
| **Source impedance** | 600 ohms or less balanced |
| **Input impedances** | 30,000 ohms or greater |
| **Output impedances** | Less than 100 ohms at insert and direct outputs |
| **Load impedances** | 600 ohms balanced (at insertion point) 5000 ohms balanced (at direct outputs) |
| **Output levels** | dBm nominal, +26 dBm maximum |
| **Channel separation** | 60 dB |
| **Phasing** | Low number or numbered terminals of the input pair is in phase with the similar terminals of the output pair. |
| **Power requirements** | +/-25 volts dc, 100 mA nominal, 185 mA maximum. +12 volts dc, 50 mA |
| **Ambient temperature** | to 60 degrees Celsius |
| **Dimensions** | 1.60&quot; wide 14.15&quot; high 6.50&quot; deep (41 mm 360 mm 165 mm) Ibs oz (1.14 kg) net |

## Circuit description

From [1985 - M521 - 038.jpg](MANUALS/1985%20-%20M521%20-%20038.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**5A14-077 CONTROL ASSEMBLY**

The 5A14-077 is an interface control assembly between the St console r microprocessor based control system and the m520 series of input and submaster modules Channel/Solo_ Latches

Dual Latch U1 provides the holding or Latching circuitry to control the solid state program channel and solo SW | tches of the M520 series of modules The Latch outputs are buffered by transistor drivers Q1 through 04 The Latch maybe controlled by positive toggle voltage applied to P2 pin for the solo and P2 pin for the channel or program circuit. Pulsing these control inputs will result in the Latches alternately being set and cleared The Latch UIA and UIB maybe directly set or cleared from the control system Via pulses fed through C4 to C7 _ These controlling signals are held by the data bus Latch u7 _ Data Bus An bit data bus is connected to the input modules, for the purpose of feeding control signals or reading tally information. This data bus connects to the 5A14-077 at P1 pins to 15_ select Line at P1 pin and read/write control Line at P1 pin controls the flow of data to and from this assembly Tally_Buffers u5 and u6 are tally buffers which feed information from the input module pushbutton selectors and sense points onto the data bus upon command from the central control system Control Latch u7 is control Latch which feeds control pulses to remotely turn on and off the channel and solo solid state switches upon command from the central control system. ?ower_Decoupl ing This assembly utilizes low power cMOS circuitry throughout. ReguLator u8 decouples the unregulated +10 to +12 volt logic supply voltage down to +5 volts to operate the integrated circu ts

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWlYb3JZZl80bmM/view?resourcekey=0-iJTt91R6YMIzRCkyWaf-LA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWlYb3JZZl80bmM&resourcekey=0-iJTt91R6YMIzRCkyWaf-LA" width="240" alt="19xx - M521 - DOC - 2442-04-003 - SUB MASTER FADERS ADERS MONO IMPUT FADERS.jpg"></a><br><sub>19xx - M521 - DOC - 2442-04-003 - SUB MASTER FADERS ADERS MONO IMPUT FADERS</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOGJWZVpMZ043bXc/view?resourcekey=0-xTNY3arikblyFWIodofGqw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOGJWZVpMZ043bXc&resourcekey=0-xTNY3arikblyFWIodofGqw" width="240" alt="19xx - M521 - DOC - 521-04-001 - STEREO INPUT MODL.jpg"></a><br><sub>19xx - M521 - DOC - 521-04-001 - STEREO INPUT MODL</sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M521.stl`](MECHANICAL/M521.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M521)

- **Size:** 41 × 360 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 1.60" wide 14.15" high 6.50" deep (41 mm 360 mm 165 mm) Ibs oz (1.14 kg) net)
- **From the drawing:** 21 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M521 - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M521.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQV9VcGNmSFBpVmc/view?resourcekey=0-gU-VD5TM2FZyRb55lnk53A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQV9VcGNmSFBpVmc&resourcekey=0-gU-VD5TM2FZyRb55lnk53A" width="240" alt="1985 - M521 - 020 - Functional (2).jpg"></a><br><sub>1985|18 · 020 - Functional (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU3Jhcm9HV0x6dDQ/view?resourcekey=0-7ST8g-UmSSkrDF3PaMpkSA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU3Jhcm9HV0x6dDQ&resourcekey=0-7ST8g-UmSSkrDF3PaMpkSA" width="240" alt="1985 - M521 - 521-01-001 - AUX PRE-PCST AUX AUX AUX.jpg"></a><br><sub>1985|18 · 521-01-001 - AUX PRE-PCST AUX AUX AUX · <a href="SCHEMATICS/1985%20-%20M521%20-%20521-01-001%20-%20AUX%20PRE-PCST%20AUX%20AUX%20AUX%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVkowc2x0amNzcE0/view?resourcekey=0-uGKFfbxd7NqKDlSVU-HL0g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVkowc2x0amNzcE0&resourcekey=0-uGKFfbxd7NqKDlSVU-HL0g" width="240" alt="1985 - M521 - 521-02-001 - STEREO INPUT MODULE SCHEMATIC.jpg"></a><br><sub>1985|18 · 521-02-001 - STEREO INPUT MODULE SCHEMATIC · <a href="SCHEMATICS/1985%20-%20M521%20-%20521-02-001%20-%20STEREO%20INPUT%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS1phOFdoSFdsTzA/view?resourcekey=0-L8BZq3DUPZ89VnMsxlnNAA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS1phOFdoSFdsTzA&resourcekey=0-L8BZq3DUPZ89VnMsxlnNAA" width="240" alt="1985 - M521 - 521-02-001 - SYSTEMB TALLY ATT SENSE.jpg"></a><br><sub>1985|18 · 521-02-001 - SYSTEMB TALLY ATT SENSE · <a href="SCHEMATICS/1985%20-%20M521%20-%20521-02-001%20-%20SYSTEMB%20TALLY%20ATT%20SENSE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUUEyXy1WMVJ2WDA/view?resourcekey=0-AiFa6mi7hiL97gT7-5QfsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUUEyXy1WMVJ2WDA&resourcekey=0-AiFa6mi7hiL97gT7-5QfsQ" width="240" alt="1985 - M521 - 521-06-001 - STEREO INPUT MODULE COMPONENT LAYOUT.jpg"></a><br><sub>1985|18 · 521-06-001 - STEREO INPUT MODULE COMPONENT LAYOUT · <a href="SCHEMATICS/1985%20-%20M521%20-%20521-06-001%20-%20STEREO%20INPUT%20MODULE%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1985|18 · 020 - Functional](https://drive.google.com/file/d/0B0yR0b5T78SKQ0VIYzI4UVQzTE0/view?resourcekey=0-JSRdfZikcgvSXXPew1s2tQ) · [1985|18 · B 14-076-02-001 - SA14-076 STEREO CHANNEL AMPLIFIER - SCHEMATIC](https://drive.google.com/file/d/0B0yR0b5T78SKaFdpTnZnVDF2UW8/view?resourcekey=0-psXB2oMsQyaeyqKf6JU6-w)

Not on Google Drive yet: `19xx - 521-01-001 - STEREO INPUT MODULE FUNCTIONAL - ISS 2.jpg`, `19xx - 521-02-001 - STEREO INPUT MODULE SCHEMATIC - ISS 3.jpg`, `19xx - 521-02-001 - STEREO INPUT MODULE SCHEMATIC.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOUhVb1F3U2Q0NEE/view?resourcekey=0-i9i1HBUkDWPYkg492qjvjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOUhVb1F3U2Q0NEE&resourcekey=0-i9i1HBUkDWPYkg492qjvjA" width="240" alt="1985 - M521 - Sterio Input Module Connector Layout.jpg"></a><br><sub>1985|18 · Sterio Input Module Connector Layout</sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

**To check:**

- polarity assumed: 16 contacts given + / − that the drawing does not mark (e.g. P2-A INSERT OUT L +) (M521: 1985 - M521 - Sterio Input Module Connector Layout.jpg)

**Inserts:** INSERT L: INSERT OUT L → INSERT IN L · INSERT R: INSERT OUT R → INSERT IN R

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | INSERT OUT L - | insert_send | INSERT OUT L - | medium |
| 2 | INSERT OUT R - | insert_send | INSERT OUT R - | medium |
| 3 | INSERT PREFADE L - | out | INSERT PREFADE L - | medium |
| 4 | INSERT PREFADE R - | out | INSERT PREFADE R - | medium |
| 5 | INSERT IN L - | insert_return | INSERT IN L - | medium |
| 6 | INSERT IN R - | insert_return | INSERT IN R - | medium |
| 7 | SHIELD | shield | shield | medium |
| 8 | L DIRECT - | out | L DIRECT - | medium |
| 9 | R DIRECT - | out | R DIRECT - | medium |
| 10 | SHIELD | shield | shield | medium |
| 11 | N/C | nc |  | medium |
| 12 | RD/NWR | control_in | DATA BUS | medium |
| 13 | DATA BUS D0 | bus | DATA BUS | medium |
| 14 | DATA BUS D2 | bus | DATA BUS | medium |
| 15 | DATA BUS D4 | bus | DATA BUS | medium |
| 16 | DATA BUS D6 | bus | DATA BUS | medium |
| 17 | ATTENUATOR SENSE | other | ATTENUATOR SENSE | medium |
| 18 | N/C | nc |  | medium |
| 19 | -25 V | power |  | medium |
| 20 | 25 V COMMON | ground |  | medium |
| 21 | +25 V | power |  | medium |
| 22 | CHASSIS GROUND | ground |  | medium |
| A | INSERT OUT L + | insert_send | INSERT OUT L + | medium |
| B | INSERT OUT R + | insert_send | INSERT OUT R + | medium |
| C | INSERT PREFADE L + | out | INSERT PREFADE L + | medium |
| D | INSERT PREFADE R + | out | INSERT PREFADE R + | medium |
| E | INSERT IN L + | insert_return | INSERT IN L + | medium |
| F | INSERT IN R + | insert_return | INSERT IN R + | medium |
| H | SHIELD | shield | shield | medium |
| J | L DIRECT + | out | L DIRECT + | medium |
| K | R DIRECT + | out | R DIRECT + | medium |
| L | SHIELD | shield | shield | medium |
| M | N/C | nc |  | medium |
| N | NSEL (MODULE SELECT, ACTIVE LOW) | control_in | DATA BUS | medium |
| P | DATA BUS D1 | bus | DATA BUS | medium |
| R | DATA BUS D3 | bus | DATA BUS | medium |
| S | DATA BUS D5 | bus | DATA BUS | medium |
| T | DATA BUS D7 | bus | DATA BUS | medium |
| U | N/C | nc |  | medium |
| V | CONTROL COMMON | ground |  | medium |
| W | N/C | nc |  | medium |
| X | N/C | nc |  | medium |
| Y | +12 V | power |  | medium |
| Z | N/C | nc |  | medium |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHJFbUF1TTZuTlE/view?resourcekey=0-bl9oafE42_z48QNHT6YWqA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHJFbUF1TTZuTlE&resourcekey=0-bl9oafE42_z48QNHT6YWqA" width="240" alt="1985 - M521 - 000.jpg"></a><br><sub>1985|18 · 000</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVU1XLVhHLVF4UE0/view?resourcekey=0-O5B4kiQaKah10Tgyf25eAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVU1XLVhHLVF4UE0&resourcekey=0-O5B4kiQaKah10Tgyf25eAw" width="240" alt="1985 - M521 - 001.jpg"></a><br><sub>1985|18 · 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRFdyYVM1SzVXelU/view?resourcekey=0-XFDcPcGPaw6QfNyS1oR41g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRFdyYVM1SzVXelU&resourcekey=0-XFDcPcGPaw6QfNyS1oR41g" width="240" alt="1985 - M521 - 002.jpg"></a><br><sub>1985|18 · 002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTzhpdkNvZW1zam8/view?resourcekey=0-55U3AS23TlolU8j0wJq8Kw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTzhpdkNvZW1zam8&resourcekey=0-55U3AS23TlolU8j0wJq8Kw" width="240" alt="1985 - M521 - 003.jpg"></a><br><sub>1985|18 · 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUx6RDc2dk8ycVE/view?resourcekey=0-bFxp2KKWsq3spwLBpD6ROw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUx6RDc2dk8ycVE&resourcekey=0-bFxp2KKWsq3spwLBpD6ROw" width="240" alt="1985 - M521 - 004.jpg"></a><br><sub>1985|18 · 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkoyd2VnMzdtWVk/view?resourcekey=0-1MxBA5SLQLrdhZLhaz4Ksw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkoyd2VnMzdtWVk&resourcekey=0-1MxBA5SLQLrdhZLhaz4Ksw" width="240" alt="1985 - M521 - 005.jpg"></a><br><sub>1985|18 · 005</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY1BDNG5xN1dYZjg/view?resourcekey=0-yeKIkfqgY-SitbKhV8jixw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY1BDNG5xN1dYZjg&resourcekey=0-yeKIkfqgY-SitbKhV8jixw" width="240" alt="1985 - M521 - 006.jpg"></a><br><sub>1985|18 · 006</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYjItZVhXVlhSQlE/view?resourcekey=0-jHqck1eSWhBIeumLHCBkVA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYjItZVhXVlhSQlE&resourcekey=0-jHqck1eSWhBIeumLHCBkVA" width="240" alt="1985 - M521 - 007.jpg"></a><br><sub>1985|18 · 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdjZXbW1FOXpLRWc/view?resourcekey=0-SpmzTX6_4lyzAz-96g7H6g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdjZXbW1FOXpLRWc&resourcekey=0-SpmzTX6_4lyzAz-96g7H6g" width="240" alt="1985 - M521 - 008.jpg"></a><br><sub>1985|18 · 008</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVDZhYlZlU05ONkE/view?resourcekey=0-hsnz1qEUqH76CkeuQPZxzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVDZhYlZlU05ONkE&resourcekey=0-hsnz1qEUqH76CkeuQPZxzg" width="240" alt="1985 - M521 - 009.jpg"></a><br><sub>1985|18 · 009</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlRkX3J6Nk9FXzQ/view?resourcekey=0-czXt5LVhBp91CPf9mkGLEg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlRkX3J6Nk9FXzQ&resourcekey=0-czXt5LVhBp91CPf9mkGLEg" width="240" alt="1985 - M521 - 010.jpg"></a><br><sub>1985|18 · 010</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYm5hT1FkVEx6RWM/view?resourcekey=0-OUumNKGhcIyudB506herhQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYm5hT1FkVEx6RWM&resourcekey=0-OUumNKGhcIyudB506herhQ" width="240" alt="1985 - M521 - 011.jpg"></a><br><sub>1985|18 · 011</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdDA1N1U0X185RWs/view?resourcekey=0-hdCnSXDMC5YvrvCWnU1rRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdDA1N1U0X185RWs&resourcekey=0-hdCnSXDMC5YvrvCWnU1rRQ" width="240" alt="1985 - M521 - 012.jpg"></a><br><sub>1985|18 · 012</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS0MzT1dZOEw1WlU/view?resourcekey=0-xtGje3gryAeXx9RmGooAhA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS0MzT1dZOEw1WlU&resourcekey=0-xtGje3gryAeXx9RmGooAhA" width="240" alt="1985 - M521 - 013.jpg"></a><br><sub>1985|18 · 013</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb01GeENWRDF5RHM/view?resourcekey=0-qMQRABkGQJoCf5zBwkvCdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb01GeENWRDF5RHM&resourcekey=0-qMQRABkGQJoCf5zBwkvCdQ" width="240" alt="1985 - M521 - 014.jpg"></a><br><sub>1985|18 · 014</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWFZ2Q2dFZzNIN2M/view?resourcekey=0-_swtfZmMos4AbqlQlZiXWw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWFZ2Q2dFZzNIN2M&resourcekey=0-_swtfZmMos4AbqlQlZiXWw" width="240" alt="1985 - M521 - 015.jpg"></a><br><sub>1985|18 · 015</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeTZqd0hoX2V1b2c/view?resourcekey=0-KLJNILNho9y1_uJ8pi05pw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeTZqd0hoX2V1b2c&resourcekey=0-KLJNILNho9y1_uJ8pi05pw" width="240" alt="1985 - M521 - 016.jpg"></a><br><sub>1985|18 · 016</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdzlGR0h4VVh6T1E/view?resourcekey=0-4_Ftww1g0G5iSVx7er8Dfg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdzlGR0h4VVh6T1E&resourcekey=0-4_Ftww1g0G5iSVx7er8Dfg" width="240" alt="1985 - M521 - 017 (2).jpg"></a><br><sub>1985|18 · 017 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2hPTVcxMERwdEU/view?resourcekey=0-_lULc_OIiZDsXkYth2gXCA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2hPTVcxMERwdEU&resourcekey=0-_lULc_OIiZDsXkYth2gXCA" width="240" alt="1985 - M521 - 018.jpg"></a><br><sub>1985|18 · 018</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQjA1SXp0bWx3eVk/view?resourcekey=0-YM9KZTrhzIdgG4MtVDtttw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQjA1SXp0bWx3eVk&resourcekey=0-YM9KZTrhzIdgG4MtVDtttw" width="240" alt="1985 - M521 - 019 - Module.jpg"></a><br><sub>1985|18 · 019 - Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTTc3QzRuTkN4bVU/view?resourcekey=0-h1H3-iu9hviYWz2ZY9JfqA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTTc3QzRuTkN4bVU&resourcekey=0-h1H3-iu9hviYWz2ZY9JfqA" width="240" alt="1985 - M521 - 021 (2).jpg"></a><br><sub>1985|18 · 021 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUTJzbm91VGItdmM/view?resourcekey=0-gBWihIPkTG1SGtFGOuRaVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUTJzbm91VGItdmM&resourcekey=0-gBWihIPkTG1SGtFGOuRaVg" width="240" alt="1985 - M521 - 022.jpg"></a><br><sub>1985|18 · 022</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWW55VE50LXlaYkE/view?resourcekey=0-BZK1uEFq8RWCnxY4KAOxvA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWW55VE50LXlaYkE&resourcekey=0-BZK1uEFq8RWCnxY4KAOxvA" width="240" alt="1985 - M521 - 023.jpg"></a><br><sub>1985|18 · 023</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOUp2Qm5iakQ0Qm8/view?resourcekey=0-2EdYG3xX6e0p0OUXURXIWg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOUp2Qm5iakQ0Qm8&resourcekey=0-2EdYG3xX6e0p0OUXURXIWg" width="240" alt="1985 - M521 - 024.jpg"></a><br><sub>1985|18 · 024</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZVZ5Z19qNXcwMVU/view?resourcekey=0-5qF6pXBRniODuIWMtOoEog" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZVZ5Z19qNXcwMVU&resourcekey=0-5qF6pXBRniODuIWMtOoEog" width="240" alt="1985 - M521 - 025.jpg"></a><br><sub>1985|18 · 025</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWWdlSVlmdzhQYjg/view?resourcekey=0-TDySleDdBdx7nrbrQZtonQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWWdlSVlmdzhQYjg&resourcekey=0-TDySleDdBdx7nrbrQZtonQ" width="240" alt="1985 - M521 - 026.jpg"></a><br><sub>1985|18 · 026</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeWp1TWw5X2EyRDQ/view?resourcekey=0-gfC_esrhvJpNI4e47SuILA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeWp1TWw5X2EyRDQ&resourcekey=0-gfC_esrhvJpNI4e47SuILA" width="240" alt="1985 - M521 - 027.jpg"></a><br><sub>1985|18 · 027</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVVJnM3QwNm5jSHM/view?resourcekey=0-ZGwez9vDEvMbip7cosNx9A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVVJnM3QwNm5jSHM&resourcekey=0-ZGwez9vDEvMbip7cosNx9A" width="240" alt="1985 - M521 - 028 (2).jpg"></a><br><sub>1985|18 · 028 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ293V0s0dDdMbW8/view?resourcekey=0-oXxh4UmYf3iB24umuhlamA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ293V0s0dDdMbW8&resourcekey=0-oXxh4UmYf3iB24umuhlamA" width="240" alt="1985 - M521 - 029.jpg"></a><br><sub>1985|18 · 029</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV2xWdmROY3RzYU0/view?resourcekey=0-smcPZIDsNaLU5ElJqV_7mQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV2xWdmROY3RzYU0&resourcekey=0-smcPZIDsNaLU5ElJqV_7mQ" width="240" alt="1985 - M521 - 030.jpg"></a><br><sub>1985|18 · 030</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQkdfeEdZS0VFNDg/view?resourcekey=0-OqtYFaHF52KfRBrpmwlbNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQkdfeEdZS0VFNDg&resourcekey=0-OqtYFaHF52KfRBrpmwlbNg" width="240" alt="1985 - M521 - 031.jpg"></a><br><sub>1985|18 · 031</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX05zd2x3ZWQ1T1U/view?resourcekey=0-EuPRYWOs1iP0YtY4u87L1A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX05zd2x3ZWQ1T1U&resourcekey=0-EuPRYWOs1iP0YtY4u87L1A" width="240" alt="1985 - M521 - 032.jpg"></a><br><sub>1985|18 · 032</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSlA0N0RjYkluNDA/view?resourcekey=0-sNoiCr20oUF00dHa0aRv3w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSlA0N0RjYkluNDA&resourcekey=0-sNoiCr20oUF00dHa0aRv3w" width="240" alt="1985 - M521 - 033.jpg"></a><br><sub>1985|18 · 033</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXNIS3BNOE1ycVk/view?resourcekey=0-1nLO_To8BVD0U5T3wKEMcA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXNIS3BNOE1ycVk&resourcekey=0-1nLO_To8BVD0U5T3wKEMcA" width="240" alt="1985 - M521 - 034.jpg"></a><br><sub>1985|18 · 034</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa2p1b2xLTmRoTms/view?resourcekey=0-eCKKgscKsthwMMUA1QmlKg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa2p1b2xLTmRoTms&resourcekey=0-eCKKgscKsthwMMUA1QmlKg" width="240" alt="1985 - M521 - 035.jpg"></a><br><sub>1985|18 · 035</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQXFGLXZNaWt0M3c/view?resourcekey=0-Pu88mclc-lUW9ylA5k7lMQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQXFGLXZNaWt0M3c&resourcekey=0-Pu88mclc-lUW9ylA5k7lMQ" width="240" alt="1985 - M521 - 036.jpg"></a><br><sub>1985|18 · 036</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWlzaVpDZkVuY3c/view?resourcekey=0-qns-v3K9OUHPUL2Q7lKDRA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWlzaVpDZkVuY3c&resourcekey=0-qns-v3K9OUHPUL2Q7lKDRA" width="240" alt="1985 - M521 - 037.jpg"></a><br><sub>1985|18 · 037</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKek9fczhzVGVTWkk/view?resourcekey=0-1KnIioPcowAPchOyMMxB0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKek9fczhzVGVTWkk&resourcekey=0-1KnIioPcowAPchOyMMxB0A" width="240" alt="1985 - M521 - 038.jpg"></a><br><sub>1985|18 · 038</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKS3ZsX0VUeG9URW8/view?resourcekey=0-DROwVxrSYfutgy20a9bOCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKS3ZsX0VUeG9URW8&resourcekey=0-DROwVxrSYfutgy20a9bOCw" width="240" alt="1985 - M521 - 039.jpg"></a><br><sub>1985|18 · 039</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1c1dUljcmYtZmc/view?resourcekey=0-A-2TjKbQSru7F_IrPnwGYg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1c1dUljcmYtZmc&resourcekey=0-A-2TjKbQSru7F_IrPnwGYg" width="240" alt="1985 - M521 - 040.jpg"></a><br><sub>1985|18 · 040</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKellPWnU5bUZNRXc/view?resourcekey=0-7V9XifQeRIcgFvan_4CgGA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKellPWnU5bUZNRXc&resourcekey=0-7V9XifQeRIcgFvan_4CgGA" width="240" alt="1985 - M521 - 041 (2).jpg"></a><br><sub>1985|18 · 041 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWx3cERQT2s3WjQ/view?resourcekey=0-zdMaj6o8bvcpnBTIyKBaSg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWx3cERQT2s3WjQ&resourcekey=0-zdMaj6o8bvcpnBTIyKBaSg" width="240" alt="1985 - M521 - 041.jpg"></a><br><sub>1985|18 · 041</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRk9uUUFMSHN6NWs/view?resourcekey=0-lJj9wE69ZJbzM-_k_6va0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRk9uUUFMSHN6NWs&resourcekey=0-lJj9wE69ZJbzM-_k_6va0A" width="240" alt="19xx - M521 - AD - WBSPS - AD - LS series 003.jpg"></a><br><sub>19xx - M521 - AD - WBSPS - AD - LS series 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbFk3ZWlfQTQxdHc/view?resourcekey=0-HhWPKcg7Ls5SELA1psGokQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbFk3ZWlfQTQxdHc&resourcekey=0-HhWPKcg7Ls5SELA1psGokQ" width="240" alt="19xx - M521 - DOC - 004.jpg"></a><br><sub>19xx - M521 - DOC - 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaVExUlNPcU5VTkk/view?resourcekey=0-99-0K0XkkijrSRAOK8Vz1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaVExUlNPcU5VTkk&resourcekey=0-99-0K0XkkijrSRAOK8Vz1w" width="240" alt="19xx - M521 - DOC - 007.jpg"></a><br><sub>19xx - M521 - DOC - 007</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT1JzUi1hczZrekU/view?resourcekey=0-c_DWul-nM1uVcirXGJnviQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT1JzUi1hczZrekU&resourcekey=0-c_DWul-nM1uVcirXGJnviQ" width="240" alt="19xx - M521 - DOC - 011.jpg"></a><br><sub>19xx - M521 - DOC - 011</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWll1T3U3d1FlUkE/view?resourcekey=0-_gOzUE4b-G5toHgg-JB2NQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWll1T3U3d1FlUkE&resourcekey=0-_gOzUE4b-G5toHgg-JB2NQ" width="240" alt="19xx - M521 - DOC - 015.jpg"></a><br><sub>19xx - M521 - DOC - 015</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLU5TOVlib0NocXc/view?resourcekey=0-9H42t9RZK8zcdw-ne1Pz5g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLU5TOVlib0NocXc&resourcekey=0-9H42t9RZK8zcdw-ne1Pz5g" width="240" alt="19xx - M521 - DOC - 016.jpg"></a><br><sub>19xx - M521 - DOC - 016</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWXJ5T01fN1ljYVU/view?resourcekey=0-O2vE2I4LGjtm76GHmQbaIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWXJ5T01fN1ljYVU&resourcekey=0-O2vE2I4LGjtm76GHmQbaIQ" width="240" alt="19xx - M521 - DOC - 017.jpg"></a><br><sub>19xx - M521 - DOC - 017</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeU5PVEZWZnowbDQ/view?resourcekey=0-ZReLvKRYBLvxwEMXUwSw9w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeU5PVEZWZnowbDQ&resourcekey=0-ZReLvKRYBLvxwEMXUwSw9w" width="240" alt="19xx - M521 - DOC - 018.jpg"></a><br><sub>19xx - M521 - DOC - 018</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmRKTGVocVNrOXM/view?resourcekey=0-ApH2ftoskYJ88n-omHD8sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmRKTGVocVNrOXM&resourcekey=0-ApH2ftoskYJ88n-omHD8sg" width="240" alt="19xx - M521 - DOC - 030.jpg"></a><br><sub>19xx - M521 - DOC - 030</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTGRNY3dWcXVjYVU/view?resourcekey=0-0uKKxuRwoUhaPtF99j_mnw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTGRNY3dWcXVjYVU&resourcekey=0-0uKKxuRwoUhaPtF99j_mnw" width="240" alt="19xx - M521 - DOC - 031.jpg"></a><br><sub>19xx - M521 - DOC - 031</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbkZZRmp3d3Q1RmM/view?resourcekey=0-MnZxtyDRE4JjGML6hHU65w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbkZZRmp3d3Q1RmM&resourcekey=0-MnZxtyDRE4JjGML6hHU65w" width="240" alt="19xx - M521 - DOC - 032.jpg"></a><br><sub>19xx - M521 - DOC - 032</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1gv_rUE3mG3NlYtclvxesbGgBYy_gIrs2/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1gv_rUE3mG3NlYtclvxesbGgBYy_gIrs2" width="240" alt="19xx - M521 - DOC - RTO Racks Information Sheet.jpg"></a><br><sub>19xx - M521 - DOC - RTO Racks Information Sheet</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1985|18 · 017](https://drive.google.com/file/d/0B0yR0b5T78SKblZUeGRWcDZCMkU/view?resourcekey=0-35OSpf1XpzkZFJwsFJKyZg) · [1985|18 · 021](https://drive.google.com/file/d/0B0yR0b5T78SKOFgyb2JZclMwX1E/view?resourcekey=0-M95AtlcQ5xgNiyql58Hjnw) · [1985|18 · 028](https://drive.google.com/file/d/0B0yR0b5T78SKNURER0pNbkdwX3c/view?resourcekey=0-vbtJuMmoP29To5kDCqXeGA)

Not on Google Drive yet: `19xx - M521 - PARTS LIST SA14-077 CONTROL ASSEMBLY.jpg`, `M521 - 001.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1985 - M521 - 521-01-001 - AUX PRE-PCST AUX AUX AUX.kicad_sch](KICAD/1985%20-%20M521%20-%20521-01-001%20-%20AUX%20PRE-PCST%20AUX%20AUX%20AUX.kicad_sch)
- [1985 - M521 - 521-02-001 - STEREO INPUT MODULE SCHEMATIC.kicad_sch](KICAD/1985%20-%20M521%20-%20521-02-001%20-%20STEREO%20INPUT%20MODULE%20SCHEMATIC.kicad_sch)
- [1985 - M521 - 521-02-001 - SYSTEMB TALLY ATT SENSE.kicad_sch](KICAD/1985%20-%20M521%20-%20521-02-001%20-%20SYSTEMB%20TALLY%20ATT%20SENSE.kicad_sch)
- [1985 - M521 - B 14-076-02-001 - SA14-076 STEREO CHANNEL AMPLIFIER - SCHEMATIC.kicad_sch](KICAD/1985%20-%20M521%20-%20B%2014-076-02-001%20-%20SA14-076%20STEREO%20CHANNEL%20AMPLIFIER%20-%20SCHEMATIC.kicad_sch)
- [19xx - 521-01-001 - STEREO INPUT MODULE FUNCTIONAL - ISS 2.kicad_sch](KICAD/19xx%20-%20521-01-001%20-%20STEREO%20INPUT%20MODULE%20FUNCTIONAL%20-%20ISS%202.kicad_sch)
- [19xx - 521-02-001 - STEREO INPUT MODULE SCHEMATIC - ISS 3.kicad_sch](KICAD/19xx%20-%20521-02-001%20-%20STEREO%20INPUT%20MODULE%20SCHEMATIC%20-%20ISS%203.kicad_sch)
- [19xx - 521-02-001 - STEREO INPUT MODULE SCHEMATIC.kicad_sch](KICAD/19xx%20-%20521-02-001%20-%20STEREO%20INPUT%20MODULE%20SCHEMATIC.kicad_sch)
- [M521.kicad_sym](KICAD/M521.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
