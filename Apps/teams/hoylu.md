---
title: Сведения о приложениях для Hoylu от Hoylu
ms.author: elmalova
author: elenamalova
ms.date: 07/20/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Hoylu, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4b63b3bd9cfec20a665d7fd112d2db09c280b594
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553090"
---
# <a name="hoylu"></a>Hoylu

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 20 июля 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/732e01bc-570a-43ac-9671-8c7fc4152662" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001573" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Hoylu корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Hoylu |
| ID | WA200001573 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Hoylu |
| URL-адрес веб-сайта-партнера | [https://hoylu.com](https://hoylu.com) |
| URL-адрес политики конфиденциальности | [https://hoylu.com/privacy-policy](https://hoylu.com/privacy-policy) |
| URL-адрес терминов использования | [https://hoylu.com/terms-of-use](https://hoylu.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Hoylu о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да. Ведение журнала делается для безопасности приложений, и EUII и OII собираются в виде имени и фамилии, электронной почты, IP-адреса, ID организации. Поставщиком журналов Hoylu является Datadog. Datadog сертифицирована на соответствие рамочной защите конфиденциальности МЕЖДУ ЕС и США и является регистратором STAR для Альянса облачной безопасности (CSA). Datadog также проводит ключевые независимые сторонние проверки своей безопасности, процессов и служб, включая завершение аудита SOC 2 Type II. Пользователь может запрашивать удаление этих сведений с помощью процесса, удовлетворяемого GDPR, в любое время.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные приложения хранятся в Облачные службы Microsoft Azure, и все используемые протоколы шифрования соответствуют требованиям FIPS 140-2. эти производственные данные доступны только администраторам инфраструктуры (PMA). Администрирование учетных записей для организации осуществляется через Azure AD с 2FA.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35933" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

