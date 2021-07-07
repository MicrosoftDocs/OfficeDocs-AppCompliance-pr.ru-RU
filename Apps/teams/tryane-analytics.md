---
title: Сведения о приложениях для tryane Analytics от Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Tryane Analytics, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d5b5119f0c9897b6d59163ad03580744a7f822f0
ms.sourcegitcommit: 65d4afba6f46d45315b2a90d2b21ce1737707e7b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/02/2021
ms.locfileid: "53283575"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 28 сентября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные tryane в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Tryane Analytics |
| Идентификатор | WA200001827 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Tryane |
| URL-адрес веб-сайта-партнера | [https://www.tryane.com](https://www.tryane.com) |
| URL-адрес политики конфиденциальности | [https://analytics.tryane.com/docs/en/privacy_policy.html](https://analytics.tryane.com/docs/en/privacy_policy.html) |
| URL-адрес терминов использования | [https://analytics.tryane.com/docs/en/terms_of_use.html](https://analytics.tryane.com/docs/en/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Tryane о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ActivityFeed.Read | приложение |  | Чтение всех действий пользователей в командах | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | приложение |  | Все списки всех каналов с именами, описаниями | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | приложение |  | Список всех сообщений каналов&#8217; метаданных | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | приложение |  | Определение пользователей с лицензией Team в клиенте | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | приложение |  | Получите список всех команд, членов&#8217;и скрытых членов | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | приложение |  | Чтение всех действий пользователей в командах | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | приложение |  | Список всех каналов и свойств групп | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | делегирована | Пользовательский id, имя, адрес электронной почты, дата создания. Мы храним эти данные для обеспечения аналитики использования в Teams | Определение текущего пользователя во время подписки | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Организационное правило, описанное в нашей политике ИТ-безопасности и стандартах кодирования, не позволяет нам отображаться в журналах EUII и OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Где и как: база данных Azure/Azure для серверов PostgreSQL Кто доступ к ней: наше приложение и управление авторизацией администраторов баз данных: 
 - Управление отдельными авторизациями: RBAC
 - Управление системной авторизацией: частные конечные точки в виртуальных сетях Azure

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

