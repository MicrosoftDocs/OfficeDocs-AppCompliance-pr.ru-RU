---
title: Сведения о приложениях для Asana от Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
description: Вся доступная информация о безопасности и соответствии требованиям для Asana, политики обработки данных, сведения Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 04d0208b5177cc289f80534f83208b1a6d96d3af
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095581"
---
# <a name="asana"></a>Asana

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 2 ноября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/f0e33e18-08fc-4511-a2a7-c6bdff367263" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001727" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные Asana корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Asana |
| Идентификатор | WA200001727 |
| Возможности | Бот, вкладка, расширение обмена сообщениями |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Asana |
| URL-адрес веб-сайта-партнера | [https://asana.com/?noredirect&amp;utm_source=asana_inproduct &amp; ut...](https://asana.com/?noredirect&amp;utm_source=asana_inproduct&amp;utm_medium=organic_inproduct&amp;utm_campaign=msft_teams_launch) |
| URL-адрес политики конфиденциальности | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL-адрес терминов использования | [https://asana.com/terms#terms-of-service](https://asana.com/terms#terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена Asana о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Надстройка передает основные сведения электронной почты (отправитель, recepient, субъект, тело) и вложения в Asana по запросу пользователя. |  | Электронная почта . В настоящее время открыта электронная почта, когда отображается в области задач. — в настоящее время читает открытые вложения электронной почты для загрузки в задачи Asana. — Это позволяет пользователям быстро выполнять задачи в Asana с помощью информации из электронных писем. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Наше приложение регистрит только сведения, относящиеся к данным Asana. Единственный раз, когда мы регистрим все, что связано с Outlook данными пользователя, это когда пользователь явно прикрепит электронную почту или загрузит вложение в Asana, и даже в этом случае мы не регистрим содержимое. Краткосрочные журналы существуют на серверах, которые могут включать некоторые пользовательские данные, но они являются эфемерными и ограничены периодами менее 72 часов.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Enterprise клиенты имеют гарантированное шифрование в покое с помощью AES-256. Данные хранятся в веб-службах Amazon, а AWS управляет ключами шифрования с помощью системы управления ключами. У нас есть 2FA для всех администраторов. Доступ предоставляется по принципу наименьших привилегий.
Администраторы организации Asana имеют возможность настроить учетные записи SAML, SCIM, Service и просматривать данные, которые помещаются в средство. Администраторы могут запрашивать полный организационный экспорт из консоли администрирования и аудита по мере необходимости.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

