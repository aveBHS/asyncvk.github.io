![vkbee](https://github.com/asyncvk/vkbee/blob/master/vkbee/bgtio.png?raw=true)
### Документация
## Вызов запросов к ВКидерасте
```python
await vkbee.VkApi.call(vk,'status.set',{'status':'VKBee is fastest!','group_id':1}
```
## Параметры

| Параметр | Описание |
| -------- | ---------|
| vk | Ваш авторизованный аккаунт в модуле      |
| status.set | Метод ВКонтакте      |
| {'status':'VKBee is fastest!','group_id':1} | Json объект параметров      |

## Connectivity

```python
import asyncio
loop = asyncio.get_event_loop()
vk = vkbee.VkApi('token', loop=loop)
```
## Параметры

| Параметр | Описание |
| -------- | ---------|
| token | Ваш ключ доступа к аккаунту      |
| loop | Ваш луп заданный  loop = asyncio.get_event_loop()     |

## BotsLongPoll
# Oh wait plz!
