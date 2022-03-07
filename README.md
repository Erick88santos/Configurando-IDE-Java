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


## ​ 4.2 Copie o caminho que aparecerá no terminal, no meu caso:

/usr/lib/jvm/java-11-openjdk-amd64/bin/java

## ​ 4.3 Vamos editar o arquivo .bashrc:

sudo gedit ~/.bashrc

## ​ 4.4 Copie o código abaixo e cole no final do arquivo .bashrc.

# ​ IMPORTANTE: cuidado para não alterar nada no arquivo além de apenas colar no final do mesmo o que vou te disponibilizar a seguir.

## ​ JAVA_HOME = aqui você coloca o caminho do tópico 4.2, tirando o /bin/java

JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
export JAVA_HOME
export PATH=$PATH:$JAVA_HOME

## ​ 4.3 Salve o arquivo

## ​ 4.4 Vamos conferir se a alteração ficou salva:

cat ~/.bashrc
# Feche o terminal e abra novamente

small_orange_diamond6. Vamos conferir mais uma vez se o Java está instalado na nossa máquina

java --version


