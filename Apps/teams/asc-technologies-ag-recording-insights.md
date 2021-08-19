---
title: Сведения о приложениях для записи ASC Аналитика asC Technologies AG
ms.author: elmalova
author: elenamalova
ms.date: 06/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для asC Recording Аналитика, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: efeac55591daa01827df42e8b473acdea8ee66f5
ms.sourcegitcommit: 3660f89e183c638979a31c295ac059daa6c387dd
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/18/2021
ms.locfileid: "58391892"
---
# <a name="asc-recording-insights"></a>AsC Recording Аналитика

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 2 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/8f79287d-5850-42f1-9af2-48ddf6ef89a8" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000708" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые asC Technologies AG в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | AsC Recording Аналитика |
| ID | WA200000708 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | ASC Technologies AG |
| URL-адрес веб-сайта-партнера | [https://asctechnologies.com/english/index.html](https://asctechnologies.com/english/index.html) |
| URL-адрес страницы Teams приложения | [https://asctechnologies.com/english/ASC_Recording_Insights_...](https://asctechnologies.com/english/ASC_Recording_Insights_Compliance_Recording_for_Microsoft_Teams.html) |
| URL-адрес политики конфиденциальности | [https://teams.asc-recording.app/privacy](https://teams.asc-recording.app/privacy) |
| URL-адрес терминов использования | [https://asctechnologies.com/english/asc_impressum.html](https://asctechnologies.com/english/asc_impressum.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена ASC Technologies AG о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | приложение | Сведения о собраниях пользователей | Object ID собраний | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read | приложение | Созданные чаты пользователей | Объектный ID чатов | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Chat.Read.All | приложение | Созданные чаты пользователей | Объектный ID чатов | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| Group.Read.All | приложение | Группа пользователей membership AD | Объектный ID группы AD | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| OnlineMeetings.Read.All | приложение | Сведения о собраниях пользователей | Object ID собраний | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.Read | приложение | Имена и фамилии пользователей | ID объекта пользователя | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |
>| User.ReadBasic.All | приложение | Основные данные пользователя | Объектный ID пользователя | [a22e0150-3615-46aa-b0a7-086c87a9f38d](https://docs.microsoft.com/microsoft-365-app-certification/azure/a22e0150-3615-46aa-b0a7-086c87a9f38d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API экспорта | Нет |  |  |  |  |

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

>У нас нет данных в системах партнеров

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

Эта информация предоставлена ASC Technologies AG о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

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
| Что вы не используете для вашего приложения? | ,<br/>- Неявные Flow OAuth2, если не требуется spa<br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
