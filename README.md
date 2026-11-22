# AEGIS Plugin (Paper / Purpur 1.21.11, Java 21)

## Сборка плагина
1. Установите **JDK 21** и **Apache Maven 3.9+**.
2. В корне проекта выполните:
   ```bash
   mvn clean package
   ```
3. Готовый JAR-файл появится в `target/AEGIS-1.0.0.jar`.

## Установка на сервер
1. Поместите `AEGIS-1.0.0.jar` в папку `plugins/`.
2. Запустите сервер — плагин автоматически создаст все 11 конфигураций и сгенерирует ресурспаки `plugins/AEGIS/packs/legendary.zip` и `plugins/AEGIS/packs/cosmetic.zip`.
