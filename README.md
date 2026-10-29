# molecular-cloning-buddy

Molecular Cloning Calculator 🧬
A calculator for Ligation and Gibson Assembly reactions. Built this to replace a folder full of clunky Excel spreadsheets that are a pain to navigate at the bench. It handles the molar ratio math and volume scaling automatically.

What's Inside
The tool packs two main calculators 

1. Ligation Calculator
Stops you from having to manually crunch molar ratios every time you swap an insert.
Automated Mass Calculations: Plug in your vector and insert sizes (bp) and concentrations (ng/µL). It immediately spits out the exact nanograms needed for 1:3, 1:5, and 1:7 molar ratios.
Master Mix Ready: Automatically calculates the pipetting volumes for your DNA, 10x Buffer, ATP, Ligase, and the remaining MQ water to hit a standard 20 µL reaction volume.

2. Gibson Assembly Calculator
Built to handle both single and multi-fragment (up to 3 inserts) assemblies without the headache.
Molar Conversions: Instantly converts your raw ng/µL and base pair lengths into pmol.
Vector Normalization: Normalizes your insert volumes against the vector for standard 1:1 (single insert) or 1:2 (multi-insert) molar equivalents.
Reaction Scaling: Checks against recommended max/min pmol limits and automatically scales the Gibson Master Mix and MQ water volumes for standard 10 µL or 20 µL reactions.

Usage
Deployment is basically nonexistent. You can use it right out of the box:
Clone the repo or just download the index.html file.
Double-click to open it in any modern browser.
For the best setup, just enable GitHub Pages on your repo so you can pull it up easily on your phone or lab tablet.

Contributing
If you spot an edge case where the math breaks, or if you want to add a Golden Gate assembly module, feel free to open an issue or drop a PR.
