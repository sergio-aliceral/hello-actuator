# Objetivo
API actuator com Spring Boot.

## Iniciando

- `git clone https://github.com/sergio-aliceral/hello-actuator.git`
- `cd hello-actuator`

## Pré-requisitos
- `mvn --version`<br>

Você deverá ver a indicação da versão do Maven instalada e a versão do JDK. Observe que o JDK é obrigatório, assim como a definição das variáveis de ambiente **JAVA_HOME** e **M2_HOME**.

## Limpar, compilar e empacotar
- `mvn clean install`<br>

Gera arquivo _hello-actuator-1.0.0.jar_ no diretório _target_.

## Executando a aplicação
- `java -jar target/hello-actuator-1.0.0.jar`<br>

Executa o aplicativo por meio do arquivo jar criado pelo comando `mvn clean install`, conforme comentado anteriormente.

### Endpoints

- Lista todos os serviços: `GET` http://localhost:8080/actuator
