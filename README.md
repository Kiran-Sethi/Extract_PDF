# Extract_PDF
Python scripts to demonstrate extraction of the text and tabular content from the PDF.

Using PyPDF2 library , we can extract the text content from the PDF files . I demonstrated the extraction of paragraphs using the python script.

1. To identify paragraphs , text is splitted over sentence ending  with punctuation mark '?/./!' followed by line break.

2. Paragraphs not starting with Capital Letters are discarded as bad paragraph.

3. Paragraph continuing over page breaks are considered accordingly.


Also , using camelot-py  we can extract the tabular content from the PDF.

