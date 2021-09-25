---
title: Сведения о приложениях для InCaseIT по Pilotech AS
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для InCaseIT, политики обработки данных, Microsoft Cloud App Security каталог приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: dbc393582f4146c8cf9b44da122b35629df59a83
ms.sourcegitcommit: d5c60e66355ffa8fb84565e565f8bb15a665a099
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/24/2021
ms.locfileid: "59785774"
---
# <a name="incaseit"></a>InCaseIT

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/4420b597-c1d5-4d40-ba81-2b2a78575c81" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003265" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные службой Pilotech AS корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | InCaseIT |
| ID | WA200003265 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Pilotech AS |
| URL-адрес веб-сайта-партнера | [https://incaseit.com](https://incaseit.com) |
| URL-адрес страницы Teams приложения | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/introduction-to-incaseit-version-2-0) |
| URL-адрес политики конфиденциальности | [https://www.incaseit.com/privacy-policy/](https://www.incaseit.com/privacy-policy/) |
| URL-адрес терминов использования | [https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/t...](https://www.manula.com/manuals/pilotech-as/incaseit2/1/en/topic/1-4-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Pilotech AS о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | Единственным используемым данным является явное подтверждение пользователями, позволяя приложению использовать маркер доступа для вызова Graph API. | В нашем приложении хранится только ссылка на запланированное собрание для простого доступа к собраниям для пользователей.  Эти URL-адреса должны поддерживать протокол HTTPS. 1. Создание запланированного Teams собрания. 2. Сохраните ссылку на собрание в базе данных 3. Используйте ссылку на собрание для кнопки в приложении для легкого доступа к собранию. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| OnlineMeetings.ReadWrite | делегирована | Единственным используемым данным является явное подтверждение пользователями, позволяя приложению использовать маркер доступа для вызова Graph API. | В нашем приложении хранится только ссылка на собрание в Интернете для легкой доступности собраний для пользователей.  Эти URL-адреса должны поддерживать протокол HTTPS. 1. Создание собрания Teams в Интернете. 2. Сохраните ссылку на собрание в базе данных 3. Используйте ссылку на собрание для кнопки в приложении для легкого доступа к собранию. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |
>| User.Read | делегирована | Единственным используемым данным является явное подтверждение пользователями, позволяя приложению использовать маркер доступа для вызова Graph API. | Данные не хранятся с разрешения User.Read. | [9af6eceb-6a8b-4710-b51d-dde2ac01cc71](https://docs.microsoft.com/microsoft-365-app-certification/azure/9af6eceb-6a8b-4710-b51d-dde2ac01cc71) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>EUII может появляться в журналах приложений при отправке сообщений внутренним группам управления кризисами во время кризиса. Политики удаления журналов в том, что мы экономим максимум 3 месяца журналов. При необходимости они могут быть удалены по запросу. 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>У нас есть соглашения о защите данных со всеми нашими партнерами и субвендорами, обеспечивающие соблюдение правил GDPR, регулирующих положение обработчиков данных и подпереработчиков данных.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена в Pilotech AS о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/><br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
