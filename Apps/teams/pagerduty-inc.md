---
title: Сведения о приложениях для PagerDuty по PagerDuty, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для PagerDuty, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 3729a9523ea4af31015f6e8111c6843e90d465f3
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287774"
---
# <a name="pagerduty"></a>PagerDuty

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 27 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/c8c302dc-4e77-4536-890d-0c2bffbef9cc" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001637" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые PagerDuty, Inc. корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | PagerDuty |
| Идентификатор | WA200001637 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | PagerDuty, Inc. |
| URL-адрес веб-сайта-партнера | [https://www.pagerduty.com](https://www.pagerduty.com) |
| URL-адрес страницы Teams приложения | [https://www.pagerduty.com/integrations/microsoft-teams](https://www.pagerduty.com/integrations/microsoft-teams) |
| URL-адрес политики конфиденциальности | [https://www.pagerduty.com/privacy-policy/](https://www.pagerduty.com/privacy-policy/) |
| URL-адрес терминов использования | [https://www.pagerduty.com/service-terms-use/](https://www.pagerduty.com/service-terms-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена PagerDuty, Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| OnlineMeetings.ReadWrite | делегирована | При создании собрания и получении ответа мы используем такие поля: join_web_url, audioConferencing. Эти поля необходимы для показа пользователю ссылки на собрание или альтернативных способов подключения к собранию. | Мы экономим: join_web_url, audioConferencing. Эти поля необходимы для показа пользователю ссылки на собрание или альтернативных способов подключения к собранию. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadForTeam | делегирована | Использование для добавления приложения pagerduty для чата. | Использование для добавления приложения pagerduty для чата. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsAppInstallation.ReadWriteForTeam.All | делегирована | Использование для добавления приложения pagerduty для чата. | Использование для добавления приложения pagerduty для чата. | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| TeamsTab.ReadWrite.All | делегирована | Использование для добавления приложения pagerduty в качестве вкладки на собрании | Использование для добавления приложения pagerduty в качестве вкладки на собрании | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.Read | делегирована | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| User.ReadBasic.All | делегирована | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| email | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные необходимы для получения сведений о собраниях пользователей и в Интернете | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| offline_access | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные переквалифицировать для получения сведений о собраниях пользователей и в Интернете | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| openid | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные переквалифицировать для получения сведений о пользователе и создания и получения собраний в Интернете | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| profile | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные переквалифицировать для получения сведений о пользователе и создания и получения собраний в Интернете | [05ffe668-5b27-45ff-a64d-b2ed6c475d7a](https://docs.microsoft.com/microsoft-365-app-certification/azure/05ffe668-5b27-45ff-a64d-b2ed6c475d7a) |
>| OnlineMeetings.ReadWrite | делегирована | При создании собрания и получении ответа мы используем такие поля: join_web_url, audioConferencing. Эти поля необходимы для показа пользователю ссылки на собрание или альтернативных способов подключения к собранию. | Мы экономим: join_web_url, audioConferencing. Эти поля необходимы для показа пользователю ссылки на собрание или альтернативных способов подключения к собранию. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam | делегирована | Использование для добавления приложения pagerduty для чата. | Использование для добавления приложения pagerduty для чата. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsAppInstallation.ReadForTeam.All | делегирована | Использование для добавления приложения pagerduty для чата. | Использование для добавления приложения pagerduty для чата. | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| TeamsTab.ReadWrite.All | делегирована | Использование для добавления приложения pagerduty в качестве вкладки на собрании | Использование для добавления приложения pagerduty в качестве вкладки на собрании | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.Read | делегирована | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| User.ReadBasic.All | делегирована | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | Используются данные: id, userPrincipalName . Он используется для получения пользователей microsoft teams, чтобы добавить их к собранию в качестве участников | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| email | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные необходимы для получения сведений о собраниях пользователей и в Интернете | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| offline_access | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные необходимы для получения сведений о собраниях пользователей и в Интернете | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| openid | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные переквалифицировать для получения сведений о пользователе и создания и получения собраний в Интернете | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |
>| profile | делегирована | Использование для запросов авторизации и маркеров. Используются данные: access_token, refresh_token, expires_in, область | access_token, refresh_token, expires_in, область. Эти данные переквалифицировать для получения сведений о пользователе и создания и получения собраний в Интернете | [8f79a561-d2f1-4a1e-8092-c2039043a40e](https://docs.microsoft.com/microsoft-365-app-certification/azure/8f79a561-d2f1-4a1e-8092-c2039043a40e) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Данные, которые поддерживает PagerDuty, ограничиваются данными машин из продуктов мониторинга, а сведения о PII ограничены: корпоративным адресом электронной почты, именем, фамилией и номером телефона. Список суб-процессоров с доступом к этим данным можно найти здесь: https://www.pagerduty.com/subprocessors/ | Данные, которые поддерживает PagerDuty, ограничиваются данными машин из продуктов мониторинга, а сведения о PII ограничены: корпоративным адресом электронной почты, именем, фамилией и номером телефона. Список суб-процессоров с доступом к этим данным можно найти здесь: https://www.pagerduty.com/subprocessors/ | Данные, которые поддерживает PagerDuty, ограничиваются данными машин из продуктов мониторинга, а сведения о PII ограничены: корпоративным адресом электронной почты, именем, фамилией и номером телефона. Список суб-процессоров с доступом к этим данным можно найти здесь. Дополнительные сведения о конфиденциальности данных можно https://www.pagerduty.com/subprocessors/ найти здесь: https://www.pagerduty.com/privacy-policy/ |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>PagerDuty требует, чтобы стандарты безопасности данных не менее строгие, чем те, которые поддерживаются PagerDuty, чтобы поддерживаться всеми поставщиками, с которыми мы переключаем данные, включая договорное обязательство в виде подписанного DPA. Дополнительные сведения о наших стандартах безопасности данных можно найти здесь: https://www.pagerduty.com/data-security-policy/

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

Эта информация предоставлена PagerDuty, Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, передовую практику регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
