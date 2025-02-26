Running Markdown (.md) files to Powerpoint
------------------------------------------

Standalone set up
=================

pandoc [input.md] -s -o [output.pptx] --reference-doc [template.pptx]

pandoc questionnaires.md -s -o test-qs.pptx --reference-doc ddi-q.pptx

