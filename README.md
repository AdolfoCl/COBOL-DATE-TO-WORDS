# FECHA-A-PALABRAS (DATE TO WORDS)
UNISYS MCP COBOL sample date to words

Return the date in the following format: 

~~~~
    <day of week>, ## de <month> de ####
~~~~

Valid date from 19000101 until 99991231 (format "yyyymmdd")

The parameter must be preceded by one letter indicating the result word case.

This letter posibilities are:

~~~~
    m ---> lower case
    M ---> UPPER CASE
    l ---> Day and Month in Camel
    L ---> Day in Camel and month in lower case
~~~~

Example:
~~~~
   input:
   
        L20190202
   
   result in: 
   
        Sabado, 02 de febrero de 2019
~~~~