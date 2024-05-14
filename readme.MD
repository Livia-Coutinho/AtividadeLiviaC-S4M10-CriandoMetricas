# Programação - Semana 04
## Relatório: Criando métricas

### Aluna: Livia Coutinho

</br>

# Resumo da tecnologia:
A tecnologia principal abordada nesta atividade, cujo tutorial etsá disponível através do link https://learn.microsoft.com/pt-br/dotnet/core/diagnostics/metrics-instrumentation,  é a API de métricas disponível no namespace `System.Diagnostics.Metrics`. Essa API foi introduzida para oferecer uma maneira padronizada e eficiente de instrumentar e coletar métricas em aplicativos .NET. Com a API de métricas, os desenvolvedores podem monitorar diversos aspectos do desempenho de suas aplicações, como contadores, cronômetros, medidores e gauges.

# Conceitos aprendidos:
- **Instrumentação de aplicativos:** refere-se ao processo de adicionar pontos de monitoramento em um aplicativo para coletar dados sobre seu comportamento e desempenho. A API de métricas facilita a instrumentação de aplicativos .NET, permitindo que os desenvolvedores adicionem contadores, medidores, cronômetros e gauges para monitorar diferentes aspectos do aplicativo.

- **Métricas personalizadas:** além das métricas padrão fornecidas pela API, os devs também podem criar suas próprias métricas personalizadas para monitorar aspectos específicos de seus aplicativos. Isso é feito criando instâncias de `ObservableCounter` e `ObservableGauge` e registrando-as com um `Meter`.

- **Coleta de métricas:** uma vez que as métricas estão instrumentadas em um aplicativo, elas precisam ser coletadas e processadas para análise. Isso é feito usando um `MetricCollector`, que pode ser configurado para registrar e verificar as medições de instrumentos específicos.

- **Testes de métricas:** para garantir que as métricas estejam sendo coletadas e registradas de forma certa, é importante testá-las. Os testes de métricas podem ser realizados tanto com injeção de dependência quanto sem ela, e os resultados podem ser verificados usando um `MetricCollector`.

# Conclusão:

A atividade de programação da semana 4 do módulo 10, de introdução à coleta de métricas em aplicações .NET, proporciona uma compreensão sobre o monitoramento e análise do desempenho de aplicativos usando a API de métricas fornecida pelo namespace `System.Diagnostics.Metrics`. Através da instrumentação de aplicativos, criação de métricas personalizadas e coleta de métricas, quem está desenvolvendo pode obter insights úteis sobre o comportamento de seus aplicativos e identificar áreas para melhorias de desempenho.

# Passo a passo

### Step 1: Preparação do ambiente

- Começar instalando o SDK do .NET Core 6 ou uma versão mais recente, caso ainda não o tenha feito. 
- Certificar-se de ter acesso a uma linha de comando (CLI) para executar os comandos do .NET.

# Prints da realização da atividade

####
