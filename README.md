# Wiegand Code Parser & Converter (26-bit and 34-bit)

This application is designed to easily convert Wiegand access control codes between different formats and verify their parity.

## How to Use

1. **Select Size:** Choose between **26-Bit** (standard format) or **34-Bit** (extended format).

2. **Select Input Mode:**

   * **Decimal/Hexadecimal/Binary:** Use this mode to parse a complete Wiegand code.

   * **FC/CN Pair:** Use this mode to *generate* a full Wiegand code by entering the Facility Code (FC) and Card Number (CN) separately.

3. **Enter Data:** Input the code or the FC/CN pair into the relevant field(s).

4. **Click "Parse & Convert."**

## Output Explained

The results section provides a complete breakdown of the code:

* **Parity Check Status:** Indicates if the entered full code is **VALID** or **INVALID** based on the Wiegand parity rules for the selected size. (For FC/CN Pair input, the generated code is always **VALID**.)

* **Full Binary Code:** Shows the 26 or 34 bits, color-coded for visual clarity:

  * <span style="color: #f43f5e; font-weight: 700;">Red:</span> Parity Bits

  * <span style="color: #10b981; font-weight: 700;">Green:</span> Facility Code (FC)

  * <span style="color: #3b82f6; font-weight: 700;">Blue:</span> Card Number (CN)

* **Extracted Values:** Shows the Facility Code and Card Number in decimal format.

* **Decimal/Hexadecimal Equivalents:** Displays the final code in the alternate formats.
