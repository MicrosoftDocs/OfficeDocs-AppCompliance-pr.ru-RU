---
title: Сведения о приложениях для Org@Work от Lundano
ms.author: elmalova
author: elenamalova
ms.date: 08/10/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Org@Work, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 81e59d53704529ed26aa6760f3cd00799f77deaa
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287425"
---
# <a name="orgwork"></a>Org@Work

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 10 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/b9f5d3b0-424e-473d-bcbe-dd01f17f9a41" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002461" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Lundano корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Org@Work |
| Идентификатор | WA200002461 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Lundano |
| URL-адрес веб-сайта-партнера | [https://www.lundano.com/en/](https://www.lundano.com/en/) |
| URL-адрес страницы Teams приложения | [https://www.lundano.com/orgatwork/index.html#](https://www.lundano.com/orgatwork/index.html#) |
| URL-адрес политики конфиденциальности | [https://cp.lundano.com/privacy_en.html](https://cp.lundano.com/privacy_en.html) |
| URL-адрес терминов использования | [https://cp.lundano.com/Terms_en.html](https://cp.lundano.com/Terms_en.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Lundano о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | делегирована | Мы храним данные. Мы просто используем данные для входа пользователя в Org@work | Нет | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| email | делегирована | Мы храним данные. Мы просто используем данные для входа пользователя в Org@work | Нет | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| offline_access | делегирована | Мы храним данные. Мы просто используем данные для входа пользователя в Org@work | Нет | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| openid | делегирована | Мы храним данные. Мы просто используем данные для входа пользователя в Org@work | Нет | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |
>| profile | делегирована | Мы храним данные. Мы просто используем данные для входа пользователя в Org@work | Нет | [aa1c54a1-f482-424d-9389-dbd131233483](https://docs.microsoft.com/microsoft-365-app-certification/azure/aa1c54a1-f482-424d-9389-dbd131233483) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Чтобы его подтвердить, необходимо упоминают имя сотрудника для руководителя планирования. | Имена первых &amp; сотрудников, адрес электронной почты, рабочее место и организация | Эти сведения необходимы Org@Work планирования для завершения рабочего &amp; процесса |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Политика конечных пользователей, договорное соглашение и удаление

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36914' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36914" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена Lundano о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | Сотрудник, менеджер планирования и администратор |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Нет |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/>- Неявные Flow OAuth2, если не требуется spa<br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
