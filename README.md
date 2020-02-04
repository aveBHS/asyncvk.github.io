![vkbee](https://github.com/asyncvk/vkbee/blob/master/vkbee/bgtio.png?raw=true)
### Документация
## Вызов запросов к ВКидерасте
```python
await vkbee.VkApi.call(vk,'status.get',{'status':'VKBee is fastest!','group_id':1}
```
## Параметры

| Параметр | Описание |
| -------- | ---------|
| 1 | Ваш авторизованный аккаунт в модуле      |
## Connectivity

```python
import asyncio
loop = asyncio.get_event_loop()
vk = vkbee.VkApi('token', loop=loop)
```

## BotsLongPoll
# Oh wait plz!
