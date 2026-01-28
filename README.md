# HRC_payout_generator
_____________________________________________________________________________________________________
_____________________________________________________________________________________________________

TL;DR

Double-click the EXE → enter paid places, total prize pool, 1st / 2nd / last prize → click Generate.

_____________________________________________________________________________________________________
_____________________________________________________________________________________________________

Using the EXE

1/ Download the latest release and run HRC Payout Generator.exe (double-click).

2/ Fill in the fields:

  - Paid places: how many positions get paid
  - Total prize pool: total amount to distribute
  - Use 100 if you’re working in percent
  - Use the real prize pool (e.g., 25000) if you’re working in currency
  - Decimals: rounding decimals (usually 2)
  - Anchors (required):
      1st prize
      2nd prize
      Last prize (min-cash)
  - Final Table shape:
      FT places: default 9
      FT steepness multiplier: default 1.3333 (FT is 4/3 steeper than non-FT)
  - Output:
      Output folder: where the JSON will be saved
      Filename (optional): leave blank to auto-name

3/ Click Generate payout JSON.

4/ Import the generated .json into HoldemResources Calculator (HRC) as your payout structure.
