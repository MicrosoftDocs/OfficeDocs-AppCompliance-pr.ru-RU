---
title: Сведения о приложениях для PlayQuiz - Aprende &amp; Juega by TeamsChamp
ms.author: elmalova
author: elenamalova
ms.date: 05/11/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для PlayQuiz - Aprende Juega, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре &amp; CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 2d538edf2b96311ea7f2611a33d2362786453ee3
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59286089"
---
# <a name="playquiz---aprende-amp-juega"></a>PlayQuiz — Aprende &amp; Juega

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 11 мая 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/d36eac22-ff28-4392-9ba7-6e32151b9894" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002820" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые TeamsChamp в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | PlayQuiz — Aprende &amp; Juega |
| Идентификатор | WA200002820 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | TeamsChamp |
| URL-адрес веб-сайта-партнера | [https://www.encamina.com](https://www.encamina.com) |
| URL-адрес страницы Teams приложения | [https://www.teamsquiz.com](https://www.teamsquiz.com) |
| URL-адрес политики конфиденциальности | [https://www.teamsquiz.com/en/privacy-policy/](https://www.teamsquiz.com/en/privacy-policy/) |
| URL-адрес терминов использования | [https://www.teamsquiz.com/en/terms/](https://www.teamsquiz.com/en/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены teamsChamp о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | делегирована | Имя, электронная почта и изображение профиля пользователя | электронной почты, для записи в приложение и имени для отображения его в приложении | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |
>| User.ReadBasic.All | делегирована | Имя, электронная почта и изображение профиля | не храня эти данные, только считывая их для отображения в leaderboad (application) | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |
>| openid | делегирована | просмотр базового профиля пользователя | электронной почты, для записи в приложении и имени для отображения его в приложении | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |
>| profile | делегирована | Чтение базового профиля пользователя | электронной почты, для записи в приложении и имени для отображения его в приложении | [f3277edf-4f66-4e94-853b-cc1f1e2914f8](https://docs.microsoft.com/microsoft-365-app-certification/azure/f3277edf-4f66-4e94-853b-cc1f1e2914f8) |


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

>удаление, хранение, аудит, архивация, все управления в приложении

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39114" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены teamsChamp о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

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
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
