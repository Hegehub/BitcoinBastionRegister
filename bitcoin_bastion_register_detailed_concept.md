# Bitcoin Bastion Register

## Подробный концепт проекта

**Bitcoin Bastion Register** — это суверенная Bitcoin-only кассовая система, торговый регистр и локальный commerce-node для бизнеса, который хочет принимать Bitcoin напрямую: через собственную Bitcoin/Lightning-инфраструктуру, локальную сеть, NFC, Bluetooth и offline-first процессы.

Проект не должен быть обычной “crypto-кассой”. Его основная идея — помочь торговцу не просто принимать BTC, а **жить и работать на Bitcoin rails**: со своей нодой, своими правилами, своими терминалами, своими чеками, своим treasury-контролем и своей локальной устойчивой торговой инфраструктурой.

---

## 1. Короткая формула

```text
Bitcoin Bastion Register
=
Bitcoin-only касса
+ Lightning terminal
+ on-chain BTC checkout
+ local Bitcoin/Lightning node commerce
+ offline-first торговый регистр
+ NFC / Bluetooth / local Wi-Fi payment transport
+ treasury console
+ privacy guard
+ merchant intelligence
+ circular Bitcoin economy infrastructure
```

---

## 2. Главная формулировка

**Bitcoin Bastion Register** — это Bitcoin-only суверенная кассовая система, торговый регистр и локальный commerce-node для приёма Lightning и on-chain BTC через собственную Bitcoin/Lightning-ноду, локальный Wi-Fi, NFC, Bluetooth и offline-first процессы, с treasury-контролем, privacy scoring, проверяемыми чеками, reconciliation и поддержкой circular Bitcoin economy.

Английская версия:

> **Bitcoin Bastion Register is a Bitcoin-only sovereign merchant register and local commerce node for Lightning and on-chain Bitcoin payments, designed to operate through merchant-owned Bitcoin infrastructure, local Wi-Fi, NFC, Bluetooth and offline-first workflows, with treasury controls, privacy scoring, verifiable receipts, reconciliation and circular Bitcoin economy support.**

---

## 3. Почему Register, а не POS

Аббревиатура **POS** в торговле означает *Point of Sale*, но в Bitcoin-среде она может ассоциироваться с **Proof of Stake**, что плохо для Bitcoin-maxi позиционирования.

Поэтому основной бренд:

```text
Bitcoin Bastion Register
```

Компоненты:

| Название | Смысл |
|---|---|
| **Bitcoin Bastion Register** | основной продукт |
| **Bastion Register Terminal** | кассирский интерфейс / планшет / телефон / PWA |
| **Bastion Register Box** | локальное устройство с нодой, Wi-Fi, Bluetooth, NFC |
| **Bastion Commerce Node** | продвинутая нодовая версия для бизнеса |
| **Bitcoin Bastion Register Sovereign+** | версия с отдельной укладкой USDT / XMR / ZEC |

---

## 4. Философия проекта

### 4.1. Bitcoin maximalism

Ядро проекта должно быть строго Bitcoin-only.

```text
Only Bitcoin
Only sats
Only Lightning
Only on-chain BTC
No altcoins in core
No stablecoins in core
No custodial balances
No private key storage
No exchange dependency
No token economy
```

Ключевой принцип:

> **Bitcoin is the money. Everything else is optional, isolated and non-core.**

---

### 4.2. Self-custody

Bitcoin Bastion Register не должен быть банком и не должен хранить деньги пользователя.

Правильная модель:

```text
Bastion Register
  ↓
Payment Adapter
  ↓
Merchant-owned infrastructure
  ↓
BTCPay / LND / Core Lightning / Bitcoin Core
  ↓
Merchant wallet / node / cold storage
```

Принцип:

```text
Register creates invoices.
Merchant node receives funds.
Owner controls keys.
System records, explains and audits operations.
```

Register может:

- создавать invoice;
- создавать payment request;
- отслеживать оплату;
- вести журнал продаж;
- выдавать чек;
- оценивать риски;
- предлагать treasury actions;
- создавать unsigned PSBT;
- логировать sensitive events.

Register не должен:

- хранить seed phrase;
- хранить private keys;
- держать custodial balance;
- автоматически отправлять BTC без approval;
- маскироваться под custodial wallet.

---

### 4.3. Anarcho-capitalist logic

С анархокапиталистической точки зрения проект ценен тем, что снижает зависимость бизнеса от:

- банков;
- карточных процессоров;
- custodial payment gateways;
- KYC-посредников;
- заморозки счетов;
- chargeback-механизмов;
- fiat rails;
- облачных SaaS-провайдеров;
- платёжной цензуры.

Правильное позиционирование:

> Инструмент добровольной торговли, прямого расчёта, самохостинга, приватности, устойчивости и денежного суверенитета.

Неправильное позиционирование:

> Касса для обхода закона.

---

### 4.4. Sovereignty-first commerce

Bitcoin Bastion Register должен помогать торговцу владеть:

```text
деньгами
ключами
платёжной инфраструктурой
кассовыми данными
отчётами
правилами
терминалами
ролями сотрудников
treasury-политикой
локальной торговой сетью
```

---

## 5. Продуктовая структура

```text
Bitcoin Bastion Register
│
├── Register Core
│   ├── продажи
│   ├── чеки
│   ├── смены
│   ├── роли
│   ├── терминалы
│   └── audit log
│
├── Bitcoin Payment Layer
│   ├── Lightning
│   ├── on-chain BTC
│   ├── BTCPay Server
│   ├── LND
│   ├── Core Lightning
│   └── Bitcoin Core
│
├── Sovereign Local Commerce Layer
│   ├── local Wi-Fi
│   ├── Bluetooth relay
│   ├── NFC tap-to-request
│   ├── local node mode
│   ├── mesh event mode
│   ├── offline sale records
│   └── reconciliation
│
├── Local Node Layer
│   ├── Bitcoin Core
│   ├── Lightning node
│   ├── node health
│   ├── mempool status
│   ├── local peer discovery
│   └── own-node verification
│
├── Treasury Layer
│   ├── hot wallet warnings
│   ├── cold storage planner
│   ├── PSBT workflow
│   ├── treasury policy
│   └── approval flows
│
├── Privacy Layer
│   ├── privacy score
│   ├── no-KYC merchant stack
│   ├── metadata minimization
│   ├── address reuse protection
│   └── Tor-first options
│
├── Merchant Intelligence Layer
│   ├── reports
│   ├── sovereignty score
│   ├── internet independence score
│   ├── lightning readiness score
│   ├── fee intelligence
│   └── operator recommendations
│
├── Circular Economy Layer
│   ├── merchant network
│   ├── local sats flow
│   ├── merchant-to-merchant payments
│   ├── Nostr identity
│   └── local economy dashboard
│
└── Optional Non-Bitcoin Settlement Layer
    ├── USDT module
    ├── XMR / Monero module
    └── ZEC / Zcash module
```

---

## 6. Основное отличие от обычной кассы

Обычная касса:

```text
Нет интернета — нет продаж.
```

Bitcoin Bastion Register:

```text
Нет интернета — переходим в суверенный локальный режим.
```

Обычный платёжный процессор:

```text
Нужен cloud, банк, API и разрешение посредника.
```

Bitcoin Bastion Register:

```text
Нужна твоя нода, твоя сеть, твои правила и твой риск-менеджмент.
```

---

## 7. Register Core

### 7.1. Продажи

Сущность `Sale`:

```text
sale_id
merchant_id
store_id
terminal_id
cashier_id
status
total_amount_sats
display_currency
display_amount
exchange_rate_snapshot
created_at
paid_at
cancelled_at
refunded_at
```

Статусы продажи:

