# primer-design-tool
Input Validation:

Validates DNA sequences (only A, T, C, G bases allowed)
Checks for sequence length and content
Primer Design Algorithm:

Calculates melting temperature (Tm) using the Wallace rule and nearest-neighbor method
Computes GC content
Generates reverse complement sequences
Finds optimal primer pairs based on:
Length constraints (18-25 bp)
Tm range (55-65°C)
GC content (40-60%)
Product size (100-1000 bp)
User Interface:

Clean, professional design with Tailwind CSS
Sequence input textarea
Error handling and validation messages
Results table showing:
Forward and reverse primers
Melting temperatures
GC content
Product sizes
Loading state during calculations
Responsive layout
Features:

Displays up to 5 primer pairs
Shows detailed properties for each primer
Real-time validation
Mobile-friendly design
To use the tool:

Enter your DNA sequence in the textarea (only A, T, C, G bases)
Click "Design Primers"
View the generated primer pairs with their properties
The tool will automatically calculate optimal primer pairs based on standard PCR primer design criteria.
