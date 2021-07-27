---
title: Сведения о приложениях для LMS365 от ELEARNINGFORCE International
ms.author: elmalova
author: elenamalova
ms.date: 03/18/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Все доступные сведения о безопасности и соответствия требованиям для LMS365, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4a4690496c4da8fd31de70bfa796d15d73dba844
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53521772"
---
# <a name="lms365"></a>LMS365

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 18 марта 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/d136f17e-df84-47f2-97a4-13aa24c0c647" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381467" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные корпорацией Майкрософт ELEARNINGFORCE International:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | LMS365 |
| Идентификатор | WA104381467 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | ELEARNINGFORCE International |
| URL-адрес веб-сайта-партнера | [https://www.elearningforce.com](https://www.elearningforce.com) |
| URL-адрес страницы Teams приложения | [https://www.elearningforce.com/teams](https://www.elearningforce.com/teams) |
| URL-адрес политики конфиденциальности | [https://www.elearningforce.com/privacy](https://www.elearningforce.com/privacy) |
| URL-адрес терминов использования | [https://www.elearningforce.com/LMS365-SaaS-Terms](https://www.elearningforce.com/LMS365-SaaS-Terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена ELEARNINGFORCE International о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| GroupMember.Read.All | приложение | Нет | Позволяет приложению расширять участников группы AD, которые необходимы для регистрации группы пользователей на курсы. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| Mail.Send | делегирована | Нет | Разрешение запрашивается динамически при настройке учетной записи электронной почты для уведомления. Позволяет приложению отправлять сообщения уведомлений | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| RoleManagement.Read.Directory | приложение | Нет | Позволяет приложению получать SharePoint домена во время предварительного обеспечения клиента. Домен используется для построения URL-адресов. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Invite.All | делегирована | Нет | Позволяет приложению приглашать внешних пользователей в текущий журнал от имени пользователя | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read | делегирована | Нет | Вход и чтение профиля пользователя. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | делегирована | Нет | Позволяет приложению считыть полный профиль текущего входа в пользователя. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| User.Read.All | приложение | Позволяет приложению читать полный профиль пользователя. Это&#8217;, необходимое для чтения пользователей&#8217; менеджеров для создания отчетов иерархии. | Следующие персональные данные хранятся в специальной базе данных для соответствующего клиента, используемого для функции панели мониторинга диспетчера управления для пользователей &amp; в приложении. Имя учетной записи, имя отображения пользователя, адрес электронной почты, отдел, название задания, Office, страна, город, ID/Email диспетчера | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |
>| profile | делегирована | Нет | Просмотр основного профиля пользователя. | [a1a0b277-0efb-4f00-9661-6d1a3df3cddc](https://docs.microsoft.com/microsoft-365-app-certification/azure/a1a0b277-0efb-4f00-9661-6d1a3df3cddc) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| SharePoint | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Имя используется только для отображения персонализированного сообщения, когда бот приветствует пользователя. | Персональные данные хранятся в специальной базе данных Azure для соответствующего клиента, используемого для функции панели мониторинга диспетчера управления для пользователей в приложении &amp; LMS365. | Имя учетной записи, имя отображения пользователя, адрес электронной почты, отдел, название задания, Office, страна, город, ID/Email диспетчера |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да, мы используем телеметрию Аналитика log Analytics, которые используются только для сохранения проблем и имеют политику хранения в течение 90 дней, после которой все данные удаляются.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>LMS365 оснащен функцией очистки, которая удаляет любые личные данные из базы данных клиентов LMS365.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35695" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения были предоставлены ELEARNINGFORCE International о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | Платформы устройств, состояние устройства, клиентские приложения |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
