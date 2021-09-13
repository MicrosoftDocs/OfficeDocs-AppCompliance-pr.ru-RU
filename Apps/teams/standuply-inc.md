---
title: Сведения о приложениях для standuply by Standuply Inc.
ms.author: elmalova
author: elenamalova
ms.date: 08/04/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Standuply, политики обработки данных, сведения Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 0b1613f70b1909faf9582a5a88e73273ae5bcc77
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286094"
---
# <a name="standuply"></a>Standuply

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 4 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/1250b735-e9df-4d5b-ae82-da96c55c64e4" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003001" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Standuply Inc. Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Standuply |
| Идентификатор | WA200003001 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Standuply Inc. |
| URL-адрес веб-сайта-партнера | [https://standuply.com](https://standuply.com) |
| URL-адрес страницы Teams приложения | [https://standuply.com](https://standuply.com) |
| URL-адрес политики конфиденциальности | [https://standuply.com/privacy-policy](https://standuply.com/privacy-policy) |
| URL-адрес терминов использования | [https://standuply.com/terms](https://standuply.com/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена standuply Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| MailboxSettings.Read | приложение | Локальный часовой пояс пользователя. Запуск отчетов с параметром &quot; Задать вопросы в локальном часовом поясе пользователя&quot; | P.3 https://standuply.com/privacy-policy | [e9f5cb58-89eb-4f80-9a6c-b73823b62176](https://docs.microsoft.com/microsoft-365-app-certification/azure/e9f5cb58-89eb-4f80-9a6c-b73823b62176) |
>| User.Read | делегирована | Имя пользователя и рис. Предоставление сводок отчетов от имени конкретного пользователя. | P.3 https://standuply.com/privacy-policy | [e9f5cb58-89eb-4f80-9a6c-b73823b62176](https://docs.microsoft.com/microsoft-365-app-certification/azure/e9f5cb58-89eb-4f80-9a6c-b73823b62176) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| https://standuply.com/security-subprocessors | P.3 https://standuply.com/privacy-policy | Мы используем AWS и другие поставщики инфраструктуры, которые не принадлежат Корпорации Майкрософт, поэтому это необходимо для работы службы. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| это необходимо для работы службы, чтобы предоставить сводки отчетов от Teams пользователей. | P.3 https://standuply.com/privacy-policy | Необходимо предоставить доступ к истории отчетов для пользователей приложений |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>https://standuply.com/privacy-policy

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>По отзывам служб и соглашениям об утверждении

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/42544' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/42544" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена standuply Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Нет |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
