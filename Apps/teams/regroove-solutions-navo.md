---
title: Сведения о приложениях для Navo от Regroove Solutions
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Navo, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 11346ff15831615ac6b617d8d14f83f38c7de0a5
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283114"
---
# <a name="navo"></a>Navo

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 24 августа 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/d8653da2-4682-4b92-b659-485087957897" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001047" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые regroove Solutions для Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Navo |
| Идентификатор | WA200001047 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Regroove Solutions |
| URL-адрес веб-сайта-партнера | [https://regroove.ca ; https://getnavo.com](https://regroove.ca ; https://getnavo.com) |
| URL-адрес политики конфиденциальности | [https://getnavo.com/privacy-policy/](https://getnavo.com/privacy-policy/) |
| URL-адрес терминов использования | [https://getnavo.com/terms-of-service/](https://getnavo.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены regroove Solutions о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | приложение | Мы храним количество пользователей и запрашиваем его один раз за цикл вы выставления счета. Кроме того, в качестве ID для организации используется ИД аренды. | Позволяет подсчитать количество пользователей в аренде, используемой для вы выставления счета. Он также позволяет нам запрашивать сведения о группах, в которые находится пользователь, чтобы мы могли использовать обрезку безопасности для защиты определенных данных. Мы также запрашиваем id аренды организации. | 75ce4e02-e37b-479c-81c7-438348a2a251 |
>| User.Read | делегирована | Данные не хранятся | Вход и чтение профиля пользователя | 75ce4e02-e37b-479c-81c7-438348a2a251 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Мы храним id и количество пользователей в Stripe. |  | User.Read | Delegated | Вход и чтение профиля пользователя — данные не хранятся |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да, в приложении Аналитика мы храним идентификацию пользователя с проверкой подлинности и ID учетной записи пользователя (Tenancy Id).

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все данные, которые мы храним сами (не через службу, например Stripe или Application Аналитика), хранятся в базе данных Azure Cosmos. Все администраторы используют 2FA, и доступ ограничен подмножество наших сотрудников.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35974" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

