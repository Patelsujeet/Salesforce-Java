# Salesforce--Java
Prerequiste
1) Install force-WSC.jar
    https://repo1.maven.org/maven2/com/force/api/force-wsc/48.0.0/force-wsc-48.0.0.jar
2) Tool.jar
    located in your local system 
      Java/jdk-xxx/lib/tools.jar
3) Antlr.jar
   https://www.antlr.org/download/antlr-4.7.2-complete.jar
4) enterprise Jar
    Need to generate buy using above given jar files
5) WSDL file


Steps
1) Create one folder with salesforce WSC (Name would be as per you wish)
2) Copy the above given jar files and paste in that folder.
    example :
        WSC
        |
        |___force-wsc-48.0.0.jar (Download from given link)
        |___tools.jar (Copy from Java/jdk.xx.yy/lib/tools.jar)
        |___antlr-4.7.2-complete.jar
   Note: All jar file must be in same folder
3) go to salesforce org -> setup -> in Quick Find enter "API" -> click on API -> click on "Generate Enterprise WSDL" -> click on "Generate" 
4) one XML file will be open in your browser and save that file as per below given name
      "enterprise.wsdl.xml"
5)
        
        