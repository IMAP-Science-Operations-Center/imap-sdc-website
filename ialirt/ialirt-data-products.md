## Data Products

### ACE-heritage, near real-time data products produced by I-ALiRT


These I-ALiRT data products correspond to products produced by ACE but at a higher cadence.
<!--
	Markdown files will also accept HTML formatted items.
	Since markdown tables are difficult to edit and not as fleible as HTML tables,
	tables are kept as HTML tables.
-->
<table>
    <thead>
    <tr>
        <th>IMAP Source</th>
        <th>I-ALiRT Data Product</th>
        <th>Description</th>
        <th>Units</th>
        <th>I-ALiRT Cadence</th>
        <th>ACE RTSW Cadence</th>
    </tr>
    </thead>
    <tr>
        <td rowspan="3">SWAPI</td>
        <td>
            pseudo-speed (u<sub>p</sub>)
        </td>
        <td rowspan="3">Coincidence counts of 0.4 to 10 keV/q solar wind H<sup>+</sup> protons grouped as a single 12-second coarse sweep (across 62 energy steps of the ESA energy range)</td>
        <td> km/s </td>
        <td rowspan="3">12 sec</td>
        <td rowspan="3">64 sec</td>
    </tr>
    <tr>
        <td>
            pseudo-density (n<sub>p</sub>)
        </td>
        <td>#/cm3</td>
    </tr>
    <tr>
        <td>
            pseudo-temperature (T<sub>p</sub>)
        </td>
        <td>K</td>
    </tr>
    <tr>
        <td>CoDICE-Hi</td>
        <td>Suprathermal proton flux</td>
        <td>H<sup>+</sup> proton fluxes (differential intensities; 15 energy ranges)</td>
        <td>#/(cm2-sr-s-MeV)</td>
        <td>1 min</td>
        <td>5 min</td>
    </tr>
    <tr>
        <td>HIT</td>
        <td>SEP proton count rates</td>
        <td>6 to 15 MeV protons (2 energy ranges, omnidirectional look direction)</td>
        <td>#/s</td>
        <td>1 min</td>
        <td>5 min</td>
    </tr>
    <tr>
        <td rowspan="2">MAG</td>
        <td>B vectors <br> </td>
        <td rowspan="2">GSE, GSM, and RTN coordinates. Magnetic field measurements at dynamic range of ± 512 nT and resolution ≥ 16 pT</td>
        <td>nT</td>
        <td rowspan="2">4 sec</td>
        <td rowspan="2">60 sec</td>
    </tr>
    <tr>
        <td>
            Azimuthal and elevation angles of B (&phi;<sub>B</sub>, &Theta;<sub>B</sub>)
        </td>
        <td>
            degrees
        </td>
    </tr>
</table>

### New I-ALiRT data products, not available in ACE

These new I-ALiRT data products will enhance space weather forecasting.

<table>
    <thead>
    <tr>
        <th>IMAP Source</th>
        <th>I-ALiRT Data Product</th>
        <th>Description</th>
        <th>Units</th>
        <th>I-ALiRT Cadence</th>
    </tr>
    </thead>
    <tr>
        <td>CoDICE-Lo</td>
        <td>Solar wind charge state ratios and elemental abundances</td>
        <td>C<sup><small>6+</small></sup>/C<sup><small>5+</small></sup>, O<sup><small>7+</small></sup>/O<sup><small>6+</small></sup>, Fe<sup><small>(low)</small></sup>/Fe<sup><small>(high)</small></sup>, C/O, Mg/O, Fe/O determined from pseudo-number densities of solar wind species</td>
        <td>unitless</td>
        <td>4 min</td>
    </tr>
    <tr>
        <td rowspan="2">HIT</td>
        <td>SEP electron count rates</td>
        <td>&lt; 1 MeV electrons (2 energy ranges, each for sunward and antisunward look directions)</td>
        <td rowspan="2">#/s</td>
        <td rowspan="2">1 min</td>
    </tr>
	<tr>
        <td>Helium-4 count rates</td>
        <td>6 to 70 MeV/nuc 4He (2 energy ranges, omnidirectional look direction)</td>
    </tr>
    <tr>
        <td rowspan="2">SWE</td>
        <td>Identification of counterstreaming (bidirectional) electron flow</td>
        <td>A single number indicating whether electrons are flowing in one direction along the magnetic field or both directions (parallel and antiparallel) to the magnetic field</td>
        <td> 0 = unidirectional <br> 1 = bidirectional</td>
        <td rowspan="2">1 min</td>
    </tr>
    <tr>
        <td>Solar wind electron count rates</td>
        <td>Normalized counts of 100 eV to 1 keV suprathermal electrons summed over 7 CEMs and all spin angles, at each energy channel (8 total).</td>
        <td>Normalized #/s</td>
    </tr>
</table>
