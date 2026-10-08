# Easy Aurum — Privacy Policy

Last updated: 8 October 2026

Contact: crypto.rider86@gmail.com

## Summary

Easy Aurum is a local-first finance app. The developer does not run any server that receives your data, does not create accounts, and does not collect analytics, advertising identifiers or crash reports. Your financial data stays on your device.

## Data stored on your device

Accounts, transactions, budgets, goals, rules and connection settings are stored in an encrypted database (SQLCipher) in the app's container on your iPhone. The encryption key is derived from a root secret kept in the iOS Keychain. The same root secret can be restored from your 24-word recovery phrase. The phrase is shown to you once and is never sent anywhere. If you lose both the device and the phrase, the developer cannot recover your data.

Backup files (.eabackup) are created only when you ask for one. They are encrypted with the same root secret. API keys of connections are included in a backup only if you switch that option on.

## Data the app sends over the network

The app contacts third-party services directly from your device. The developer does not see these requests. Each service sees your IP address, the time of the request and the data needed to answer it:

- Exchange rates: Frankfurter (European Central Bank rates), Bank of Russia (cbr.ru) and CoinGecko. Requests contain currency or coin codes, not your balances.
- Public blockchain data, only if you add a wallet connection: mempool.space (Bitcoin), public RPC nodes and Blockscout (Ethereum and other EVM networks), Solana RPC, toncenter (TON), Aptos indexer. Requests contain the public wallet address you entered. If you enter your own Alchemy key or your own node address, requests go there instead.
- Brokers and exchanges, only if you add them: T-Bank (T-Invest), Finam and Binance. The app sends the read-only key you entered to that provider only. The app refuses keys that can trade or withdraw.
- NFT images are loaded only after you tap "Show images". The image host then sees your IP address.
- Optional private sync, only if you enter a sync server address: the server receives encrypted blocks it cannot read, plus a vault identifier derived from your key, packet sizes, timestamps and your IP address. No sync server is built into the app and none is used unless you configure one.

The app does not trade, send or withdraw funds, and never asks for seed phrases or private keys of wallets.

## What we do not collect

No name, e-mail, phone number, location, contacts, photos, advertising identifier, analytics or tracking data. The app does not track you across other companies' apps or websites.

## Sharing and retention

The developer does not receive your data, so there is nothing to share or retain. Third-party providers listed above handle requests under their own policies. Deleting the app deletes the local database. Deleting a connection erases its stored key.

## Beta testing

Builds are distributed through Apple TestFlight. Apple may collect crash and feedback data you choose to send through TestFlight, under Apple's privacy policy.

## Children

The app is not directed at children under 13.

## Changes

If this policy changes, the date above changes and the new text is published at the same address.

---

# Easy Aurum — Политика конфиденциальности

Обновлено: 8 октября 2026

Контакт: crypto.rider86@gmail.com

## Кратко

Easy Aurum хранит данные на вашем устройстве. У разработчика нет сервера, который получает ваши данные, нет аккаунтов, аналитики, рекламных идентификаторов и отчётов о сбоях. Если вы потеряете и телефон, и 24 слова, разработчик не сможет восстановить данные.

## Что хранится на устройстве

Счета, операции, бюджеты, цели, правила и настройки подключений лежат в зашифрованной базе (SQLCipher). Ключ выводится из корневого секрета в Keychain iOS; тот же секрет восстанавливается из 24 слов. Слова показываются один раз и никуда не отправляются. Резервная копия .eabackup создаётся только по вашей команде и шифруется. Ключи подключений попадают в неё, только если вы включите этот переключатель.

## Что приложение отправляет в сеть

Запросы идут с вашего устройства напрямую к сторонним сервисам; разработчик их не видит. Сервис видит ваш IP, время и данные запроса.

- Курсы: Frankfurter (курсы ЕЦБ), Банк России, CoinGecko. В запросах коды валют и монет, не ваши остатки.
- Блокчейны, только если вы добавили кошелёк: mempool.space, публичные RPC и Blockscout, Solana RPC, toncenter, индексер Aptos. В запросах публичный адрес, который вы ввели. С вашим ключом Alchemy или своим узлом запросы идут туда.
- Брокеры и биржи, только если вы их добавили: Т-Банк, Финам, Binance. Ключ «только чтение» уходит только этому провайдеру. Ключи с правом торговли и вывода приложение отклоняет.
- Картинки NFT загружаются только после нажатия «Показать изображения»; сервер картинок видит ваш IP.
- Необязательная приватная синхронизация, только если вы указали адрес сервера: он получает зашифрованные блоки, которые не может прочитать, а также идентификатор хранилища, размеры, время пакетов и IP. Встроенного сервера нет.

Приложение не торгует, не переводит и не выводит средства и не запрашивает seed-фразы и приватные ключи кошельков.

## Что мы не собираем

Имя, e-mail, телефон, геолокацию, контакты, фото, рекламный идентификатор, аналитику и данные для отслеживания.

## Тестирование

Сборки распространяются через Apple TestFlight. Данные о сбоях и отзывы, которые вы отправляете через TestFlight, обрабатывает Apple по своей политике.

## Дети

Приложение не предназначено для детей младше 13 лет.
