import telebot
import time
bot = telebot.TeleBot("8128327778:AAHvEhM5ucdXT9bDcH1b2WIPawspuDcJ-YI",parse_mode=None)
@bot.message_handler(commands=['start'])
def send_welcome(message):
    bot.send_message(message.chat.id, "👨‍💻Приветствую, на связи Мухаметов Эрик. \n\n Я подготовил для тебя полноценное, бесплатное обучение по заработку через Ozon.\n\nРекомендую посмотреть все уроки до конца.\n\n Это полноценное обучение по Ozon, изучив которое ты сможешь начать работать и зарабатывать через Ozon.\n\nТак же в уроках ты найдешь информацию о том, как стать моим партнёром и зарабатывать вместе со мной.\n\nТак что, не откладывай на потом и приступай к изучению: https://drive.google.com/drive/folders/12Ylw0NuiliZ8yajyZoz8MPZj4a6XJBdV")
    time.sleep(10)  # Задержка на 2 дня в секундах
    bot.send_message(message.chat.id, "Привет, получилось изучить курс? \n\n Если у тебя есть вопросы касательно работы с Озон, то ты можешь написать мне и я с радостью отвечу на них🤝\n\n https://t.me/themukhametov")
    time.sleep(10)  # Задержка на 2 дня в секундах
    bot.send_message(message.chat.id, "Как получить результаты максимально быстро и увидеть первую прибыль через месяц.\n\n Прямо сейчас ты можешь изучить курс и двигаться самостоятельно.\n\n Либо, стать моим партнёром в формате личного менторства и работать вместе со мной. \n\n Каждого партнёра я довожу до конкретного результата. \n\n Совместный запуск магазина на Ozon: \n\n 1. запуск магазина с уже проверенными товарами, с рекомендациями по отгрузке каждого из них под ваш индивидуальный бюджет. \n\n 2. Налаженная логистика. Все товары уже лежат на складе нашего фул-Филмент, готовые к поставке. Для отгрузки товара вам нужно будет лишь создать заявку на поставку в личном кабинете Ozon Seller под нашим руководством. \n\n 3. Отточенный алгоритм действий, который приведет нас к фактическим продажам спустя 1.5-2 недели с момента старта сотрудничества. \n\n 4. Совместное создание карточек товара и изучение всех кнопок в личном кабинете.  В качестве куратора по всем моментам личного кабинета будет предоставлен один из действующих, опытных партнеров. Характеристики для карточек товаров будут предоставлены в виде скриншотов из настроек уже действующих, продающихся карточек. \n\n 5. Полноценная обратная связь как от меня, так и от кураторов, дизайнеров, сотрудников фф и тд. В наших общих интересах сделать так, чтобы у вас были хорошие продажи на маркетплейсе. \n\n  6. По необходимости лично занимаемся выкупами/созданием отзывов на ваши товары. \n\n 7. Гарантия лично от меня: после запуска всех процессов продажи точно будут. \n\n 8. Личное менторство бессрочное, после запуска совместное долгосрочное дружеское сотрудничество и развитие❤ \n\n️Довожу до фактического результата, далее расширяем ассортимент и магазин превращается в полноценный бизнес, приносящий очень хороший доход. Набираю партнеров для долгосрочного сотрудничества, во благо развития своего оптового направления.  Стоимость обучения 40.000₽. Для уточняющих вопросов можем созвониться и обговорить все детали) \n\n Для связи пишите в личку тг: https://t.me/themukhametov")
bot.polling(none_stop=True, interval=0)
