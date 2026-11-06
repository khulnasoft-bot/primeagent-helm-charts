# primeagent IDE chart

Helm chart for primeagent as IDE with a persistent storage or an external database (for example PostgreSQL).


## Quick start

Install the chart:

```bash
helm repo add primeagent https://khulnasoft-bot.github.io/primeagent-helm-charts
helm repo update
helm install primeagent-ide primeagent/primeagent-ide -n primeagent --create-namespace
```


## Examples
See more examples in the [examples directory](https://github.com/khulnasoft-bot/primeagent-helm-charts/tree/main/examples/primeagent-ide).