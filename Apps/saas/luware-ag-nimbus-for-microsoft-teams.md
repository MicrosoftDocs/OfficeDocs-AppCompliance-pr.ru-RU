---
title: Сведения о приложениях для Luware Nimbus для Microsoft Teams luware AG
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для Luware Nimbus для Microsoft Teams, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: d7139f3ca934da20e58bb9f838217796ca5644da
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410493"
---
# <a name="luware-nimbus-for-microsoft-teams"></a>Luware Nimbus для Microsoft Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 1 октября 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/web-apps/luwareagzurich.advanced_routing_azure_marketplace" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Luware AG корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Luware Nimbus для Microsoft Teams |
| Идентификатор | luwareagzurich.advanced_routing_azure_marketplace |
| Имя компании-партнера | Luware AG |
| URL-адрес веб-сайта-партнера | [https://luware.com](https://luware.com) |
| URL-адрес политики конфиденциальности | [https://luware.com/en/privacy-policy](https://luware.com/en/privacy-policy) |
| URL-адрес терминов использования | [https://luware.com/en/agreements/saas/](https://luware.com/en/agreements/saas/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Luware AG о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | делегирована | Сопутствующие консоли: Чтение календаря входа в пользовательское шоу Календарь с назначениями | Отсутствует | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calendars.Read.Shared | делегирована | Сопутствующие консоли: Чтение общих календарей, чтобы показать календарь с назначениями | Отсутствует | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read | делегирована | Сопровождающий консоли: поиск Exchange контактов зарегистрированного пользователя | Нет | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Contacts.Read.Shared | делегирована | Сопутствующие консоли: поиск в общих Exchange контактов | Нет | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| GroupMember.Read.All | приложение | Получить членов группы, прочитать группы безопасности | Мы храним эту информацию, так как агенты центра обработки вызовов управляются через членство в группе | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Presence.Read.All | делегирована | Показать присутствие в поиске контактов на странице Сопутствующие консоли | Отсутствует | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read | делегирована | Get UserInformation (от входа в пользователя) | Нет | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.Read.All | оба | Nimbus App — get CallerInformation. При внутреннем вызове в контакт-центр мы делаем обратный разглядывание того, кто это может быть, чтобы мы могли показать эту информацию агенту. В консоли Attendant (с делегированным разрешением) мы ищем весь внутренний каталог для целей передачи. | Для отчета REasons о том, кто больше всех вызвал, мы храним эти данные. | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| User.ReadBasic.All | делегирована | Ограниченный поиск пользователей | Нет | [23694b6c-5a4a-45ce-9c6a-37c5f1880d4e](https://docs.microsoft.com/microsoft-365-app-certification/azure/23694b6c-5a4a-45ce-9c6a-37c5f1880d4e) |
>| Calls.AccessMedia.All | приложение | Многие из этих приложений и ботов (одна очередь в центре контактов): Подпишитесь на тона DTMF, в которых клиент может выбрать свою позицию в IVR | Все DTMF Info для выбранных способов через IVR по причине отчетности | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.Initiate.All | приложение | Многие из этих приложений и ботов (по одному в очереди контактного центра): вызов агента  | Все сведения о CDR по причине отчетности | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.InitiateGroupCall.All | приложение | Многие из этих приложений и ботов (по одному в очереди контактного центра): вызов агента  | Все сведения о CDR по причине отчетности | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |
>| Calls.JoinGroupCall.All | приложение | Многие из этих приложений и ботов (по одной очереди в центре контактов): Присоединяйтесь к эскалации вызова для воспроизведения объявлений | Все сведения о CDR по причине отчетности | [7e1fc6b3-90a7-4a98-a766-5627193e95bc](https://docs.microsoft.com/microsoft-365-app-certification/azure/7e1fc6b3-90a7-4a98-a766-5627193e95bc) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Агрегированные данные отчетов (записи о подробностях вызовов, сведения о вызываемом вызове, сведения о поездках по вызову и т. д.): данные конфигурации за 24 месяца: журналы приложений по контракту клиента +30 дней: временное хранение внутренних журналов приложений (чтобы помочь инженерам службы поддержки устранить неполадки в производительности и работе компонентов приложений) 30 дней.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>https://luware.com/en/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена Luware AG о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | Клиентские приложения, пользователи и группы |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

