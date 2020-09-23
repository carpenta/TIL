# Azure CLI snippets


### azure servicebus queue 내용 확인 (message count 확인)
```
az servicebus queue show \
    --resource-group learn-0172f928-50c1-4cb2-97cb-1b47fc3b0b9d \
    --name salesmessages \
    --query messageCount \
    --namespace-name <namespace-name>
```
