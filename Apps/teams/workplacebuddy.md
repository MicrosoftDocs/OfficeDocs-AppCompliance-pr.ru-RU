---
title: Сведения о приложениях для WorkplaceBuddy по WorkplaceBuddy
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для WorkplaceBuddy, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: cfbab9d138e1ee0fa846f8c9e3454f7af6c86c29
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286841"
---
# <a name="workplacebuddy"></a>WorkplaceBuddy

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/6fef6052-d84d-4071-b679-8b542512a621" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001238" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые службой WorkplaceBuddy корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | WorkplaceBuddy |
| Идентификатор | WA200001238 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | WorkplaceBuddy |
| URL-адрес веб-сайта-партнера | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL-адрес страницы Teams приложения | [https://www.workplacebuddy.com](https://www.workplacebuddy.com) |
| URL-адрес политики конфиденциальности | [https://www.workplacebuddy.com/privacy-policy.pdf](https://www.workplacebuddy.com/privacy-policy.pdf) |
| URL-адрес терминов использования | [https://www.workplacebuddy.com/terms-of-use.pdf](https://www.workplacebuddy.com/terms-of-use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена WorkplaceBuddy о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | делегирована | Мы синхронизируйте эти данные, чтобы позволить вкладке WorkplaceBuddy работать Teams и нацелить определенных пользователей с помощью чат-бота | Только имя, ID и члены | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| Group.Read.All | делегирована | Мы синхронизируйте эти данные, чтобы позволить вкладке WorkplaceBuddy работать Teams и нацелить определенных пользователей с помощью чат-бота | Только имя, ID и члены | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.Read | делегирована | Мы синхронизируйте эти данные, чтобы пользователи могли войти в систему | Имя, электронная почта, изображение профиля, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |
>| User.ReadBasic.All | делегирована | Мы синхронизируйте эти данные, чтобы пользователи могли войти в систему | Имя, электронная почта, изображение профиля, ID | [39073da9-c47c-4da8-b57a-3786461db8f4](https://docs.microsoft.com/microsoft-365-app-certification/azure/39073da9-c47c-4da8-b57a-3786461db8f4) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Мы нуждаемся в этих данных, чтобы обеспечить персонализированный опыт | Имя, электронная почта, ID | Мы нуждаемся в этих данных, чтобы обеспечить персонализированный опыт |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Н/Д

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

Эта информация предоставлена WorkplaceBuddy о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

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
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/><br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
