---
title: Сведения о приложениях для DBit от Diamondsoft Solutions, LLC
ms.author: elmalova
author: elenamalova
ms.date: 04/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для DBit, политики обработки данных, сведения о Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 095ce62c1d0b193cd63105e2df3599f6eac3725c
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412459"
---
# <a name="dbit"></a>DBit

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 июня 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/b28bb657-8edd-47ae-a912-c5fc11b3e89e" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001536" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые компанией Diamondsoft Solutions, LLC корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | DBit |
| Идентификатор | WA200001536 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Diamondsoft Solutions, LLC |
| URL-адрес веб-сайта-партнера | [https://www.diamondsoftsolutions.com](https://www.diamondsoftsolutions.com) |
| URL-адрес политики конфиденциальности | [https://www.dbit.io/privacypolicy.html](https://www.dbit.io/privacypolicy.html) |
| URL-адрес терминов использования | [https://www.dbit.io/termsofuse.html](https://www.dbit.io/termsofuse.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены компанией Diamondsoft Solutions, LLC, о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | делегирована | Мы не храним Graph в нашей системе или базах данных. | Вход и чтение профиля пользователя | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| email | делегирована | Мы не храним Graph в нашей системе или базах данных. | Просмотр электронных адресов пользователей | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| offline_access | делегирована | Мы не храним Graph в нашей системе или базах данных. | Сохранение доступа к данным, к которым он был предоставлен | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| openid | делегирована | Мы не храним Graph в нашей системе или базах данных. | Вход пользователей | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |
>| profile | делегирована | Мы не храним Graph в нашей системе или базах данных. | Просмотр базовых профилей пользователей | [1533d702-7604-463a-9fa3-63077c425e76](https://docs.microsoft.com/microsoft-365-app-certification/azure/1533d702-7604-463a-9fa3-63077c425e76) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Создание приветствия | Мы не храним сведения о реестре в нашей системе или базах данных. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы не собираем эту информацию.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы используем Azure Cache Redis, максимальный срок службы данных в кэше — 300 минут. Элементы данных кэша шифруются с помощью AES256. Только служба приложений может подключаться к Azure Cache Redis с помощью SSL, строка подключения хранится в Azure Environmental Variable.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35912" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


