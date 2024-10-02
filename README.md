# Ponderada Semana 8

## Integração de Telemetria com Go e Signoz baseado no TDD

A telemetria é uma ferramenta essencial para monitorar o comportamento de sistemas em produção, acompanhando métricas, rastreamentos e eventos em tempo real. Ela pode ser usada juntamente com o TDD para verificar a eficiência e qualidade do código em tempo de execução.

O Signoz é uma ferramenta de telemetria que pode ser integrada facilmente com aplicações Go para monitorar métricas como CPU, memória e latência. Neste repositorio irei demonstrar como podemos usar telemetria em uma aplicação Go com Signoz (baseado no tutorial do card da atividade).

## Como Usar Signoz com Go

### Passo 1: Clonar o Repositório do Signoz

![image](/imgs/i0.png)

### Passo 2: Clonar o Repositório de Exemplo

![image](/imgs/i3.png)

### Estrutura do Repositório

```
/ponderada-s8
  └── sample-golang-app
  └── signoz
  └── README.md
```

### Passo 3: Iniciar o Signoz

Siga as instruções da documentação do Signoz para iniciar o Signoz no ambiente.

### Passo 4: Instalar Dependências

```bash
go mod tidy
```

### Passo 5: Verificar Scripts de Telemetria

Verifique se o código inclui as configurações de telemetria adequadas (baseado no tutorial).

![image](/imgs/i4.png)

### Passo 6: Configurar Variáveis de Ambiente e Conectar

Defina as variáveis de ambiente para conectar o projeto ao Signoz (ex: localhost, portas e pacotes corretos)

![image](/imgs/i7.png)

Com isso, a configuração está completa. A aplicação Go agora está integrada ao Signoz e pronta para monitorar telemetria, permitindo o rastreamento de métricas em tempo real e a visualização de logs para melhorias de performance, respectivamente.