```text
draft
pending_payment
payment_request_created
payment_request_transferred
pending_customer_action
pending_network_settlement
paid
seen_by_node
settled
expired
cancelled
partially_refunded
refunded
offline_pending
manual_pending
reconciled
rejected
```

---

### 7.2. Товары и услуги

MVP:

```text
custom amount
custom note
quick item buttons
basic categories
```

Дальше:

```text
Product
SKU
category
tax label
price fiat
price sats optional
inventory optional
stock reservation
```

---

### 7.3. Смены

Сущность `Shift`:

```text
shift_id
store_id
terminal_id
opened_by
opened_at
closed_by
closed_at
expected_revenue_sats
actual_paid_sats
expired_invoices_sats
refunded_sats
tips_sats
lightning_fees_sats
manual_adjustments
discrepancy_report
```

Пример закрытия смены:

```text
Total sales: 3,420,000 sats
Paid: 3,250,000 sats
Expired: 120,000 sats
Refunded: 50,000 sats
Lightning fees: 2,100 sats
Net received: 3,247,900 sats
```

---

### 7.4. Shift Integrity Seal

После закрытия смены система создаёт hash-снимок:

```text
shift_id
sale_ids
payment_ids
total_sats
opened_at
closed_at
cashier_id
terminal_id
hash
signature
```

Это делает журнал смен tamper-evident.

---

### 7.5. Роли

| Роль | Возможности |
|---|---|
| Cashier | создавать продажи, принимать оплату |
| Senior Cashier | мелкие возвраты, закрытие своей смены |
| Manager | смены, отчёты, возвраты |
| Owner | treasury, node settings, policies |
| Admin | системные настройки |
| Auditor | только просмотр отчётов и audit log |

---

### 7.6. Cashier Risk Limits

Пример:

```text
Cashier:
- max sale: 500,000 sats
- max refund: 50,000 sats
- cannot export reports
- cannot view treasury
- cannot change node settings
- cannot enable non-Bitcoin assets
```

---

### 7.7. Dual-Control Approvals

Для чувствительных действий нужно два подтверждения:

```text
enable USDT module
change cold storage destination
raise hot wallet limit
export full accounting data
create large refund
create PSBT above threshold
raise offline sale limits
enable emergency fallback mode
```

---

## 8. Bitcoin Payment Layer

### 8.1. Lightning Checkout

```text
Кассир вводит сумму
→ Register считает sats
→ создаёт Lightning invoice
→ показывает QR / NFC / Bluetooth / local URL
→ покупатель платит
→ Register получает settlement event
→ sale становится paid/settled
→ создаётся чек
→ событие попадает в audit log
```

---

### 8.2. On-chain BTC Checkout

Для крупных платежей:

```text
Кассир вводит сумму
→ Register создаёт Bitcoin address
→ показывает QR / NFC / printed code
→ следит за mempool
→ статус: seen / 1 confirmation / 3 confirmations / final
→ создаёт чек
→ связывает txid с продажей
```

---

### 8.3. Payment Rail Recommendation

Система рекомендует лучший rail:

```text
Small amount → Lightning
Medium amount → Lightning if liquidity ok
Large amount → on-chain
High mempool fees → Lightning preferred
Low inbound liquidity → on-chain fallback
```

Факторы:

```text
amount
inbound liquidity
mempool fees
store policy
product type
urgency
risk level
customer preference
connectivity status
```

---

### 8.4. Explainable Rail Choice

```text
Recommended: Lightning

Reason:
- amount is below policy threshold
- inbound liquidity is sufficient
- on-chain fee environment is high
- expected confirmation time is too long
```

---

### 8.5. Fiat Display, Sats Accounting

Цена может отображаться в fiat, но внутренняя логика должна быть Bitcoin-native.

```text
display_currency = EUR
settlement_asset = BTC
accounting_unit = sats
```

Пример:

```text
Coffee: €3.50
Amount: 5,812 sats
Payment: Lightning
```

В hardcore Bitcoin mode:

```text
Coffee: 6,000 sats
Meal: 28,000 sats
Ticket: 120,000 sats
```

---

## 9. Bitcoin Purity Mode

По умолчанию включён строгий Bitcoin-only режим.

```text
ONLY BITCOIN
NO ALTCOINS
NO STABLECOINS
NO CUSTODIAL BALANCES
NO PRIVATE KEY STORAGE
NO EXCHANGE CHECKOUT
NO TOKENIZED PAYMENT RAILS
```

Что запрещает:

```text
USDT
ETH
SOL
XRP
custodial checkout
exchange-hosted wallets
private key import
automatic exchange withdrawal
mixing BTC revenue with non-BTC assets
public API dependency if policy forbids it
```

---

## 10. Bitcoin-native Receipts

### 10.1. Структура чека

```text
Receipt ID
Sale ID
Amount sats
Fiat equivalent
Exchange rate source
Payment method
Lightning payment hash
Invoice ID
On-chain txid
Confirmation status
Cashier ID
Terminal ID
Timestamp
Merchant public key
Merchant signature
```

---

### 10.2. Merchant Signature

Каждый чек подписывается merchant signing key.

Важно:

```text
Этот ключ не связан с Bitcoin treasury keys.
Он нужен только для подписи чеков.
```

Данные подписи:

```text
sale_id
amount_sats
timestamp
terminal_id
payment_reference
merchant_public_key
signature
```

---

### 10.3. Offline-verifiable Receipt

Чек должен проверяться без cloud.

QR может содержать:

```text
receipt payload
merchant public key
signature
minimal verification metadata
```

Покупатель или аудитор может проверить:

```text
чек выпущен этим торговцем
сумма не изменена
timestamp не подделан
payment reference соответствует продаже
```

---

### 10.4. Local Receipt Verification

Локальная страница:

```text
http://bastion.local/verify
```

Показывает:

```text
Receipt signature: valid
Merchant: verified locally
Payment status: pending / settled / unknown
```

---

### 10.5. Orange-pill Receipt

Опциональный текст на чеке:

```text
Paid peer-to-peer with Bitcoin.
No bank intermediary.
No chargeback processor.
Final settlement in sats.
```

---

## 11. Sovereign Local Commerce Layer

Это центральный модуль проекта.

Главная идея:

> Bitcoin Bastion Register должен продолжать работать даже при отключении интернета, используя локальную сеть, собственную ноду, NFC, Bluetooth, offline records и последующую сверку.

---

### 11.1. Режимы связи

```text
1. Online Mode
2. Local Node Mode
3. Local Wi-Fi Mode
4. Bluetooth Relay Mode
5. NFC Tap-to-Request Mode
6. Local Mesh Mode
7. Emergency Receive Mode
8. Trusted Tab Mode
```

---

### 11.2. Online Mode

```text
Internet: yes
Local node: yes
Lightning routing: yes
Settlement: immediate
```

---

### 11.3. Local Node Mode

```text
Internet: degraded or unavailable
Local network: yes
Local node: yes
Settlement: depends on external connectivity
Sales records: yes
Invoices: yes
Receipts: yes
```

---

### 11.4. Local Mesh Mode

```text
Internet: no
Local Wi-Fi/Bluetooth: yes
Payment request transfer: yes
Final settlement: maybe later
Receipt: pending
```

---

### 11.5. Emergency Receive Mode

```text
Internet: no
Lightning: unavailable
Use pre-generated on-chain addresses
Mark sale as pending
Require manager approval
Warn about delayed settlement
```

---

### 11.6. Trusted Tab Mode

Для постоянных клиентов или закрытых сообществ:

```text
Customer receives goods now
Payment marked pending
Settlement required later
Risk limit applies
Merchant approves manually
```

Пример:

```text
Customer: Alice
Trusted limit: 300,000 sats
Open balance: 42,000 sats
Settlement due: today
```

---

## 12. Local Wi-Fi Node Mode

Самый реалистичный offline/degraded сценарий.

