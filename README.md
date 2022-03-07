# ​ Configurando-IDE-Java
Diversos modos de configurações de IDE java em ambientes diferentes

# ​ Pré-requisitos
 Possuir conta no github
 Sistema Operacional (Windows/Linux)

# ​ Instalação/Configuração do Java
 Um pouco da história do Java
 Diferença entre JRE e JDK
 Versões do Java
 Se não existisse IDE?

# ​ Ubuntu
 Instalação OpenJDK
 Configuração de variável de ambiente
 Instalação do Eclipse
 Configurando o ícone no Dock
 Instalação do IntelliJ

# ​ Windows
 Instalação OpenJDK
 Configuração de variável de ambiente
 Instalação do Eclipse
 Instalação do IntelliJ

# ​ IntelliJ 
 Diferenças entre versões
 Conhecendo um pouco por dentro da IDE
 Criando seu primeiro projeto Java no IntelliJ
 Atalhos e Produtividade
 Conectar seu projeto no GitHub

# ​ Eclipse 
 Diferenças entre versões
 Conhecendo um pouco por dentro da IDE
 Criando seu primeiro projeto Java no IntelliJ
 Atalhos e Produtividade
 Conectar seu projeto no GitHub

# Outras Alternativas 
# Visual Studio Code

# Linux
## Instalação openJDK

### ​  O OpenJDK (Kit de Desenvolvimento Java Aberto) é uma implementação gratuita e de código aberto da linguagem de programação Java. A implementação está licenciada sob a GNU General Public License (GPL) com uma exceção de vinculação. JDK = JRE + JVM

## ​ 1. Abra o terminal e vamos verificar se temos o Java instalado:

java -version

## ​ 2. Para instalar o openJDK-13, digite no terminal: A versão mais atual LTS é do Java 11, que terá seu suporte estendido até Setembro de 2022. Este tipo de suporte iniciou no Java 8 que será mantido até 2023.

sudo apt-get install openjdk-13-jdk

## ​ 3. Confirme se realmente foi instalado com sucesso:

java -version

## 4. Vamos configurar o ambiente JAVA_HOME:

## ​ 4.1 Verificar o caminho da instalação do Java:

sudo update-alternatives --config java



