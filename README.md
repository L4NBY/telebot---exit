# telebot---exit
Quando o usuário sair do grupo telebot 


```
@bot.message_handler(func=lambda m: True, content_types=['left_chat_member'])
def remove_member(message):
    bot.reply_to(message, 'Tchau seu corno  ' + str(message.left_chat_member.first_name))
```
