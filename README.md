TNTPlus - бесплатный плагин с открытым исходным кодом, который будет включать в себя полезные фишки, 1 из них продемонстрирована на видео. 

видео - https://www.youtube.com/watch?v=38DQiCughUA

*Все плагины TNTPlugins будут поддерживать формат таких уведомлений 

MessageManager:

Say(UnturnedPlayer player, string text) - чат игровой с поддержкой Rich
Send(UnturnedPlayer player, string text, EMessageType eMessageType) - отправка сообщений как на видео.

Доступные типы сообщений 
1. Unknown - обычная чёрная панель
2. Error
3. Succes 
4. Notification 
5. Warning 

UpdateManager:

UpdateManager.OnSecondTick += UpdateManager_OnSecondTick; -  ивент который вызывается каждую секунду

Далее потихоньку буду что добавлять/изменять, пока сделал набросок.
(предложения свои можете написать в группу или оставить комментарий)

Скорее всего будете переделана структура уведомлений, сделаю возможность указать время до исчезновения каждого типа.

Если необходимо добавлю отдельную плавную анимацию исчезновения сообщения.

- С уважением TNTPlugins!
