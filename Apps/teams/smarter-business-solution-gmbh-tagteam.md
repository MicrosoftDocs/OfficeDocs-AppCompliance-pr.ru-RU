---
title: Сведения о приложениях для TagTeam от Smarter Business Solution GmbH
ms.author: elmalova
author: elenamalova
ms.date: 05/12/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для TagTeam, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 025d0040bdd58a01cd3993445c025b9a61f90822
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60408338"
---
# <a name="tagteam"></a>TagTeam

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 21 апреля 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/6d7f01cb-cfa5-48d9-beed-363d381ae32b" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002829" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые GmbH smarter business solution для Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | TagTeam |
| Идентификатор | WA200002829 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Smarter Business Solution GmbH |
| URL-адрес веб-сайта-партнера | [https://www.smarterbusiness.at](https://www.smarterbusiness.at) |
| URL-адрес страницы Teams приложения | [https://www.smarterbusiness.at/en/tagteam-help](https://www.smarterbusiness.at/en/tagteam-help) |
| URL-адрес политики конфиденциальности | [https://www.smarterbusiness.at/en/add-in-privacy-policy](https://www.smarterbusiness.at/en/add-in-privacy-policy) |
| URL-адрес терминов использования | [https://www.smarterbusiness.at/en/terms-of-use-for-tagteam](https://www.smarterbusiness.at/en/terms-of-use-for-tagteam) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена GmbH smarter Business Solution О том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMessage.Read.All | делегирована | Мы не собираем эти данные, а используем только для отображения бесед с тегами. Мы хотели бы изменить его на API поиска, но Graph API в настоящее время не поддерживает это.  | Нет | [6d7f01cb-cfa5-48d9-beed-363d381ae32b](https://docs.microsoft.com/microsoft-365-app-certification/azure/6d7f01cb-cfa5-48d9-beed-363d381ae32b) |
>| User.Read | делегирована | Отображение User-Information (например, имя) на вкладке | Нет | [6d7f01cb-cfa5-48d9-beed-363d381ae32b](https://docs.microsoft.com/microsoft-365-app-certification/azure/6d7f01cb-cfa5-48d9-beed-363d381ae32b) |
>| User.ReadBasic.All | делегирована | Отображение User-Avatars на вкладке | Нет | [6d7f01cb-cfa5-48d9-beed-363d381ae32b](https://docs.microsoft.com/microsoft-365-app-certification/azure/6d7f01cb-cfa5-48d9-beed-363d381ae32b) |
>| openid | делегирована | Только для SignIn — данные не хранятся | Отсутствует | [6d7f01cb-cfa5-48d9-beed-363d381ae32b](https://docs.microsoft.com/microsoft-365-app-certification/azure/6d7f01cb-cfa5-48d9-beed-363d381ae32b) |


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

>Мы храним только описанные данные в Azure Cosmos DB. Мы не делимся им с другими системами Parnter!

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/38164' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/38164" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена GmbH smarter Business Solution GmbH о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и выполнили все применимые методы, описанные в платформа удостоверений Майкрософт списке интеграции?  | Да |
| Использует ли ваше приложение MSAL (Microsoft Authentication Library) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Нет |
| Запрашивает ли ваше приложение наименьшие разрешения на привилегии для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение запрашивает динамически и постепенно? | Да |
| Поддерживает ли ваше приложение многотенантность? | Да |
| У вашего приложения есть конфиденциальный клиент? | Да |
| У вас есть все идентификаторы единого ресурса перенаправления, зарегистрированные для вашего приложения? | Да |
| Что вы не используете для вашего приложения? | - Перенаправление URL-адресов под диктовки,<br/><br/>- Поток учетных данных владельца ресурса (ROPC) |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Позволяет ли модель разрешений добиться успеха только в том случае, если клиентская приложение получает соответствующее согласие? | Да |
| Использует ли приложение API предварительного просмотра? | Да |
| Использует ли ваше приложение неподготовленные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

