# SFTool releases

Публичная витрина релизов **SFTool** (Shadow Fight Tool) — собранные и
подписанные APK, автоматически публикуемые из приватного репозитория
[`lharmonie07/myapp`](https://github.com/lharmonie07/myapp).

Здесь нет исходного кода и ключей — только готовые к установке файлы.

Обновления публикуются не через GitHub Releases, а обычными файлами прямо в
репозитории:

- [`latest.json`](latest.json) — манифест (`versionCode`, `versionName`,
  `apkUrl`, `notes`);
- [`releases/sftool-latest.apk`](releases/sftool-latest.apk) — сам APK,
  подписанный стабильным release-ключом, поэтому ставится поверх
  предыдущей установленной версии.

Оба файла отдаются без авторизации через `raw.githubusercontent.com` —
именно так приложение (`UpdateChecker.kt`) проверяет и скачивает
обновления. Скачать APK напрямую можно и вручную по ссылке выше.
