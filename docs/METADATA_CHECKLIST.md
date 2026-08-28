# Чеклист об'єктів метаданих

Статуси:
- ✅ — є схема (`metadata.md`) + модуль у `src/`
- 📄 — лише схема (модуль не потрібен)
- 🔗 — розширення штатного об'єкта (опис у схемі)

| # | Об'єкт | Тип | Статус | Шлях |
|---|--------|-----|--------|------|
| 1 | `LC_КартыLoyalCards` | Довідник | ✅ | `src/Catalogs/LC_КартыLoyalCards/` |
| 2 | `LC_УровниЛояльности` | Довідник | ✅ | `src/Catalogs/LC_УровниЛояльности/` |
| 3 | `LC_ПартииБонусов` | Довідник | ✅ | `src/Catalogs/LC_ПартииБонусов/` |
| 4 | `LC_БонусныеБаллыКлиентов` | Регістр накопичення | ✅ | `src/AccumulationRegisters/LC_БонусныеБаллыКлиентов/` |
| 5 | `LC_БонусныеБаллыОборот` | Регістр накопичення | ✅ | `src/AccumulationRegisters/LC_БонусныеБаллыОборот/` |
| 6 | `LC_ПартииБонусов` | Регістр відомостей | ✅ | `src/InformationRegisters/LC_ПартииБонусов/` |
| 7 | `LC_ОчередьСинхронизацииLoyalCards` | Регістр відомостей | ✅ | `src/InformationRegisters/LC_ОчередьСинхронизацииLoyalCards/` |
| 8 | `LC_ТокеныLoyalCards` | Регістр відомостей | ✅ | `src/InformationRegisters/LC_ТокеныLoyalCards/` |
| 9 | `LC_СостоянияБонусов` | Перерахування | 📄 | `src/Enums/LC_СостоянияБонусов.md` |
| 10 | `LC_СтатусыБонуснойПартии` | Перерахування | 📄 | `src/Enums/LC_СтатусыБонуснойПартии.md` |
| 11 | `LC_ВидыБонусныхОпераций` | Перерахування | 📄 | `src/Enums/LC_ВидыБонусныхОпераций.md` |
| 12 | `LC_СпособыИдентификацииКлиента` | Перерахування | 📄 | `src/Enums/LC_СпособыИдентификацииКлиента.md` |
| 13 | `LC_СтатусыКартыLoyalCards` | Перерахування | 📄 | `src/Enums/LC_СтатусыКартыLoyalCards.md` |
| 14 | `LC_АдресСервераLoyalCards` | Константа | 📄 | `src/Constants/metadata.md` |
| 15 | `LC_EmailLoyalCards` | Константа | 📄 | `src/Constants/metadata.md` |
| 16 | `LC_ПарольLoyalCards` | Константа | 📄 | `src/Constants/metadata.md` |
| 17 | `LC_PassTypeIdentifier` | Константа | 📄 | `src/Constants/metadata.md` |
| 18 | `LC_TemplateId` | Константа | 📄 | `src/Constants/metadata.md` |
| 19 | `LC_OrganisationId` | Константа | 📄 | `src/Constants/metadata.md` |
| 20 | `LC_ТаймаутЗапросаСек` | Константа | 📄 | `src/Constants/metadata.md` |
| 21 | `LC_ИспользоватьИнтеграциюLoyalCards` | Константа | 📄 | `src/Constants/metadata.md` |
| 22 | `LC_ОперацияБонусов` | Документ | ✅ | `src/Documents/LC_ОперацияБонусов/` |
| 23 | `LC_АктивацияИСгораниеБонусов` | Регламент | ✅ | `src/ScheduledJobs/LC_АктивацияИСгораниеБонусов/` |
| 24 | `LC_МиграцияВБонуснуюПрограмму` | Обробка | ✅ | `src/DataProcessors/LC_МиграцияВБонуснуюПрограмму/` |
| 25 | `ЧекККМ` | Розширення документа | 🔗 | `docs/metadata/DOCUMENT_EXTENSIONS.md` |
| 26 | `ВозвратТоваровОтПокупателя` | Розширення документа | 🔗 | `docs/metadata/DOCUMENT_EXTENSIONS.md` |
| 27 | `Контрагенты` | Розширення довідника | 🔗 | `docs/CATALOGS_SCHEMA.md` |
| 28 | `ИнформационныеКарты` | Розширення довідника | 🔗 | `docs/CATALOGS_SCHEMA.md` |

## Загальні модулі

| Модуль | Шлях |
|--------|------|
| `LC_LoyalCardsAPI` | `src/CommonModules/LC_LoyalCardsAPI/` |
| `LC_ОбщегоНазначения` | `src/CommonModules/LC_ОбщегоНазначения/` |
| `LC_БонуснаяПрограммаСервер` | `src/CommonModules/LC_БонуснаяПрограммаСервер/` |
| `LC_СинхронизацияLoyalCards` | `src/CommonModules/LC_СинхронизацияLoyalCards/` |
| `LC_ИнтеграцияЧекККМ` | `src/CommonModules/LC_ИнтеграцияЧекККМ/` |
| `LC_БонуснаяПрограммаКлиент` | `src/CommonModules/LC_БонуснаяПрограммаКлиент/` |
