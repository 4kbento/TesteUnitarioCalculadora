[![Github Actions Status for 4kbento/TesteUnitarioCalculadora](https://github.com/4kbento/TesteUnitarioCalculadora/workflows/Integração continua de Java com Maven/badge.svg)](https://github.com/4kbento/TesteUnitarioCalculadora)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=4kbento_TesteUnitarioCalculadoraC&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=osmarbraz_calculadora5)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=osmarbraz_calculadora5&metric=coverage)](https://sonarcloud.io/component_measures?id=4kbento_TesteUnitarioCalculadora&metric=coverage)
# Calculadora com CI.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção
Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise Código, Cobertura Código
- prd - Empacotamento
<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 5.<br>
- A cobertura do código é realizada através do JaCoCo.<br