```text
Cashier Terminal
   ↓ local Wi-Fi
Bastion Register Box
   ↓ local network
BTCPay / LND / Core Lightning
   ↓
Bitcoin Core
```

Даже если внешний интернет пропал, система может:

```text
создавать локальные продажи
создавать payment requests
показывать QR
вести смену
печатать или показывать чеки
сохранять offline records
передавать данные по local Wi-Fi
синхронизироваться после восстановления связи
```

---

## 13. Собственная Lightning-нода как ядро

Это исключительная особенность проекта.

Bitcoin Bastion Register не просто подключается к внешнему Lightning API. Он должен уметь работать вокруг собственной Lightning-ноды торговца.

```text
Bastion Register
+ Bitcoin Core
+ Lightning node
  - LND или Core Lightning
+ BTCPay Server optional
+ local Wi-Fi access
+ local terminal discovery
+ local failover mode
```

Это делает Register не cloud cash register, не custodial payment terminal, не exchange checkout, а суверенной Bitcoin-кассой на собственной инфраструктуре.

---

### 13.1. Важная честность про Lightning offline

Если нет интернета, Lightning-нода может:

```text
создавать invoice
показывать invoice
хранить pending payment request
```

Но не всегда может:

```text
получить routed payment от внешнего клиента
подтвердить settlement
обновить channel state
связаться с peers
```

Поэтому UI должен жёстко различать:

```text
Invoice created
```

и:

```text
Payment settled
```

---

## 14. Local Wi-Fi Payment Page

Bastion Register Box может поднимать локальную страницу:

```text
http://bastion.local/pay/{sale_id}
```

или:

```text
http://register.local
```

Сценарий:

```text
Кассир создаёт продажу
→ терминал показывает QR с local URL
→ покупатель открывает локальную страницу
→ видит invoice / address / receipt
→ оплачивает через wallet
```

Полезно для:

```text
конференций
рынков
фестивалей
закрытых клубов
Bitcoin villages
circular economy communities
```

---

## 15. Bluetooth Payment Request Relay

Bluetooth используется не как settlement layer, а как local transport layer.

Что передаётся:

```text
Lightning invoice
BOLT12 offer
LNURL
on-chain address
receipt payload
pending sale proof
refund request
```

Принцип:

```text
Bluetooth ≠ payment settlement.
Bluetooth = transport for payment data.
```

Сценарий:

```text
Register создаёт payment request
→ передаёт его покупателю через Bluetooth
→ покупатель получает invoice/address
→ если у покупателя есть интернет, он платит
→ если интернета нет, продажа остаётся pending
→ Register позже сверяет settlement
```

---

## 16. NFC Tap-to-Request

Не “tap-to-pay” в банковском смысле, а именно:

```text
NFC Tap-to-Request
```

Как работает:

```text
Покупатель прикладывает телефон
→ получает Lightning invoice / BOLT12 offer / LNURL / on-chain URI
→ подтверждает оплату в своём wallet
→ Register ждёт settlement
```

NFC payload:

```text
sale_id
amount
asset
payment request
expiry
nonce
merchant signature
```

NFC нельзя использовать для передачи:

```text
private keys
seed phrase
admin tokens
node credentials
treasury data
sensitive customer data
```

---

## 17. Payment Transport Layer

Нужно отдельно различать:

```text
payment asset
payment rail
payment transport
```

Payment Asset:

```text
BTC
USDT
XMR
ZEC
```

Payment Rail:

```text
Lightning
Bitcoin on-chain
Liquid
Monero network
Zcash shielded
```

Payment Transport:

```text
QR
NFC
Bluetooth
local Wi-Fi URL
internet URL
printed code
manual code
```

Примеры:

```text
Asset: BTC
Rail: Lightning
Transport: NFC

Asset: BTC
Rail: on-chain
Transport: QR

Asset: BTC
Rail: Lightning invoice
Transport: Bluetooth

Asset: BTC
Rail: on-chain fallback
Transport: printed QR
```

---

## 18. Bastion Register Box

Аппаратная версия проекта.

```text
mini PC / Raspberry Pi / industrial box
+ Bitcoin Core optional pruned node
+ Lightning node
+ BTCPay Server optional
+ Register backend
+ local Wi-Fi hotspot
+ Bluetooth
+ NFC module
+ encrypted local database
+ printer support
+ backup system
+ optional touchscreen
```

Назначение:

```text
магазин
кафе
рынок
конференция
private club
Bitcoin circular economy village
pop-up event
```

Главная особенность:

> Даже если интернет нестабилен, Bastion Register Box остаётся локальным центром торговли.

---

## 19. Local Commerce Kernel

Внутри Bastion Register Box должен быть локальный commerce kernel.

```text
Local Commerce Kernel:
- создаёт продажи
- создаёт payment requests
- управляет локальными терминалами
- хранит offline records
- подписывает чеки
- отслеживает node health
- управляет QR / NFC / Bluetooth / Wi-Fi transport
- делает reconciliation после восстановления сети
```

Это сердце offline-first архитектуры.

---

## 20. Local Peer Discovery

Для локальной сети:

```text
Register terminal discovers local node
Register terminal discovers local backend
customer app discovers local payment endpoint
manager dashboard discovers active terminals
```

Технические варианты:

```text
mDNS / Bonjour
local DNS
QR with local URL
Bluetooth advertisement
NFC tag
```

UX-пример:

```text
Detected local Bastion node:
bastion-register.local

Status: online
Lightning node: connected
Bitcoin Core: synced
```

---

## 21. Device Pairing и Terminal Trust

Bluetooth, NFC и локальные терминалы требуют строгой модели доверия.

Pairing flow:

```text
Owner opens pairing mode
→ terminal shows pairing code
→ Bastion Register Box confirms device
→ terminal receives limited certificate/token
→ terminal appears as trusted/limited/event-only
```

Terminal trust levels:

```text
owner terminal
manager terminal
cashier terminal
event terminal
guest display
revoked device
```

Local device certificate:

```text
terminal_id
public key
role
trust_level
expiry
allowed_modes
signed_by_owner_key
```

Short-lived offline permissions:

```text
Event terminal permission expires after 12 hours.
```

или:

```text
Cashier device can create offline sales only until 22:00.
```

---

## 22. Offline Address Pool

Для emergency on-chain режима можно заранее генерировать адреса.

Как работает:

```text
Owner prepares address pool
→ addresses encrypted locally
→ terminal can use next unused address
→ each address used once
→ system warns if pool is low
→ after internet returns, reconciliation starts
```

Правило:

```text
Address already used.
Generate another address or reconnect to node.
```

---

## 23. Emergency Kit

Перед событием или мероприятием Register может подготовить аварийный набор.

```text
Emergency Kit:
- pre-generated on-chain addresses
- pre-generated QR sheets
- encrypted address pool
- terminal pairing keys
- local Wi-Fi fallback credentials
- offline receipt templates
- manual receipt numbering
- recovery checklist
```

---

## 24. Offline Settlement Honesty Engine

Система должна честно различать:

```text
payment request transferred
```

и:

```text
payment settled
```

Пример предупреждения:

```text
Status: Pending, not settled.

Risk:
- merchant has not received final payment yet
- Lightning route cannot be verified while offline
- on-chain transaction may not be broadcast yet
```

---

## 25. Risk-based Offline Acceptance

Пример политики:

```yaml
offline:
  allow_offline_sales: true
  max_offline_sale_sats: 100000
  trusted_customer_limit_sats: 500000
  require_manager_above_sats: 250000
  allow_goods_release_before_settlement: false
```

То есть кофе можно продать с небольшим риском, а дорогой товар — нет.

---

## 26. Reconciliation Engine

После восстановления связи система всё сверяет.

Что делает reconciliation:

