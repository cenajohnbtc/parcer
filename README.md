Скрипт main.py парсит адреса ваших кошельков в csv файле из этого дашборда Dune (активность только по нативным токенам): https://dune.com/queries/2464151/4052838
Скрипт native + stables дает на выбор 3 сценария: либо парсить csv по нативным токенам, либо сsv по стейблам, либо оба файла (они должны лежать у вас в папке с скриптом). Ссылка на скачивания csv: https://dune.com/queries/2350073/3847708

Как запустить скрипт:

1. Скачать содержимое репозитория

2. Скачать csv файл/ы по ссылке выше (кнопка Export to csv)

3. В wallets.txt добавить адреса своих кошельков: 1 строчка = 1 адрес

4. В main.py в 5 строке в скобках пишем название скаченного csv файла. В native + stables инсрукция начинается с 6 строки за #

5. Запускаем скрипт, в папке с main.py появится matched_wallets.xlsx с результами парсинга. При запуске native + stables 3 сценария, результаты по стейблам будут в последних столбцах

Наш канал в телеграмме: https://t.me/RRband