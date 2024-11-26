This is a Chinese LaTeX template made for course papers in HITSZ, it features:
 - Chinese compatible
 - page numbering in Roman numbers for the table of contents, Chinese and English abstracts
 - the formats of headings 1-3 are configured according to the HIT standard
 - other requirements in accordance with the school's academic criteria

To get this file up and running on your desktop, you should:
 - Install VS Code Studio, then download the extension **Latex Workshop** in its marketplace
 - Install MiKTeX (it provides on-the-fly package installation and management, just like the LaTeX version of Anaconda)
 - Install Perl (this is the dependency for some LaTeX packages)
 - In VS Code, click the gear icon in the lower left corner, choose _settings_, search for _Force Recipe Usage_ in the search bar, uncheck the box
 - use the hotkey <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>B</kbd> to compile the file, the PDF output will be saved in the same directory

Note that the last step is used to switch the compiler from the default one to XeLaTeX, which supports custom font faces
