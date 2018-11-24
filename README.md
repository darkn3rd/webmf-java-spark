# SparkJava

Maven makes Java easier, and Java is easy.  *Rolls eyes*

## Installing

### Mac OS X

```bash
brew install maven
unset M2_HOME
mvn compile
mvn package
```

### Ubuntu

```bash
sudo apt-get install -y openjdk-9-jre-headless maven
export JAVA_HOME=/usr/lib/jvm/java-1.9.0-openjdk-amd64
mvn compile
mvn package
```

## Running

```bash
$ mvn exec:java -Dexec.mainClass="com.mycompany.app.App"
```

## Testing

```bash
curl http://127.0.0.1:4567/
curl http://127.0.0.1:4567/hello
curl http://127.0.0.1:4567/hello/James
```
