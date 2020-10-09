## Kestral
Using c# Kestrel server to create a simple sample of a language server

### Description
simple language server api. 

### Command template
`/tools/antlr4-csharp-4.6.1-SNAPSHOT-complete.jar -package <NAMESPACE-OF-YOUR-PROGRAM> -o <OUTPUT_DIR> -Dlanguage=CSharp_v4_5 <PATH-TO-GRAMMAR>`

### Command to generate c# Files 
`cd antlr && java -jar   antlr-4.8-complete.jar  -visitor  -package StratosServer -o ../generated/ -Dlanguage=CSharp StratosParser.g4 StratosLexer.g4 && cd ..`
