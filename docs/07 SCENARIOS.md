# Бизнес-сценарии

## 1. Регистрация и вход в систему.
Пользователь скачал приложение и открыл его впервые

* Пользователь выбирает "Регистрация".
* Пользователь вводит свои данные (имя, email, пароль).
* Система проверяет корректность данных и отправляет email с подтверждением.
* Пользователь переходит по ссылке в email для завершения регистрации.
* Система подтверждает регистрацию и направляет пользователя на экран профиля.
* Если email уже зарегистрирован, система предлагает войти или восстановить пароль.
* Если подтверждение email не завершено в течение 24 часов, система отправляет напоминание.
* Если проблемы с доставкой email. Добавить возможность подтверждения через SMS.

## 2. Создание тренировочного плана
Пользователь авторизован в системе

* Пользователь переходит в раздел "Тренировки".
* Пользователь выбирает опцию "Создать план".
* Пользователь указывает параметры (цель, уровень подготовки, доступное время).
* Система предлагает шаблон плана на основе введенных данных.
* Пользователь редактирует план, добавляя или удаляя упражнения.
* Пользователь сохраняет план.
* Если пользователь не указывает параметры, система предлагает стандартный план для новичков.
* для точной персонализации, система должна предлагать анкету для уточнения физических данных.

## 3. Запись тренировки
Пользователь авторизован в системе, тренировка завершена.
 
* Пользователь переходит в раздел "Тренировки" или "Дневник тренировок".
* Пользователь выбирает опцию "Добавить тренировку".
* Пользователь вводит данные вручную (длительность, тип активности, количество подходов, вес, самочувствие) или синхронизирует данные с фитнес-трекера.
* Система сохраняет данные и обновляет статистику в разделе "Прогресс".
* Пользователь может добавить заметки или фото для мотивации.
* Если синхронизация с трекером не удалась, система предлагает ввести данные вручную.
* реализованна проверка данных на реалистичность.
* есть возможность отредактировать данные тренировки в случае ошибки.


## 4. Отслеживание прогресса
Пользователь авторизован в системе

* Пользователь переходит в раздел "Прогресс".
* Система отображает статистику (количество тренировок, сожженные калории, изменения веса).
* Пользователь выбирает временной интервал для анализа (неделя, месяц, год).
* Система обновляет графики и данные.
* Так же предусмотрено локальное хранение данных с последующей синхронизацией в системе.

## 5. Консультация с тренером
 Пользователь получает персональную консультацию от тренера через приложение.
 
* Пользователь переходит в раздел "Тренеры".
* Пользователь выбирает тренера на основе профиля (опыт, специализация, отзывы).
* Пользователь отправляет запрос на консультацию, указывая тему (например, корректировка плана).
* Тренер получает уведомление и подтверждает запрос.
* Пользователь и тренер проводят консультацию через встроенный чат или видеозвонок.
* После консультации пользователь оставляет отзыв о тренере.
* Если тренер не отвечает в течение 48 часов, система предлагает выбрать другого тренера.
* предусмотрены уведомления тренерам и бонусы за активность для увеличения вовлеченности.
 
## 6. Создание группы
Пользователь авторизован в системе
 
* Пользователь переходит в раздел "Сообщество" или "Группы".
* Пользователь выбирает "Создать группу".
* Пользователь вводит название группы, описание и выбирает настройки приватности (открытая, закрытая).
* Система создает группу и назначает пользователя администратором.
* Пользователь приглашает других пользователей присоединиться через ссылку или поиск в приложении.
* Участники принимают приглашение и становятся членами группы.
* Если пользователь не принимает приглашение в течение 7 дней, система отправляет напоминание.
* Если группа закрытая, администратор должен одобрить заявки на вступление.
* В случае конфликта между участниками группы есть возможность блокировки участниками друг друга.


## 7. Обмен сообщениями
Пользователь авторизован в системе.

* Пользователь переходит в раздел "Сообщения" или открывает чат из профиля другого пользователя/тренера.
* Пользователь пишет текстовое сообщение, при необходимости прикрепляет фото или видео (например, технику упражнения).
* Система отправляет сообщение получателю.
* Получатель получает уведомление о новом сообщении.
* Получатель отвечает, и чат обновляется в реальном времени.
* Если получатель не в сети, сообщение сохраняется и доставляется после входа в приложение.
* Если сообщение содержит запрещенный контент, система автоматически фильтрует его и отправляет предупреждение отправителю.
* Все сообщения передаются в зашифрованном виде.
 
## 8. Уведомление о замене экипировки

Пользователь авторизован, ранее указал данные об экипировке (например, кроссовки, дата покупки, пробег)
 
* Пользователь добавляет информацию о своей экипировке в разделе "Настройки/Экипировка".
* Система отслеживает использование экипировки на основе данных о тренировках (например, пройденное расстояние для кроссовок).
* При достижении заданного срока или уровня износа (например, 500 км для кроссовок) система отправляет уведомление о необходимости замены.
* Пользователь получает уведомление с рекомендацией и, при наличии, предложением  магазина для покупки.
* Пользователь подтверждает замену или откладывает уведомление на определенный срок.
* Если пользователь не добавлял данные об экипировке, система предлагает сделать это при следующем входе в раздел тренировок.
* Система использует общие рекомендации производителей об износе и позволяет пользователю корректировать параметры износа.
 
## 9. Интеграция с устройствами
Пользователь подключает фитнес устройства к системе для получения данных о пульсе, дистанции.

* Пользователь переходит в раздел "Настройки/Интеграции".
* Пользователь выбирает тип устройства или приложение.
* Система запрашивает разрешение на доступ к данным.
* После подтверждения данные (шаги, пульс, калории) синхронизируются с приложением.
* Пользователь видит обновленные данные в разделе "Прогресс". 
* Если синхронизация не удается, система предлагает проверить подключение или повторить попытку позже.
 
