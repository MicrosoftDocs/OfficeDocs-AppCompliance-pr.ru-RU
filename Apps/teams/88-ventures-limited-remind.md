---
title: Сведения о приложениях для remind by 88 Ventures Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Remind, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e2124ed68b2e9d750c8bc6a229eca0ccad200b5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552450"
---
# <a name="remind"></a>Remind

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 28 сентября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные корпорацией Майкрософт 88 Ventures Limited:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Remind |
| ID | WA200001444 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | 88 Ventures Limited |
| URL-адрес веб-сайта-партнера | [https://www.teamsreminder.app](https://www.teamsreminder.app) |
| URL-адрес политики конфиденциальности | [https://www.teamsreminder.app/#privacy](https://www.teamsreminder.app/#privacy) |
| URL-адрес терминов использования | [https://www.teamsreminder.app/#terms](https://www.teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены 88 Ventures Limited о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | делегирована | сведений, хранимых в базе данных | позволяет администратору просматривать пользовательский каталог организации для пользователей, которые установили общедоступные напоминания | 88546d4f-9973-4716-98e4-cd181c04bc2d |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| (1) Когда пользователь задает напоминание о сообщении, бот пытается получить имя человека, отправив сообщение для отображения этих сведений в списке напоминаний пользователя (2) Когда пользователь задает напоминание другому каналу или участнику чата, бот пытается получить удостоверение (пользователя или бота) и имя упомянутого пользователя, чтобы отобразить их в списке напоминаний пользователя. | (1) Когда пользователь задает напоминание о сообщении, бот пытается получить имя человека, отправив сообщение для отображения этих сведений в списке напоминаний пользователя (2) Когда пользователь задает напоминание другому каналу или участнику чата, бот пытается получить удостоверение (пользователя или бота) и имя упомянутого пользователя, чтобы отобразить их в списке напоминаний пользователя. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Функции телеметрии или ведения журнала не делятся EEUI и OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Шифрование в покое, двухфакторная проверка подлинности (2FA) для ограничения доступа к ИТ-инфраструктуре и данным клиентов, защищенные диапазоны IP между системами

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

