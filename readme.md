
Основные аннотациии методов контролера, использующих
websocket

| Аннотация              | Что делает                   |
| ---------------------- | ---------------------------- |
| `@MessageMapping`      | endpoint для STOMP сообщений |
| `@SendTo`              | broadcast сообщение          |
| `@SendToUser`          | персональное сообщение       |
| `@Payload`             | тело сообщения               |
| `@Header`              | получить header              |
| `@Headers`             | получить все headers         |
| `@DestinationVariable` | параметры destination        |

Для тестирования в postman в глобальном окружении
нужно объявить null_char через команду: pm.globals.set("NULL_CHAR", '\0')