```text
проверяет pending invoices
проверяет on-chain addresses
проверяет mempool/confirmations
обновляет sale statuses
выявляет unpaid sales
выявляет expired invoices
выявляет address reuse risk
считает offline loss risk
создаёт report
```

Пример отчёта:

```text
Offline Reconciliation Report

Offline duration: 2h 14m
Sales created: 37
Payment requests transferred: 34
Settled after reconnect: 31
Still pending: 2
Failed/expired: 1
Manual review required: 3
```

---

## 27. Conflict Resolution Engine

При восстановлении связи могут быть конфликты:

```text
две кассы продали последний товар
два терминала использовали один fallback address
одна продажа paid, другая expired
курс устарел
чек выдан, settlement не пришёл
терминал создал offline sale после истечения разрешения
```

Нужен отдельный conflict module.

---

## 28. Connectivity Intelligence

Модуль оценки связи.

Отслеживает:

```text
internet status
local Wi-Fi status
Bluetooth status
NFC module status
Bitcoin Core status
Lightning node status
BTCPay status
Tor status
mempool freshness
node sync state
peer connectivity
terminal connectivity
power status
```

Пример:

```text
Connectivity Status:

Internet: down
Local Wi-Fi: active
Bastion Register Box: reachable
Bitcoin Core: reachable but stale
Lightning node: reachable
Lightning peers: disconnected
Bluetooth: active
NFC: active

Recommended mode:
Local Mesh Mode + pending settlement
```

---

## 29. Internet Independence Score

Новый индекс:

```text
Internet Independence Score: 87 / 100
```

Факторы:

```text
локальный сервер
локальная Bitcoin node
локальная Lightning node
local Wi-Fi
Bluetooth
NFC
offline address pool
local receipt verification
encrypted local database
reconciliation engine
отсутствие обязательного cloud
```

---

## 30. Local Node Priority Mode

Если у торговца есть собственная нода, Register должен отдавать ей приоритет.

```text
Priority:
1. local Bitcoin Core
2. local Lightning node
3. local BTCPay
4. Tor connection
5. fallback public provider only if policy allows
```

В Bitcoin-only режиме можно запретить public providers:

```yaml
bitcoin:
  require_local_node: true
  allow_public_mempool_provider: false
  allow_custodial_lightning_provider: false
```

---

## 31. Own Node Verification

Внутренняя проверка:

```text
Own Node Verified: yes/no
```

Проверяется:

```text
Bitcoin Core доступен локально
node synced
Lightning node доступна
invoices создаются через собственную инфраструктуру
нет custodial payment processor
нет public API dependency
Tor активен, если включён
```

Пример:

```text
Own Node Sovereignty: 94 / 100

Strengths:
- Bitcoin Core local
- Core Lightning local
- BTCPay self-hosted
- Tor active

Weakness:
- public exchange rate provider used
```

---

## 32. Local Node Health Dashboard

```text
Bitcoin Core:
- reachable: yes
- synced: yes
- block height: 890,123
- mempool fresh: yes

Lightning Node:
- reachable: yes
- peers: 12
- channels: 8
- inbound liquidity: 3,200,000 sats
- outbound liquidity: 8,500,000 sats

Local Network:
- Wi-Fi: active
- Bluetooth: active
- NFC: active
- terminals connected: 4
```

---

## 33. Lightning Operations Layer

### 33.1. Lightning Liquidity Dashboard

```text
Inbound liquidity: 3,200,000 sats
Outbound liquidity: 8,500,000 sats
Largest receivable payment: 1,100,000 sats
Failed invoices last 24h: 3
Channel risk: medium
```

---

### 33.2. Lightning Readiness Score

Перед началом дня:

```text
Lightning Readiness: 86 / 100

Warnings:
- inbound liquidity may be low for large payments
- node uptime last 24h: 98.1%
- 2 failed invoices yesterday
```

---

### 33.3. Failed Payment Diagnosis

```text
Possible reasons:
- invoice expired
- insufficient inbound liquidity
- routing failure
- node offline
- payment timeout
- amount too large
- peer connectivity degraded
```

---

## 34. Invoice Intelligence

### 34.1. Умный Expiry

```text
Fast retail checkout: 5 minutes
Restaurant bill: 15 minutes
Online order: 30 minutes
Large invoice: custom expiry
Event mode: 3 minutes
```

---

### 34.2. Invoice Intent

```text
retail_fast
restaurant_table
online_order
donation
event_ticket
manual_invoice
supplier_payment
trusted_tab
offline_pending
```

---

## 35. Fee Intelligence

Показывает:

```text
current mempool fees
recommended fee rate
confirmation estimate
whether on-chain checkout is practical
sweep timing
UTXO consolidation window
```

Пример политики:

```yaml
fees:
  onchain_min_amount_sats: 1000000
  avoid_sweep_above_sat_vb: 25
  consolidate_utxos_below_sat_vb: 8
  require_manager_approval_if_fee_above_sats: 50000
```

---

## 36. Offline Exchange Rate Policy

Если интернет отключён, fiat-курс может устареть.

```yaml
exchange_rate:
  max_staleness_minutes: 30
  if_stale:
    - block_fiat_pricing
    - use_last_known_rate_with_warning
    - switch_to_sats_only
```

Лучший Bitcoin-maxi вариант:

```text
if fiat rate stale → switch to sats-only mode
```

Пример UI:

```text
EUR rate is stale.
Recommended: charge directly in sats.
```

---

## 37. Sats-only Offline Mode

Если нет интернета:

```text
Fiat conversion unavailable.
Switching to sats-only pricing.
```

Пример:

```text
Coffee: 6,000 sats
Meal: 28,000 sats
Ticket: 120,000 sats
```

---

## 38. Treasury Layer

### 38.1. Hot Wallet Exposure Warning

```text
Hot wallet balance: 42,000,000 sats
Policy limit: 20,000,000 sats
Risk: High

Recommendation:
Move 22,000,000 sats to cold storage.
```

---

### 38.2. Cold Storage Sweep Planner

```text
Sweep Plan:
- amount: 0.18 BTC
- destination: Vault 1
- priority: low
- suggested fee: 12 sat/vB
- PSBT required: yes
- approval required from: Owner
```

Принцип:

```text
Register recommends.
Owner approves.
Hardware wallet signs.
```

---

### 38.3. PSBT Workflow

```text
Create unsigned PSBT
→ owner reviews
→ hardware wallet signs
→ system records signed transaction
→ broadcast manually or through node
→ audit log updated
```

Register не должен хранить seed phrase или private keys.

---

### 38.4. Treasury Modes

```text
Conservative Mode:
- low hot wallet limit
- frequent cold sweeps
- no automated exchange

Growth Mode:
- hold more working BTC
- allow supplier payments
- allow channel liquidity operations

Event Mode:
- temporary higher hot wallet limit
- auto-reset policy after event

Emergency Mode:
- freeze outgoing treasury actions
- receive-only mode
```

---

## 39. Receive-only Safe Mode

Если есть подозрение на компрометацию:

```text
disable refunds
disable PSBT creation
disable treasury changes
allow only incoming payments
lock asset settings
notify owner
```

---

## 40. Policy-as-Code

Одна из центральных идей проекта.

Пример политики:

```yaml
treasury:
  hot_wallet_max_sats: 20000000
  cold_storage_sweep_day: sunday
  require_approval_above_sats: 5000000
  preferred_cold_storage_label: "Vault 1"

payments:
  prefer_lightning_below_sats: 10000000
  require_onchain_confirmations_above_sats: 50000000
  invoice_expiry_minutes: 10

privacy:
  forbid_address_reuse: true
  warn_if_public_node_alias_exposes_business: true

roles:
  cashier_max_refund_sats: 50000
  manager_max_refund_sats: 500000

offline:
  allow_offline_sales: true
  max_offline_sale_sats: 100000
  require_manager_above_sats: 250000
  allow_goods_release_before_settlement: false
```

