---
title: Сведения о приложениях для C.AI-бота по contexxt.ai
ms.author: elmalova
author: elenamalova
ms.date: 05/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для C.AI,его политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 5bb11c96f750701128470f3e1c61ea0f5d476233
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59285854"
---
# <a name="cai-adoption-bot"></a>C.AI Adoption Bot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 6 мая 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/f5323aab-3063-46cb-b632-ee01d95de494" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002633" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые contexxt.ai Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | C.AI Adoption Bot |
| Идентификатор | WA200002633 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | contexxt.ai |
| URL-адрес веб-сайта-партнера | [https://contexxt.ai](https://contexxt.ai) |
| URL-адрес страницы Teams приложения | [https://contexxt.ai/cai-adoption-bot/](https://contexxt.ai/cai-adoption-bot/) |
| URL-адрес политики конфиденциальности | [https://contexxt.ai/privacy-policy](https://contexxt.ai/privacy-policy) |
| URL-адрес терминов использования | [https://contexxt.ai/terms-of-use](https://contexxt.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены contexxt.ai о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.Read | приложение | Доступность пользователя, которая может отправлять советы в нужное время, а не во время фокуса, например. | Доступность анонимизированного пользователя, которая может отправлять советы в нужное время, а не во время фокуса, например. | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| ChannelMessage.Read.All | приложение | Microsoft Teams метаданных канала, например Private или нет, или количества бесед на канале для анализа использования Teams | Анонимные метаданные Microsoft Teams канала, например private или нет, или количество бесед на канале для анализа использования Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Chat.Read.All | приложение | Microsoft Teams метаданных чата, например, если сообщение понравилось или сколько чатов группы и 1:1 существует для анализа использования Teams | Анонимные Microsoft Teams метаданные чата, например, если сообщение понравилось или сколько групп и 1:1 чаты существуют для анализа использования Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Directory.Read.All | приложение | User Object-ID за возможность отправки советов для уточнения пользователя позже. | Hashed (anonymized) Object-ID пользователя за возможность отправки советов для уточнения пользователя позже. | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Group.Read.All | приложение | Microsoft Teams метаданных, таких как количество Teams и каналов для анализа использования Teams | Microsoft Teams метаданных, таких как количество Teams и каналов для анализа использования Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| Mail.Read | приложение | Метаданные Exchange Майкрософт, например количество электронных писем и групповых сообщений против 1:1 для анализа использования Exchange (по сравнению с Teams) | Анонимные метаданные microsoft Exchange, например количество сообщений электронной почты и групповых сообщений против 1:1 для анализа использования Exchange (по сравнению с Teams) | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |
>| User.Read.All | приложение | Microsoft Teams чата и метаданных беседы, например, если пользователь был упомянут для анализа использования Teams | Анонимные Microsoft Teams метаданные чата и беседы, например, если пользователь был упомянут для анализа использования Teams | [abe28a0d-6acc-47d8-9169-cfcc2553bc13](https://docs.microsoft.com/microsoft-365-app-certification/azure/abe28a0d-6acc-47d8-9169-cfcc2553bc13) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| В Bot Framework пользовательский id будет передаваться автоматически, чтобы иметь возможность общаться с пользователем. Дополнительные данные об использовании C.AI Analytics для индивидуализации учебного процесса для пользователя, следовательно, отправка только подходящих и полезных советов пользователям, которые могут не знать эти советы. | Нет |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Организации могут управлять (назначать или удалять) лицензии для своих пользователей. Организации могут назначать различные роли для управления лицензиями. Администраторы всегда могут запрашивать удаление данных.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/37589" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения были предоставлены contexxt.ai о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

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
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
