---
title: Сведения о приложениях для коммутирующих по маршруту коммутайт
ms.author: elmalova
author: elenamalova
ms.date: 10/07/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Commuty, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8107880619d85a0ea80ba3aa26d9f10edc9cef48
ms.sourcegitcommit: 4817af6bd92bcc7624a43ea79ba6b9362da38035
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/07/2021
ms.locfileid: "60234105"
---
# <a name="commuty"></a>Коммутайт

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 7 октября 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003325" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые службой Commuty в Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Коммутайт |
| ID | WA200003325 |
| Office 365 поддерживаемые клиенты | Outlook 2016 или более поздней Windows, Outlook 2016 или позднее на Mac, Outlook в Интернете |
| Имя компании-партнера | Коммутайт |
| URL-адрес веб-сайта-партнера | [https://www.commuty.net](https://www.commuty.net) |
| URL-адрес политики конфиденциальности | [https://support.commuty.net/article/33-privacy-policy](https://support.commuty.net/article/33-privacy-policy) |
| URL-адрес терминов использования | [https://support.commuty.net/article/32-terms-conditions](https://support.commuty.net/article/32-terms-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены коммутационным приложением о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | События календаря | Нет, он используется только для синхронизации данных Commuty с Календарь Outlook. Данные всегда предоставляются в пользовательском интерфейсе commuty (который может быть через Outlook надстройки). | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| email | делегирована | Адрес электронной почты | Нет, это используется только для совпадения пользователя Commuty с идентификатором AD | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| offline_access | делегирована | Н/Д | Н/Д | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| openid | делегирована | Аутентификация | Нет | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |
>| profile | делегирована | Удостоверение | Нет | [7c90e3d4-5233-4e49-8753-36cd5feb7fa0](https://docs.microsoft.com/microsoft-365-app-certification/azure/7c90e3d4-5233-4e49-8753-36cd5feb7fa0) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Общие личные данные (основная электронная почта, вторичная электронная почта, по которой они могут получать уведомления (необязательно), имя, имя, номер Телефон (необязательный) ,Изображение профиля (необязательно) ,Предпочитаемый язык, Личный адрес (необязательно, может быть только городом)), Данные парковки (номерной знак), Данные о мобильности: (пропуск Carpool, несколько поездок на дому, Departure-Return часов (необязательный), доступность автомобилей (необязательно), Коммутирует, Вне офиса дней). Хранение: по запросу пользователя или по окончании контракта с клиентом

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Каждый клиент Commuty подписывают наш DPA (, который https://dpa.commuty.net) включает краткий обзор по этому.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

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

Эти сведения предоставлены коммутацией о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