---

### 40.1. Policy Simulator

Перед применением политики система показывает:

```text
This policy would have triggered:
- 3 treasury sweep warnings last week
- 2 manager approvals
- 1 on-chain payment confirmation warning
- 4 offline sale restrictions
- 0 blocked normal sales
```

---

## 41. Privacy Layer

### 41.1. Privacy Score

```text
Privacy Score: 78 / 100

Warnings:
- public node alias may expose business identity
- customer email collection enabled
- one fallback address was reused 3 times
```

Факторы:

```text
address reuse
xpub exposure
public node alias
invoice metadata leakage
hot wallet balance exposure
customer data retention
third-party analytics
Tor usage
node connectivity
on-chain clustering risk
fallback address reuse
Nostr public profile exposure
```

---

### 41.2. No-KYC Merchant Stack

Это не про незаконность, а про минимизацию лишних данных.

```text
No unnecessary customer profiles
No email required
No phone required
No third-party tracking
No behavioral analytics
No customer identity graph
```

Формулировка:

> **Minimal-data commerce for sovereign merchants.**

---

### 41.3. Privacy Presets

```text
Standard Privacy:
- normal receipts
- local reports
- basic node privacy warnings

High Privacy:
- no customer metadata
- Tor-first
- no public analytics
- address reuse blocking

Maximum Privacy:
- receive-only minimal logs
- no customer identifiers
- strict invoice metadata minimization
- local-only mode
```

---

### 41.4. Privacy Impact Preview

Перед включением функции:

```text
Enabling customer emails will reduce privacy score by 8 points.
Enabling public Nostr profile may reveal business payment endpoint.
Using fallback address repeatedly may reduce privacy score.
```

---

## 42. Merchant Intelligence Layer

### 42.1. Weekly Bitcoin Commerce Report

```text
Weekly Bitcoin Commerce Report

Revenue:
- 12,450,000 sats

Payment rails:
- 91% Lightning
- 9% on-chain

Operational issues:
- 4 expired invoices
- 2 failed Lightning payments
- 1 liquidity warning

Treasury:
- hot wallet above policy limit
- suggested sweep: 3,000,000 sats

Privacy:
- no address reuse detected
- node alias exposure: low

Sovereignty:
- score improved from 76 to 82
```

---

### 42.2. Business Continuity Report

```text
Node uptime: 99.2%
BTCPay webhook success: 98.9%
Failed invoice rate: 1.8%
Terminal sync health: good
Backup age: 14 hours
Tor connectivity: active
Offline readiness: medium
```

---

### 42.3. Operator Action List

Каждый отчёт должен завершаться действиями:

```text
Recommended actions:
1. Sweep 3,000,000 sats to cold storage.
2. Increase inbound liquidity before Saturday.
3. Rotate fallback address pool.
4. Review failed invoice pattern on Terminal 2.
5. Test backup restore before event mode.
```

---

## 43. Sovereignty Score

Оценивает:

```text
own Bitcoin node
own Lightning node
BTCPay self-hosted
Tor connectivity
cold storage policy
hot wallet limits
role-based access
audit logs
no address reuse
no third-party tracking
backup health
non-custodial setup
local Wi-Fi fallback
offline address pool
reconciliation engine
```

Пример:

```text
Sovereignty Score: 82 / 100

Strengths:
- self-hosted BTCPay
- Lightning enabled
- no custodial processor
- cold storage policy active

Weaknesses:
- public node alias exposes business
- no encrypted backup tested
- hot wallet above recommended threshold
```

Категории:

```text
Monetary Sovereignty
Operational Sovereignty
Infrastructure Sovereignty
Privacy Sovereignty
Treasury Sovereignty
Data Sovereignty
Connectivity Sovereignty
```

---

## 44. Proof-of-Sale Hash Chain

Каждая продажа включается в hash chain:

```text
sale_hash_n = hash(sale_data + previous_sale_hash)
```

Польза:

```text
нельзя незаметно удалить продажу
нельзя изменить сумму без нарушения цепочки
можно проверять integrity журнала
```

---

## 45. Optional Bitcoin Timestamping

Периодически можно якорить hash дневного отчёта:

```text
daily_report_hash → optional Bitcoin timestamp
```

Не нужно писать каждую продажу в блокчейн. Достаточно периодического proof.

---

## 46. Sovereign Backup Assistant

Система следит за backup hygiene:

```text
last backup: 14 hours ago
backup encrypted: yes
restore test: never
offsite backup: disabled
```

Рекомендация:

```text
Test restore before enabling high-volume event mode.
```

---

## 47. Node Dependency Map

Показывает зависимости:

```text
Register depends on:
- BTCPay Server
- Bitcoin Core
- LND / Core Lightning
- PostgreSQL
- Redis
- Tor
- local Wi-Fi router
- Bluetooth module
- NFC module
```

Если что-то падает:

```text
LND offline:
- Lightning checkout unavailable
- on-chain checkout still available
- sales can be recorded locally
```

---

## 48. Product Modes

### 48.1. Simple Register Mode

```text
Create sale
→ Show QR
→ Confirm payment
→ Receipt
```

---

### 48.2. Sovereign Merchant Mode

```text
Register
+ node monitoring
+ reports
+ treasury
+ privacy score
+ role system
+ policies
```

---

### 48.3. Event Mode

```text
temporary staff
multiple terminals
quick onboarding
daily settlement
offline fallback
event revenue report
limited permissions
short-lived terminal certificates
```

---

### 48.4. Circular Economy Mode

```text
merchant directory
local sats flow
community dashboard
merchant-to-merchant invoices
supplier payments in BTC
local economy analytics
```

---

### 48.5. Treasury Mode

```text
cold storage planning
hot wallet limits
PSBT workflows
approval flows
treasury policy checks
reserve reporting
```

---

### 48.6. Crisis / Disruption Commerce Mode

Осторожное позиционирование: не “обход закона”, а **business continuity under financial disruption**.

```text
low-bandwidth mode
Tor-first
minimal metadata
local-first records
receive-only fallback
manual reconciliation
```

---

### 48.7. Mesh Event Mode

Для больших мероприятий:

```text
Bastion Register Box создаёт локальную сеть
все терминалы подключены
торговцы могут иметь свои терминалы
покупатели получают payment request через QR/NFC/Bluetooth
всё пишется в local event ledger
после события делается reconciliation
```

---

### 48.8. No Cloud Commerce Demo Mode

Маркетинговый demo-режим:

```text
выключить интернет
подключиться к локальному Register Box
создать продажу
передать invoice через NFC
выдать offline-verifiable receipt
показать reconciliation позже
```

---

## 49. Circular Economy Layer

### 49.1. Bastion Merchant Network

```text
Merchant directory
Nostr merchant profile
LNURL / Lightning Address
public BTC-accepted badge
optional proof-of-payment reputation
merchant-to-merchant invoices
supplier payments
circular economy analytics
```

---

### 49.2. Bitcoin Village Dashboard

```text
Merchants active today: 18
Total sats circulated: 42,000,000
Lightning success rate: 98.4%
Top category: food & drinks
Merchant-to-merchant payments: 7
```

---

### 49.3. Nostr Integration

Опционально:

```text
Nostr merchant identity
Nostr Wallet Connect
merchant discovery
decentralized reputation
private merchant notifications
optional receipt proofs
```

Важно: Nostr-профиль может снижать приватность, поэтому должен быть optional.

---

### 49.4. Circular Economy Health Score

```text
Local Bitcoin Economy Health: 71 / 100

Factors:
- active merchants
- repeat BTC spending
- merchant-to-merchant payments
- local supplier payments
- Lightning success rate
- BTC retained locally
```

