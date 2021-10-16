---
title: Сведения о приложениях для TeamSticker by Communitio от Communitio Corporation
ms.author: elmalova
author: elenamalova
ms.date: 01/19/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для TeamSticker by Communitio, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: d90eba269fb77fa8b86d20da16ef70baa72d686c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411817"
---
# <a name="teamsticker-by-communitio"></a>TeamSticker by Communitio

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 5 января 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/bceca1f0-723f-44d0-b732-b3506c0a641d" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000894" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Communitio Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | TeamSticker by Communitio |
| Идентификатор | WA200000894 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Communitio Corporation |
| URL-адрес веб-сайта-партнера | [https://www.teamsuite.biz](https://www.teamsuite.biz) |
| URL-адрес страницы Teams приложения | [https://www.teamsuite.biz/feature/](https://www.teamsuite.biz/feature/) |
| URL-адрес политики конфиденциальности | [https://www.teamsuite.biz/privacy/](https://www.teamsuite.biz/privacy/) |
| URL-адрес терминов использования | [https://www.teamsuite.biz/terms/](https://www.teamsuite.biz/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена корпорацией Communitio о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Chat.ReadWrite | приложение |  Потому что сообщения приложения для чата. | Приложение не сохраняет данные. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| Group.ReadWrite.All | оба | Приложение собирает групповой id и имя группы. | Приложение сохраняет групповую и именную пару. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| User.Read | делегирована | Приложение собирает изображение профиля пользователя. | Приложение сохраняет изображение профиля пользователя для отображения значка пользователя. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| User.Read.All | оба | Приложение собирает объект пользователя ObjectId /email/name, чтобы найти пользователя для отправки карты. | Приложение не сохраняет данные в этом случае. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| offline_access | делегирована | Приложение собирает маркер API пользователя для использования User.Read / User.Read.All в фоновом режиме. | Приложение сохраняет маркер API пользователя для использования User.Read / User.Read.All в фоновом режиме. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| openid | делегирована | Данные не собираются. | Приложение использует это разрешение для входа в openid. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |
>| profile | делегирована | Приложение собирает объект пользователя ObjectId /email/name. | Приложение сохраняет объектидов пользователя / электронной почты / имя. | [bceca1f0-723f-44d0-b732-b3506c0a641d](https://docs.microsoft.com/microsoft-365-app-certification/azure/bceca1f0-723f-44d0-b732-b3506c0a641d) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>|  Bot Framework REST API | Нет |  |  |  |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Потому что у него есть разрешение User.Read.All. | Нет |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Недоступно

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36366" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена корпорацией Communitio о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

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
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

