# TelegramKeyboard
Создание клавиатуры для телеграм бота


```Java
//Клавиатура в 1 строку
new TelegramKeyboard().CreateSingleLineKeyboard(new String[]{"Button_text", "Callback"}, new String[]{"Button2_text", "Callback"}, new String[]{"Button3_text", "Callback"});

//Многострочная клавиатура.
//Максимум 2 клавиши на строку.
new TelegramKeyboard().CreateMultiLineKeyboard(new String[]{"Button_text", "Callback"}, new String[]{"Button2_text", "Callback"}, new String[]{"Button3_text", "Callback"});
```