---

### 49.5. Merchant-to-Merchant Local Settlement

```text
Merchant A
→ supplier invoice
→ Merchant B pays through local node / Lightning / later settlement
```

Это развивает не только платежи “покупатель → продавец”, но и настоящую локальную Bitcoin-экономику.

---

### 49.6. Local Sats Flow Map

```text
Customer payments
Merchant revenue
Merchant-to-merchant payments
Supplier settlements
Treasury sweeps
```

Пример:

```text
Local Economy Today:
- 18 merchants active
- 42,000,000 sats circulated
- 7 merchant-to-merchant payments
- 63% sats retained locally
```

---

## 50. LNURL, Lightning Address, BOLT12

### 50.1. LNURL-pay

```text
static payment links
tip jars
donation mode
public merchant payment endpoint
```

---

### 50.2. Lightning Address

Пример:

```text
coffee@merchant.com
```

---

### 50.3. BOLT12 Offers

Архитектурно заложить:

```text
PaymentRequestType:
- lightning_invoice
- lnurl_pay
- bolt12_offer
- onchain_address
```

---

### 50.4. Payment Capability Discovery

Терминал должен знать:

```text
this merchant supports Lightning invoice
this merchant supports BOLT12
this merchant supports on-chain
this terminal is offline
this terminal can only create manual pending sales
```

---

## 51. Optional Non-Bitcoin Settlement Layer

Это отдельная укладка, не часть Bitcoin core.

```text
Bitcoin Bastion Register Core
  └── Bitcoin-only

Optional Non-Bitcoin Settlement Layer
  ├── USDT module
  ├── Monero / XMR module
  └── ZEC module
```

---

### 51.1. Почему отдельно

| Актив | Роль | Почему не core |
|---|---|---|
| BTC | hard money / суверенные деньги | основной актив |
| Lightning BTC | retail settlement | core |
| USDT | fiat-linked stable settlement | counterparty risk |
| XMR | privacy cash | не Bitcoin, регуляторный риск |
| ZEC | optional shielded privacy | не Bitcoin, optional privacy |

Главный принцип:

```text
Bitcoin is money layer.
USDT is fiat-linked settlement.
XMR/ZEC are privacy settlement alternatives.
They must not be merged into Bitcoin accounting.
```

---

### 51.2. Включение Non-Bitcoin Layer

При включении:

```text
You are enabling non-Bitcoin settlement assets.

This may introduce:
- counterparty risk
- regulatory risk
- custody complexity
- accounting complexity
- privacy trade-offs
- ideological deviation from Bitcoin-only mode
```

---

### 51.3. Раздельные отчёты

Неправильно:

```text
Crypto revenue: $10,000
```

Правильно:

```text
BTC Revenue
Lightning Revenue
On-chain BTC Revenue

USDT Revenue
XMR Revenue
ZEC Revenue
```

---

### 51.4. Раздельный Treasury

```text
BTC Treasury
Stablecoin Exposure
Privacy Asset Exposure
Fiat-linked Asset Exposure
```

---

## 52. USDT Module

USDT может быть полезен, но это идеологический компромисс.

### Где полезен

```text
страны с высокой инфляцией
USD-ценообразование
поставщики, которые не принимают BTC
оборотный капитал
снижение краткосрочной волатильности
```

### Риски

```text
counterparty risk
freezing risk
issuer risk
chain risk
regulatory risk
fiat dependency
ideological compromise
```

### Как встроить

USDT должен быть помечен как:

```text
Fiat-linked settlement asset
```

Функции:

```text
USDT invoice
network selector
stablecoin exposure report
auto-convert-to-BTC recommendation
counterparty risk warning
daily/weekly USDT limits
separate accounting export
```

### USDT Network Policy

```text
USDT on Liquid
USDT on Tron
USDT on Ethereum
USDT on Solana
```

С Bitcoin-aligned точки зрения:

```text
Preferred: Liquid USDT
Allowed: configurable
Core: never
```

### USDT Quarantine Wallet

```text
USDT → separate wallet/account
→ marked as fiat exposure
→ policy recommends conversion or settlement
```

---

## 53. XMR / Monero Module

Лучше использовать название **XMR Module**, а не “monerocash”.

### Где полезен

```text
privacy-first commerce
donations
sensitive lawful transactions
regions with financial surveillance
customers who value payment privacy
```

### Риски

```text
regulatory scrutiny
exchange delisting risk
accounting complexity
view key management
compliance complications
lower merchant tooling maturity
```

### Как встроить

```text
XMR payment request
Monero wallet RPC integration
view-only wallet mode
separate privacy accounting
optional view key export for owner/auditor
no customer identity collection
no automatic exchange by default
```

### Формулировка

> **Privacy-preserving settlement for lawful commerce where payment confidentiality matters.**

### View-key Governance

```text
who can access view key
when view-only export is allowed
auditor-only mode
encrypted view key storage optional
no spend key storage in Register
```

---

## 54. ZEC / Zcash Module

### Где полезен

```text
private donations
privacy-friendly commerce
selective disclosure
viewing keys for audit
payments requiring confidentiality
```

### Риски

```text
optional privacy creates mistakes
transparent addresses leak data
wallet compatibility issues
lower adoption
regulatory uncertainty
```

### Как встроить

```text
ZEC shielded invoice
prefer z-addresses
disable transparent addresses by default
viewing key support
memo policy
shielded pool warning
separate ZEC accounting
privacy status indicator
```

### Transparent-address Blocker

По умолчанию:

```text
transparent ZEC addresses disabled
shielded required
explicit owner override required
```

---

## 55. Unified Risk Engine

Для BTC, USDT, XMR, ZEC нужен общий risk engine.

Категории риска:

```text
Monetary risk
Counterparty risk
Regulatory risk
Privacy risk
Custody risk
Liquidity risk
Accounting risk
Ideological deviation risk
Operational risk
Connectivity risk
```

Risk table:

| Asset | Monetary risk | Privacy | Counterparty | Regulatory | Ideology |
|---|---:|---:|---:|---:|---:|
| BTC | Low | Medium by default | Low | Medium | Core |
| Lightning BTC | Low | Medium | Low | Medium | Core |
| USDT | Medium/High | Low/Medium | High | Medium/High | Non-core |
| XMR | Medium | High | Low | High | Non-core privacy |
| ZEC shielded | Medium | High if shielded | Low/Medium | Medium/High | Non-core privacy |

Ideological purity indicator:

```text
Mode: Pure Bitcoin
Ideological Purity: 100%

Mode: Bitcoin + USDT
Ideological Purity: 72%

Mode: Multi-Asset
Ideological Purity: 48%
```

---

## 56. Режимы с Non-Bitcoin Layer

### Pure Bitcoin Mode

```text
BTC only
Lightning
on-chain
BTCPay
no altcoins
no stablecoins
no privacy coins
```

### Bitcoin + Stable Settlement Mode

```text
BTC core
USDT optional
auto-convert policy
stablecoin exposure report
```

### Bitcoin + Privacy Settlement Mode

```text
BTC core
XMR optional
ZEC optional
separate privacy warnings
separate accounting
```

### Full Multi-Asset Sovereign Mode

```text
BTC
Lightning
on-chain
USDT
XMR
ZEC
strict separation
asset-specific policy
unified reports
```

Этот режим не должен быть default.

---

## 57. Архитектура

### 57.1. Modular Monolith First

Не микросервисы на старте.

```text
bastion_register/
  app/
    api/
    core/
    db/
    domain/
    services/
    integrations/
    tasks/
    schemas/
    main.py
```

---

### 57.2. Предлагаемая структура

