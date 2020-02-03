![vkbee](https://github.com/asyncvk/vkbee/blob/master/vkbee/bgtio.png?raw=true)
### Documentation
## Function API caller
```python
await vkbee.VkApi.call(vk,'status.get',{'status':'VKBee is fastest!','group_id':1}
```
## Connectivity
```python
import asyncio
loop = asyncio.get_event_loop()
vk = vkbee.VkApi('token', loop=loop)```
