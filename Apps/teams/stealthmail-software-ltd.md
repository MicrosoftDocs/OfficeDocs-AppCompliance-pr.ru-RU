---
title: Сведения о приложениях для StealthMail от Stealthmail Software Ltd
ms.author: elmalova
author: elenamalova
ms.date: 03/31/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для StealthMail, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 322cdc906ab0cd2ae8980d1412bb4dd9c897a5f6
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286881"
---
# <a name="stealthmail"></a>StealthMail

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 31 марта 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/1ed0a549-c730-44c7-a984-a8c658fe9807" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001748" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт по программному обеспечению Stealthmail:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | StealthMail |
| Идентификатор | WA200001748 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Stealthmail Software Ltd |
| URL-адрес веб-сайта-партнера | [https://stealthmail.com](https://stealthmail.com) |
| URL-адрес страницы Teams приложения | [https://stealthmail.com/product/teams](https://stealthmail.com/product/teams) |
| URL-адрес политики конфиденциальности | [https://stealthmail.com/privacy-statement](https://stealthmail.com/privacy-statement) |
| URL-адрес терминов использования | [https://stealthmail.com/terms-and-conditions](https://stealthmail.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена stealthmail Software Ltd о том, как это приложение собирает и хранит организационные данные и контроль, который будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | делегирована | Приложение отправляет сообщение каналу со ссылкой на созданную безопасную электронную почту | ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| ChannelMessage.Send | делегирована | Приложение отправляет сообщение каналу со ссылкой на созданную безопасную электронную почту | ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| Chat.ReadWrite | делегирована | Приложение отправляет сообщение в чат со ссылкой на созданную безопасную электронную почту | ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| GroupMember.Read.All | делегирована | Приложение получает членов канала, чтобы сделать безопасной электронной почты для них | ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| User.Read.All | делегирована | Приложение получает участников чата для безопасной электронной почты для них | ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| User.ReadBasic.All | делегирована | Приложение получает участников чата для безопасной электронной почты для них | ничего | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |
>| email | делегирована | Проверка подлинности пользователя | ничто не хранится в базе данных | [1ed0a549-c730-44c7-a984-a8c658fe9807](https://docs.microsoft.com/microsoft-365-app-certification/azure/1ed0a549-c730-44c7-a984-a8c658fe9807) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы не контролируем данные партнеров в их системах.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37867" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена stealthmail Software Ltd о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

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
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
