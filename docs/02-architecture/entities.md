# Сущностная модель

- Пациент (id, ФИО, СНИЛС, полис, дата рождения, телефон)
- Приём (id, patient_id, врач, дата, диагноз, назначения)
- Расписание (id, врач, дата, время, статус)
- Медицинский документ (id, appointment_id, тип, статус, файл, ЭП)
- Пользователь (id, логин, роль, ФИО, контакты)
- Услуга (id, patient_id, вид услуги, сумма, статус)

## ERD-схема

![ERD-сущностная модель](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/namestnikoff/medical-documentation-system-design/main/docs/02-architecture/diagrams/entities.puml)

[Исходный код схемы](diagrams/entities.puml)

