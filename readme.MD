# Programação - Semana 04
## Relatório: Criando métricas

### Aluna: Livia Coutinho

</br>

# Resumo da tecnologia:
A tecnologia principal abordada nesta atividade, cujo tutorial etsá disponível através do link https://learn.microsoft.com/pt-br/dotnet/core/diagnostics/metrics-instrumentation,  é a API de métricas disponível no namespace `System.Diagnostics.Metrics`. Essa API foi introduzida para oferecer uma maneira padronizada e eficiente de instrumentar e coletar métricas em aplicativos .NET. Com a API de métricas, os desenvolvedores podem monitorar diversos aspectos do desempenho de suas aplicações, como contadores, cronômetros, medidores e gauges.

# Conceitos aprendidos:
- **Instrumentação de aplicativos:** refere-se ao processo de adicionar pontos de monitoramento em um aplicativo para coletar dados sobre seu comportamento e desempenho. A API de métricas facilita a instrumentação de aplicativos .NET, permitindo que os desenvolvedores adicionem contadores, medidores, cronômetros e gauges para monitorar diferentes aspectos do aplicativo.

- **Métricas personalizadas:** além das métricas padrão fornecidas pela API, os devs também podem criar suas próprias métricas personalizadas para monitorar aspectos específicos de seus aplicativos. Isso é feito criando instâncias de `ObservableCounter` e `ObservableGauge` e registrando-as com um `Meter`.
