## Features
This is a ready-to-use, simple Chinese LaTeX template made for course papers in HITSZ(哈工大深圳), it features:
 - Chinese compatibility
 - Chinese and English characters are in Songti and Times New Roman respectively by default
 - page numbering in Roman numbers for the table of contents, Chinese and English abstracts
 - the formats of headings 1-3 are configured according to the HIT standard
 - other requirements in accordance with the school's academic criteria

## Compile
You can create/edit LaTeX projects using <a href="https://www.overleaf.com">Overleaf</a>

Alternatively, to get this file up and running on your desktop, you should:
 - Install VS Code Studio, then download the extension **Latex Workshop** in its marketplace
 - Install <a href="https://miktex.org/howto/install-miktex">MiKTeX</a> (it provides on-the-fly package installation and management, just like the LaTeX version of Anaconda)
 - Install <a href="https://strawberryperl.com/">Strawberry Perl</a> (this is the dependency for some LaTeX packages)
 - In VS Code, click the gear icon in the lower left corner, choose _settings_, search for _Force Recipe Usage_ in the search bar, uncheck the box
 - Press <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>B</kbd> to compile the file, the PDF output will be saved in the same directory

Note that the second to last step is used to switch the compiler from the default one to _**XeLaTeX**_, which supports custom font faces

## Preview
![image](https://github.com/user-attachments/assets/d41fc57d-b5af-4d45-8461-2bc23e28a851)