```text
bastion_register/
  app/
    core/
      config.py
      logging.py
      security.py
      permissions.py
      policy.py
      feature_flags.py

    domain/
      sales/
      payments/
      receipts/
      shifts/
      treasury/
      privacy/
      risk/
      merchants/
      assets/
      reports/
      audit/
      connectivity/
      transports/
      offline/
      reconciliation/
      local_node/
      mesh/

    integrations/
      bitcoin/
        btcpay/
        lnd/
        core_lightning/
        bitcoin_core/
        mempool/
      lightning/
        lnurl/
        bolt12/
      transports/
        bluetooth/
        nfc/
        mdns/
        local_wifi/
      non_bitcoin/
        usdt/
        monero_xmr/
        zcash_zec/

    services/
      checkout/
      payment_router/
      receipt_service/
      shift_service/
      treasury_service/
      policy_engine/
      privacy_score/
      sovereignty_score/
      risk_engine/
      reporting/
      audit_service/
      connectivity_service/
      transport_service/
      offline_sale_service/
      reconciliation_service/
      local_discovery_service/
      device_pairing_service/

    api/
      routes/
        sales.py
        payments.py
        shifts.py
        receipts.py
        treasury.py
        reports.py
        settings.py
        assets.py
        health.py
        connectivity.py
        terminals.py

    tasks/
      payment_sync.py
      webhook_processor.py
      report_jobs.py
      treasury_jobs.py
      risk_jobs.py
      backup_jobs.py
      reconciliation_jobs.py
```

---

## 58. Payment Abstraction

Общий интерфейс:

```python
class PaymentAdapter:
    asset: str
    network: str

    async def create_payment_request(...):
        ...

    async def check_payment_status(...):
        ...

    async def handle_webhook(...):
        ...

    async def refund(...):
        ...

    async def estimate_fees(...):
        ...
```

Реализации:

```text
BitcoinLightningAdapter
BitcoinOnchainAdapter
BTCPayAdapter
LNURLAdapter
BOLT12Adapter
USDTAdapter
MoneroXMRAdapter
ZcashZECAdapter
```

Adapter capability registry:

```text
supports_refund
supports_webhook
supports_confirmations
supports_partial_payment
supports_view_only
supports_fee_estimate
supports_offline_request
supports_signature_proof
```

---

## 59. Базовые сущности БД

```text
Merchant
Store
Terminal
User
Role
Shift
Product
Sale
SaleItem
PaymentRequest
PaymentEvent
PaymentTransportEvent
Receipt
Refund
ExchangeRateSnapshot
TreasuryPolicy
AssetPolicy
WalletHealthSnapshot
LiquiditySnapshot
PrivacyRiskReport
SovereigntyScoreSnapshot
ConnectivitySnapshot
LocalNodeStatus
TerminalConnection
DevicePairing
OfflineSaleRecord
ReconciliationJob
ReconciliationResult
AddressPoolEntry
LocalNetworkProfile
AuditLog
WebhookEvent
TerminalSyncState
PolicyEvaluation
TreasuryRecommendation
```

---

### PaymentEvent

```text
id
payment_request_id
event_type
status
source
payload_hash
created_at
```

Типы:

```text
invoice_created
qr_displayed
nfc_transferred
bluetooth_transferred
payment_seen
payment_confirmed
payment_expired
webhook_received
refund_requested
refund_completed
```

---

### PaymentTransportEvent

```text
id
sale_id
payment_request_id
transport_type
device_id
status
payload_hash
transferred_at
acknowledged_at
error_reason
```

---

### OfflineSaleRecord

```text
id
sale_id
terminal_id
offline_mode
risk_level
created_at
requires_reconciliation
reconciled_at
reconciliation_status
```

---

### AddressPoolEntry

```text
id
merchant_id
wallet_label
address
derivation_path_optional
used
reserved
used_at
sale_id
risk_flags
```

---

### AssetPolicy

```text
id
merchant_id
asset_code
enabled
networks_allowed
max_single_payment_amount
max_daily_volume
require_manager_approval
auto_convert_policy
custody_warning_acknowledged
accounting_export_enabled
privacy_mode
created_at
updated_at
```

---

### PaymentRequest

```text
id
sale_id
asset_code
network
rail
transport
amount_asset
amount_sats
amount_fiat
exchange_rate_id
payment_uri
qr_payload
status
expires_at
confirmed_at
settlement_reference
risk_flags
```

---

## 60. Технологический стек

### Backend

```text
Python 3.12+
FastAPI
Pydantic v2
SQLAlchemy 2.x
Alembic
PostgreSQL
Redis
Celery
```

### Bitcoin Integrations

```text
BTCPay Server API
LND
Core Lightning
Bitcoin Core RPC
Mempool.space-compatible API
LNbits
LNURL
BOLT12-ready abstraction
```

### Optional Asset Integrations

```text
USDT adapter
Liquid adapter optional
Monero wallet RPC
Zcash wallet RPC / lightwallet-compatible adapter
```

### Local / Transport Integrations

```text
mDNS / Bonjour
local DNS
Bluetooth
NFC
local Wi-Fi hotspot
printer support
device pairing
```

### Frontend

```text
React / Next.js
PWA
Tablet-first UI
QR checkout screen
Manager dashboard
Terminal mode
Backoffice mode
Local payment page
Local verification page
```

### Security / Quality

```text
JWT auth
RBAC
Argon2 password hashing
structured logs
audit logs
pytest
mypy
ruff
black
pre-commit
Prometheus metrics
OpenTelemetry-ready
Sentry-ready abstraction
```

---

## 61. UI / UX

### Cashier Screen

```text
Amount
Quick Items
Lightning QR
On-chain QR
NFC Tap-to-Request
Bluetooth Relay
Payment status
Receipt
Refund if allowed
```

### Manager Dashboard

```text
Open shifts
Sales today
Failed invoices
Refunds
Terminal health
Payment rail distribution
Offline pending sales
Reconciliation queue
```

### Owner Dashboard

```text
Treasury exposure
Hot wallet risk
Cold storage recommendations
Privacy score
Sovereignty score
Internet independence score
Policy violations
Node health
Reports export
Backup status
```

### Connectivity Dashboard

```text
Internet
Local Wi-Fi
Bluetooth
NFC
Bitcoin Core
Lightning node
BTCPay
Tor
Terminals
Power status
Recommended mode
```

### Asset Layer Dashboard

```text
BTC revenue
Lightning revenue
On-chain revenue
USDT exposure
XMR revenue
ZEC revenue
non-Bitcoin risk warnings
ideological deviation score
```

---

## 62. Hardware and Resilience

### Power-resilient Mode

```text
UPS support
battery mode for Bastion Register Box
low-power mode
local data flush
safe shutdown
mobile hotspot fallback
```

Пример:

```text
Battery: 42%
Estimated local operation: 2h 10m
Mode: low-power commerce
```

---

### Terminal Theft Mode

Если планшет украли:

```text
Owner marks terminal as stolen
→ terminal token revoked
→ local pending sales marked for review
→ offline signing permissions invalidated
→ device cannot sync as trusted
```

---

### Hardware Security Key Support

Для owner/manager actions:

```text
FIDO2 / YubiKey
hardware approval
NFC security key
```

Особенно для:

```text
включения non-Bitcoin layer
изменения treasury destination
поднятия offline limits
экспорта отчётов
PSBT workflow
```

---

## 63. Resilience Playbooks

Готовые сценарии:

```text
Internet down
Node down
Lightning peers down
BTCPay down
Printer down
Terminal stolen
Bluetooth unavailable
NFC unavailable
Router down
Power outage
Exchange rate stale
Address pool low
```

Для каждого сценария:

```text
Impact
Available modes
Recommended action
Risk level
Recovery checklist
```

Пример:

```text
Internet down.

Available:
- local sale records
- NFC request transfer
- Bluetooth request transfer
- on-chain address pool

Unavailable:
- external Lightning settlement
- mempool freshness
- exchange rate updates

Recommended:
- use low-value offline mode only
- require manager approval above 100,000 sats
```

