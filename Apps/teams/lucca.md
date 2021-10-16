---
title: Сведения о приложениях для Lucca от Lucca
ms.author: elmalova
author: elenamalova
ms.date: 09/20/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Lucca, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 61f53fe653ebce1a833005082c8254392e61b2c1
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60411604"
---
# <a name="lucca"></a>Lucca

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 августа 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/53628f6a-ac66-4fde-8945-d639c8da4c0d" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001650" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Lucca Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Lucca |
| Идентификатор | WA200001650 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Lucca |
| URL-адрес веб-сайта-партнера | [https://www.lucca.fr](https://www.lucca.fr) |
| URL-адрес политики конфиденциальности | [https://www.lucca.fr/privacy-policy](https://www.lucca.fr/privacy-policy) |
| URL-адрес терминов использования | [https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/Ter...](https://cdn2.hubspot.net/hubfs/1582050/3-DOWNLOAD_FILES/TermsAndConditions.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Lucca о том, как это приложение собирает и сохраняет организационные данные и контроль, который будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| ChannelMember.Read.All | делегирована | Данные не собираются. Мы использовали их для фильтрации планирования для отображения. Только у пользователей, которые находятся в канале, отображается их планирование | Данные не хранятся | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Chat.ReadWrite | приложение | Данные не собираются и не используются. Приложение только после сообщения, которое содержит открепительных дня | Данные не хранятся | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| Group.Read.All | приложение | Мы собираем GroupId, чтобы узнать, в какой группе приложение должно отправлять сообщение с открепительными.  | Мы храним GroupId только для сохранения конфигурации, которую сделал пользователь. Это позволяет нам знать, в какой группе отправлять сообщение | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read | делегирована | Используется для входов в пользователей | Данные не хранятся | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| User.Read.All | приложение | Используется для чтения профилей пользователей | Данные не хранятся | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| email | делегирована | Используется для отображения электронной почты пользователя на вкладке приложения | Данные не хранятся | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| openid | делегирована | Используется для входа пользователя | Данные не хранятся | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |
>| profile | делегирована | Используется для отображения профиля пользователя на вкладке приложения | Данные не хранятся | [53628f6a-ac66-4fde-8945-d639c8da4c0d](https://docs.microsoft.com/microsoft-365-app-certification/azure/53628f6a-ac66-4fde-8945-d639c8da4c0d) |


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

>политика конечных пользователей

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена Lucca о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

