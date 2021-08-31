---
title: Application Information for Cyberday by Digiturvamalli
ms.author: elmalova
author: elenamalova
ms.date: 08/09/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Cyberday, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: f2adf667a89ff8dcdd1a1f56b1f0ef91951f3eb1
ms.sourcegitcommit: 34fde42f42c623b37d1db154bf348bdc8b76a8c7
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/19/2021
ms.locfileid: "58407649"
---
# <a name="cyberday"></a>Cyberday

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 9 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/a8e43ae4-a97b-4d1a-b364-b27794da19a4" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001774" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Digiturvamalli Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Cyberday |
| Идентификатор | WA200001774 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Digiturvamalli |
| URL-адрес веб-сайта-партнера | [https://cyberday.ai](https://cyberday.ai) |
| URL-адрес страницы Teams приложения | [https://cyberday.ai](https://cyberday.ai) |
| URL-адрес политики конфиденциальности | [https://cyberday.ai/privacy](https://cyberday.ai/privacy) |
| URL-адрес терминов использования | [https://cyberday.ai/terms-of-use](https://cyberday.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены Digiturvamalli о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | делегирована | Использование электронной почты для идентификации пользователя + отображения для администраторов приложений, которые этот пользователь | Email, Teams ID пользователя | [1c7d277c-ff8a-4ea4-bc14-7d06314f8941](https://docs.microsoft.com/microsoft-365-app-certification/azure/1c7d277c-ff8a-4ea4-bc14-7d06314f8941) |
>| openid | делегирована | Использование пользовательского ID для идентификации пользователя | Email, Teams ID пользователя | [1c7d277c-ff8a-4ea4-bc14-7d06314f8941](https://docs.microsoft.com/microsoft-365-app-certification/azure/1c7d277c-ff8a-4ea4-bc14-7d06314f8941) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Heroku (Salesforce Inc.) | Teams и Teams домена клиента | Обработка этой информации необходима для выполнения контракта в соответствии с условиями использования. ID и домен клиента используются для подключения пользователей Cyberday к исправлению учетных записей организации (например, отобразить правильные рекомендации по безопасности). |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Журналы хранятся, например, при входе и проверке подлинности (хранение 2 дня), отправке и доставке электронной почты (хранение 90 дней) и трафике API/ошибках (хранение 90 дней). Кроме того, если не будет принято иное решение, все данные, которые они передали службе под управлением клиента, удаляются в течение шести месяцев после расторжения пользовательского соглашения.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Полные права администраторов (например, удаление, хранение, аудит, архивация) и другие требования, установленные для партнера в соглашениях по обработке данных отдельно с каждым обработчиком данных.

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

Эти сведения были предоставлены Digiturvamamalli о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Список типов поддерживаемых политик | Все |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/><br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API предварительного просмотра? | Нет |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
