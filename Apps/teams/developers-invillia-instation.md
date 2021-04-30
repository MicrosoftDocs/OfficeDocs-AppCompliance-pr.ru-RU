---
title: Сведения о приложениях для InStation разработчиками Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
description: Все доступные сведения о безопасности и соответствия требованиям для InStation, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 942790109cfa1493954f50be11e15ee36dbf2af2
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095320"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 6 августа 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые разработчиками Invillia корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | InStation |
| Идентификатор | WA200001701 |
| Возможности | Tab |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Разработчики Invillia |
| URL-адрес веб-сайта-партнера | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL-адрес политики конфиденциальности | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL-адрес терминов использования | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены разработчиками Invillia о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | делегирована | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | делегирована | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | делегирована | Позволяет приложению войти в организацию на первом шаге | активности и авалистичности. Позволяет приложению захватывать состояние пользователей; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | делегирована | Позволяет приложению войти в организацию на первом шаге, | активности и авалистичности. Позволяет приложению захватывать состояние пользователей; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | делегирована | магазины: id, почта, отображаемая фамилия, фамилия и изображение. Позволяет приложению искать пользовательские данные; | магазины: id, почта, отображаемая фамилия, фамилия и изображение. Позволяет приложению искать пользовательские данные; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | делегирована | магазины: id, почта, отображаемая фамилия, фамилия и изображение. Позволяет приложению искать пользовательские данные; | магазины: id, почта, отображаемая фамилия, фамилия и изображение. Позволяет приложению искать пользовательские данные; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | делегирована | Позволяет приложению захватывать основные сведения администратора&#180;в первом входе | Позволяет приложению захватывать основные сведения администратора&#180;в первом входе | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | делегирована | магазины: маркер и маркер обновления. Позволяет приложению выполнять обновление на маркере MS | магазины: маркер и маркер обновления. Позволяет приложению выполнять обновление на маркере MS | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | делегирована | Позволяет приложению войти в организацию на первом шаге | Позволяет приложению войти в организацию на первом шаге | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| profile | делегирована | Позволяет приложению захватить основные сведения администратора&#180;на первом входе; | Позволяет приложению захватить основные сведения администратора&#180;на первом входе; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы экономим только журналы использования пользователей в нашем приложении.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы экономим только журналы использования пользователей в нашем приложении. Ничего конфиденциального, не требующего шифрования, и только наши конкретные администраторы имеют доступ к этим данным.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

