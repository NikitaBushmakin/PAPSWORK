# Задача 1: Перечень заинтересованных лиц
- Сотрудники здравоохранения - различные медработники заинтересованы т.к. система может значительно облегчить их работу, например, снизив - потребность в выездах на места.
- Немобильные и изолированные пациенты - категория пользователей заинтересована т.к. система позволит им легче получать консультацию по медицинским вопросам, без необходимости долго ждать прибытия медработника на дом или долго ехать куда-либо.
- Люди, ведущие научные исследования в области здравоохранения - различные студенты и ученые заинтересованы т.к. система может позволить им легче собирать статистические данные. В частности - касательно здоровья немобильных и изолированных пациентов.
- Муниципальные власти - в том случае, если они заинтересованы в развитии здравоохранения на их территории. Кроме того, система, потенциально, позволит снизить затраты на транспортный парк организацией здравоохранения.
- Поставщики транспортных услуг органам здравоохранения - антистейкхолдер, т.к. смотри пункт выше.
- Общественные организации - заинтересованы в улучшении здравоохранения для людей.
- Обычные пользователи услуг здравоохранения - т.к. это уменьшит затрачиваемые ими усилия на получение медицинских консультации и помощь.
- Медицинские учреждения - медицинские учреждения и больницы, которые заинтересованы в сотрудничестве с компанией и использовании системы для консультаций пациентов
- Местный медицинский персонал - персонал медицинского учреждения, территориально подходящего клиенту, который обратился за консультацией
- Юристы компании - требуется соответствие системы с законодательством РФ в сфере медицинского обслуживания
- Специалисты тех. обслуживания - специалисты, ответственные за обслуживание и поддержку системы
# Задача 2: Перечень функциональных требований
- Медработник может просматривать историю болезни клиентов
- Медработник может просматривать сообщения в чате от клиентов
- Медработник может отправлять сообщения в чате
- Медработник может просматривать список медицинских диагнозов
- Медработник может выбирать из списка медицинских диагнозов подходящий медицинский диагноз
- Медработник может получать уведомления о предстоящих консультациях
- Медработник может определять сроки ответов на вопросы клиентов
- Клиент может просматривать свою историю болезни
- Клиент может редактировать свою историю болезни
- Клиент может связаться с местным медицинским персоналом через систему
- Клиент может отправить сообщение в чат
- Клиент может получить ответ в чате
- Медицинский персонал может просматривать сообщения от клиентов
# Задача 3: Схема вариантов использования
![image](https://github.com/NikitaBushmakin/PAPSWORK/assets/164217929/a2d68a26-7008-4eed-8d07-c1a74d782a5a)
# Задача 4: Предположения
- Система должна включать в себя базу знаний, содержащую информацию о различных симптомах и болезнях, чтобы медработнику было проще поставить диагноз. В базе знаний должен быть поиск по симптомам. Из Базы Знаний должна быть возможность делать выписки.
- Система должна иметь возможность хранить “репутацию” пациентов. Люди, совершающие ложные запросы или пишущие в чат не по теме, должны как-то отсеивается.
- Система должна сохранять историю обращений пациентов, чтобы можно было свериться с прошлыми диагнозами. 
- Система должна иметь возможность регистрации. Возможно, с привязкой к госуслугам или аналогичному сервису.
- Возможно, получится воспользоваться наработками компании - позаимствовать готовые элементы программы.
- Система должна быть разработана с учетом разнообразия языков, культурных особенностей и правил обработки медицинской информации в разных странах
- Система должна предоставлять средства интеграции с медицинскими учреждениями по всему миру
- Учесть возможность записей и комментариев медсестрой в системе для дальнейшего анализа и консультации со специалистами при необходимости
# Задача 5: Нефункциональные требования
- Обеспечение возможности масштабирования системы для поддержки увеличения числа медсестер и клиентов по мере роста бизнеса
- Гарантировать конфиденциальность информации о пациентах и соблюдение стандартов безопасности данных в соответствии с законодательством в области здравоохранения
- Система должна быть совместима с различными операционными системами и веб-браузерами для удобства использования
- Задержка ответа системы на запросы медсестер и клиентов не должна превышать 2 секунды
