1. Знания

2. Основная информация из уроков о хеше, логе, HEAD, статусах файлов и оформлении сообщений к коммитам.

3. Дополнить инфу про git log


## Как делать поток
```mermaid
data_flow
    A[init_subscription]
    A --> B[subscribe]
    B --> C[Pipe] --> D[map]
    D --> E[tap] --> F[console.log]
```
