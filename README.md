Часть работающей системы по автоматизации работы с заявками.

Исходные данные: в общий список попадают заявки от пользователей на кредит, по несколько тысяч в день (модель Request).

Задача: автоматизировать рабочее место сотрудника (около 150-200 человек) для работы с заявками:
* Возможность взять заявку в работу только одному человеку;
* После обработки (обзвон из браузера с логированием) движение заявки по шагам (статусам модели Process)
* Завершение работы по заявке, заявка пропадает из общего списка, сотрудник получает следующую;
* Разные сотрудники могут работать с разными заявками (по конкретным критериям фильтрации модели Request)