---
title: Сведения о приложениях для PandaDoc от PandaDoc
ms.author: elmalova
author: elenamalova
ms.date: 08/03/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для PandaDoc, политики обработки данных, Microsoft Cloud App Security каталога приложений, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 4119b4540bd4326be32adb8a8f0b6bc999cb20c1
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427961"
---
# <a name="pandadoc"></a>PandaDoc

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 19 июля 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/769d6db6-6890-4f70-8088-5943fdeac3c5" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002927" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые PandaDoc Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | PandaDoc |
| Идентификатор | WA200002927 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | PandaDoc |
| URL-адрес веб-сайта-партнера | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL-адрес страницы Teams приложения | [https://www.pandadoc.com](https://www.pandadoc.com) |
| URL-адрес политики конфиденциальности | [https://www.pandadoc.com/privacy-notice/?utm_source=microso...](https://www.pandadoc.com/privacy-notice/?utm_source=microsoft-teams&amp;utm_medium=partner&amp;utm_campaign=2021-2-inbd-marketplace-websitevisit-pandadoc-privacy) |
| URL-адрес терминов использования | [https://www.pandadoc.com/terms-of-use/](https://www.pandadoc.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены PandaDoc о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Channel.ReadBasic.All | оба | получить списки каналов для каждой ранее полученной команды и получить ids дисков файлов для каждого канала. | Данные не хранятся | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.Read.All | оба | получить списки каналов для каждой ранее полученной команды и получить ids дисков файлов для каждого канала.  | Данные не хранятся | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| ChannelSettings.ReadWrite.All | оба | получить списки каналов для каждой ранее полученной команды и получить ids дисков файлов для каждого канала. | Данные не хранятся | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.Read.All | оба | Для получения ID-Microsoft Teams в том, что пользователь является непосредственным участником. После этого будут получать каналы для каждого идентификатора команды. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Directory.ReadWrite.All | оба | Для получения ID-Microsoft Teams в том, что пользователь является непосредственным участником. После этого будут получать каналы для каждого идентификатора команды. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.All | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Files.Read.Selected | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.Read.All | оба | получить списки каналов для каждой ранее полученной команды и получить ids дисков файлов для каждого канала. Документация https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp - ;tabs=http | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Group.ReadWrite.All | оба | получить списки каналов для каждой ранее полученной команды и получить ids дисков файлов для каждого канала. Документация https://docs.microsoft.com/en-us/graph/api/channel-list?view=graph-rest-1.0&amp - ;tabs=http | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| Team.ReadBasic.All | оба | для получения ID-Microsoft Teams групп в том, что пользователь является непосредственным участником. После этого будут получать каналы для каждого идентификатора команды. Чтобы получить ID-файлы хранилища файлов, сначала необходимо получить список команд, в которые вошел пользователь. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.Read.All | оба | Для получения ID-Microsoft Teams в том, что пользователь является непосредственным участником. После этого будут получать каналы для каждого идентификатора команды. Чтобы получить ID-файлы хранилища файлов, сначала необходимо получить список команд, в которые вошел пользователь. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamSettings.ReadWrite.All | оба | или получите ID-данные групп в Microsoft Teams, в которые пользователь является непосредственным участником. После этого будут получать каналы для каждого идентификатора команды. Чтобы получить ID-файлы хранилища файлов, сначала необходимо получить список команд, в которые вошел пользователь. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForTeam.All | оба | необходимо установить приложение на пользователя в Team и установить бота в чате. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | оба | необходимо установить приложение на пользователя в Team и установить бота в чате. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.Read.All | оба |  для получения ID-Microsoft Teams, в которые пользователь является непосредственным участником. После этого будут получать каналы для каждого идентификатора команды. Чтобы получить ID-файлы хранилища файлов, сначала необходимо получить список команд, в которые вошел пользователь. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| User.ReadWrite.All | оба |  для получения ID-Microsoft Teams, в которые пользователь является непосредственным участником. После этого будут получать каналы для каждого идентификатора команды. Чтобы получить ID-файлы хранилища файлов, сначала необходимо получить список команд, в которые вошел пользователь. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| email | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| offline_access | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| openid | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |
>| profile | оба | для пользователя sso из Tab (пример - https://github.com/OfficeDev/msteams-tabs-sso-sample-nodejs) . Необходимые для получения маркера пользователя с доступом к Microsoft Graph и дальнейшего получения файлов пользователей. | Данные не хранятся. | [f2d4eec7-3d3f-46b1-a094-9f7c733d260b](https://docs.microsoft.com/microsoft-365-app-certification/azure/f2d4eec7-3d3f-46b1-a094-9f7c733d260b) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| PandaDoc API | Нет |  |  |  |  |
>| Microsoft Graph | Нет |  |  |  |  |
>| Elementor | Нет |  |  |  |  |

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

>В наших соглашениях поставщиков рассматриваются соответствующие обязательства наших и наших поставщиков в отношении конфиденциальности и безопасности данных, и каждый год мы подвергаемся проверке безопасности и конфиденциальности наших ключевых поставщиков.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21283" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены PandaDoc о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Нет |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Нет |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/> |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
