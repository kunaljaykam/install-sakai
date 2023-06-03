# Install Sakai

One Click Dev Setup, you can try on GitPod. 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Sakai-Codespace/sakai)

<table>
  <tr>
    <th style="width:33%;">MacOS</th>
    <th style="width:33%;">Windows</th>
    <th style="width:33%;">Linux (Ubuntu)</th>
  </tr>
  <tr>
    <td>1. Ensure you have Java Development Kit (JDK) installed. For MacOS, use Homebrew and install it via: <br> <code>brew install openjdk@11</code></td>
    <td>1. Ensure you have Java Development Kit (JDK) installed. You can download it from the <a href="https://www.oracle.com/java/technologies/javase-jdk11-downloads.html">Oracle website</a>.</td>
    <td>1. Ensure you have Java Development Kit (JDK) installed. On Ubuntu, use apt-get: <br> <code>sudo apt-get install openjdk-11-jdk</code></td>
  </tr>
  <tr>
    <td>2. Install Maven. Again, you can use Homebrew: <br> <code>brew install maven</code></td>
    <td>2. Install Maven. Download it from the <a href="https://maven.apache.org/download.cgi">Maven website</a> and follow the installation instructions.</td>
    <td>2. Install Maven: <br> <code>sudo apt-get install maven</code></td>
  </tr>
  <tr>
    <td>3. Download the Sakai source code from Github: <br> <code>git clone https://github.com/sakaiproject/sakai.git</code></td>
    <td>3. Download the Sakai source code from Github. You can use <a href="https://gitforwindows.org/">Git for Windows</a> and use the same command as MacOS.</td>
    <td>3. Download the Sakai source code from Github: <br> <code>git clone https://github.com/sakaiproject/sakai.git</code></td>
  </tr>
  <tr>
    <td>4. Navigate to the directory: <br> <code>cd sakai</code></td>
    <td>4. Navigate to the directory with command prompt: <br> <code>cd sakai</code></td>
    <td>4. Navigate to the directory: <br> <code>cd sakai</code></td>
  </tr>
  <tr>
    <td>5. Compile Sakai with Maven: <br> <code>mvn clean install sakai:deploy</code></td>
    <td>5. Compile Sakai with Maven: <br> <code>mvn clean install sakai:deploy</code></td>
    <td>5. Compile Sakai with Maven: <br> <code>mvn clean install sakai:deploy</code></td>
  </tr>
</table>

