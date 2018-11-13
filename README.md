# SELF-SERVICE TICKETING KIOSK FOR CINEMAS
The software is used to help customers to buy movie tickets. We developed the software using agile development.

Location of java files:
All code is in the .\Software(Source code)\src\com\code, and I use three folders called "dom", "gui", "javabean" to store our java files.
"dom" mainly stores parsers written by us. 
"gui" mainly stores all java files related to interface of our system. 
"javabean" mainly stores entity classes.

Location of XML files:
XML files are stored in .\Software(Source code)

Location of pictures ued in our software:
All pictures we use in system are stored in .\Software(Source code)\resource 

Location of text files generated by software:
statistic reprot and ticket generated by software are stored in .\Software(Source code)

Configuration of our software:

1. You can open command line in .\Software(Source code)        
or you can open command line and then input:  cd "the location of current folder\Software(Source code)"

2. Then you should input: mkdir bin                    
All .class files will be stored in bin.

3. Then you should input: javac -d bin/ src/com/code/javabean/*.java src/com/code/dom/*.java src/com/code/gui/*.java
Notice that there is a space between "bin/" and "src"
If your computer cannot encode utf-8, you should input: javac -d bin/ -encoding utf-8 src/com/code/javabean/*.java src/com/code/dom/*.java src/com/code/gui/*.java

4. You should in input: java -cp bin/ com.code.gui.ClientFrame           
Then the software starts.



