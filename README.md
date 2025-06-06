# Java-code installation
# Windows
🔧 Step-by-step:
* Go to the JDK download page:
=> Visit: https://www.oracle.com/java/technologies/javase-downloads.html

-> Download the installer:
1)Click on the latest JDK version (e.g., JDK 21 or JDK 17).
2)Choose Windows x64 Installer (.exe) and download it.

->Install the JDK:
1)Run the .exe file and follow the instructions (default settings are fine).
2) It will usually install to a folder like: C:\Program Files\Java\jdk-XX
3) Set Environment Variables (Optional but recommended):
4) Search for "Environment Variables" in Start and open it.
5) Under System Variables, find Path, click Edit, then New, and add:
=> C:\Program Files\Java\jdk-XX\bin
Click OK and apply.

6) Verify installation:
Open Command Prompt and type:
java -version
javac -version
You should see the installed version of Java and the compiler.