---

## 64. Education Layer

Встроенные подсказки:

```text
Why avoid address reuse?
Why not keep too much in hot wallet?
Why Lightning liquidity matters?
Why stablecoins are not Bitcoin?
Why self-host BTCPay?
Why offline payment request is not final settlement?
Why own node matters?
```

---

## 65. Legal-neutral Compliance Export

Система не даёт юридические советы, но умеет экспортировать:

```text
sales report
VAT/tax category report
BTC received report
exchange rate snapshots
refund report
shift report
asset-separated report
offline reconciliation report
audit log
```

Формулировка:

```text
The system provides records.
The merchant remains responsible for jurisdiction-specific reporting.
```

---

## 66. Монетизация

### 66.1. Open-core

Бесплатно:

```text
Bitcoin checkout
BTCPay integration
basic sales
receipts
shifts
local reports
```

Платно:

```text
multi-store
advanced treasury
privacy scoring
sovereignty score
internet independence score
policy-as-code
event mode
mesh mode
audit exports
asset layer
premium support
```

---

### 66.2. Hosted Management Layer

Пользователь держит BTCPay/node сам, а Bastion даёт:

```text
dashboard
analytics
alerts
reports
staff management
risk engine
```

---

### 66.3. Appliance Model

```text
Bastion Register Box:
- mini PC / Raspberry Pi / industrial box
- Bitcoin Core
- Lightning node
- BTCPay optional
- Bastion Register
- Wi-Fi hotspot
- Bluetooth
- NFC
- printer support
- Tor preconfigured
```

---

### 66.4. B2B Support

```text
installation
node setup
BTCPay setup
merchant training
event support
security review
backup planning
circular economy setup
```

---

## 67. Основные риски проекта

### 67.1. Маленький рынок

Bitcoin-only merchants пока ниша.

Решение:

```text
Bitcoin meetups
conferences
circular economies
privacy communities
online stores
independent businesses
private clubs
```

---

### 67.2. Lightning UX

Проблемы:

```text
liquidity
routing failures
node downtime
invoice expiry
channel management
offline limitations
```

Решение:

```text
BTCPay first
liquidity dashboard
failed payment diagnosis
readiness score
clear pending/settled distinction
```

---

### 67.3. Hardware Complexity

Понадобятся:

```text
receipt printer
barcode scanner
cash drawer
tablet support
customer display
NFC module
Bluetooth reliability
local Wi-Fi setup
```

Решение:

```text
PWA first
Register Box later
printer support later
hardware profiles later
```

---

### 67.4. Regulatory Pressure

Кассовое ПО связано с отчётами.

Решение:

```text
neutral exports
no tax evasion messaging
jurisdiction-specific plugins later
merchant responsibility
```

---

### 67.5. Ideological Dilution

Если добавить USDT / XMR / ZEC слишком рано, бренд станет “crypto cash register”.

Решение:

```text
Bitcoin-only core first
non-Bitcoin separate layer later
explicit warnings
separate accounting
separate branding
```

---

### 67.6. Offline Settlement Misunderstanding

Пользователь может думать, что offline payment request = оплата.

Решение:

```text
Offline Settlement Honesty Engine
clear pending status
risk warnings
policy limits
reconciliation report
```

---

## 68. Roadmap

### Phase 1 — Bitcoin Register MVP

```text
FastAPI backend
PostgreSQL
React/PWA frontend
BTCPay integration
Lightning invoice checkout
on-chain BTC checkout
sales
receipts
shifts
roles
audit log
daily report
```

---

### Phase 2 — Merchant Operations

```text
multi-terminal mode
cashier risk limits
refund workflow
manager dashboard
event mode baseline
receipt signatures
terminal sync state
device trust levels
```

---

### Phase 3 — Sovereign Local Commerce

```text
local Wi-Fi access to Register server
local BTCPay/LND/Core Lightning connection
offline sale records
pending payment status
manual reconciliation
basic QR fallback
connectivity dashboard
```

---

### Phase 4 — Local Node / Offline Advanced

```text
own node verification
local node health
address pool
reconciliation engine
terminal certificates
NFC Tap-to-Request
Bluetooth payment relay
local payment page
local receipt verification
```

---

### Phase 5 — Bitcoin Intelligence

```text
Lightning liquidity dashboard
failed payment diagnosis
fee intelligence
node health
business continuity report
payment rail recommendation
explainable rail choice
```

---

### Phase 6 — Treasury / Privacy

```text
hot wallet exposure warnings
cold storage sweep planner
PSBT workflow
treasury policy
privacy score
sovereignty score
policy-as-code
policy simulator
```

---

### Phase 7 — Circular Economy

```text
merchant network
Nostr merchant profile
LNURL-pay
Lightning Address
BOLT12 readiness
merchant-to-merchant invoices
local sats flow analytics
mesh event mode
```

---

### Phase 8 — Optional Non-Bitcoin Settlement Layer

```text
USDT module
XMR module
ZEC module
AssetPolicy
non-Bitcoin risk dashboard
separate accounting
ideological deviation warnings
view-key governance
USDT quarantine wallet
ZEC transparent-address blocker
```

---

## 69. Самый правильный порядок разработки

```text
1. Pure Bitcoin Register
2. BTCPay + Lightning + on-chain BTC
3. Sales / receipts / shifts / roles
4. Local Wi-Fi + own node mode
5. Offline records + reconciliation
6. NFC / Bluetooth transport
7. Treasury + privacy + policy
8. Circular economy layer
9. Optional USDT / XMR / ZEC layer
```

Почему:

```text
Сначала нужно завоевать доверие Bitcoin-аудитории.
Потом расширять операционные возможности.
И только после этого добавлять optional non-Bitcoin layer.
```

---

## 70. Финальная структура бренда

### Основной бренд

```text
Bitcoin Bastion Register
```

Смысл:

```text
Bitcoin-only
Lightning-first
self-custody
own-node-first
privacy-aware
offline-capable
merchant sovereignty
```

---

### Аппаратный продукт

```text
Bastion Register Box
```

Смысл:

```text
local commerce node
Bitcoin Core
Lightning node
Wi-Fi
Bluetooth
NFC
local database
offline resilience
```

---

### Терминал

```text
Bastion Register Terminal
```

Смысл:

```text
cashier interface
tablet / phone / web terminal
limited permissions
QR / NFC / Bluetooth payment request
```

---

### Продвинутая нодовая версия

```text
Bastion Commerce Node
```

Смысл:

```text
merchant-owned Bitcoin infrastructure
local node commerce
circular economy hub
```

---

### Расширенная версия

```text
Bitcoin Bastion Register Sovereign+
```

Смысл:

```text
Bitcoin core
optional USDT
optional XMR
optional ZEC
strict separation
risk scoring
asset policies
```

---

## 71. Финальная суть проекта

Bitcoin Bastion Register — это не:

```text
обычный POS
crypto checkout
custodial wallet
exchange gateway
cloud payment terminal
```

Это:

```text
суверенная Bitcoin-касса
торговый регистр
локальный commerce-node
Lightning terminal
on-chain checkout
offline-first merchant ledger
treasury console
privacy guard
merchant intelligence system
circular Bitcoin economy infrastructure
```

Главная уникальность:

> **Bitcoin Bastion Register позволяет бизнесу принимать Bitcoin и управлять торговлей через собственную инфраструктуру: свою ноду, свою локальную сеть, свои терминалы, свои правила, свои чеки, свои отчёты и свои ключи — даже при сбоях интернета и внешних платёжных систем.**

Самая короткая формула:

> **Bitcoin Bastion Register помогает торговцу не просто принимать Bitcoin, а жить и работать на Bitcoin rails.**
