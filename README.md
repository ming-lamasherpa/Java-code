# ☕ Java Installation (Windows)

## 🔧 Steps

### 1️⃣ Download JDK
- Go to: [Oracle JDK Downloads](https://www.oracle.com/java/technologies/javase-downloads.html)  
- Choose the latest **JDK (e.g., 21 or 17)**  
- Download **Windows x64 Installer (.exe)**  

### 2️⃣ Install JDK
- Run the `.exe` file → follow setup wizard (default settings are fine)  
- Installs to: `C:\Program Files\Java\jdk-XX`  

### 3️⃣ Set Environment Variables (Optional but Recommended)
- Search **Environment Variables** in Start Menu  
- Under **System Variables → Path → Edit → New**  
- Add:C:\Program Files\Java\jdk-XX\bin


### 4️⃣ Verify Installation
Open **Command Prompt**:
```bash
java -version
javac -version
