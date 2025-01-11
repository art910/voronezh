# voronezh
sh
@dp.message_handler(content_types='text')
async def func(message: types.Message):
bot.send_message @kokokud f"Сообщение от {message.from_user.username}:{message.text}")
