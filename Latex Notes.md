# Convert a markdown file to Latex
# Not sure if this works
pandoc -f markdown -t latex hello.txt

# Use pdflatex
# This works
pdflatex file.tex

# Need to write in Markdown, convert to Latex, then PDF maybe
# Or straight from Markdown to PDF

# For outputting files to a directory:
pdflatex --output-directory=Output ts2.tex
