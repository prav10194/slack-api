#### Starter python code

```python
import slack

import ssl
ssl._create_default_https_context = ssl._create_unverified_context

client = slack.WebClient(token='<User_OAuth_Token>')
client.chat_postMessage(channel='<Channel_Name>', text='This is only a test.')
```
