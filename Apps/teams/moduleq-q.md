---
title: Сведения о приложениях для Q by ModuleQ
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Q, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3424ac372f46be0fc9834611fb1a0d57c69831a4
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551909"
---
# <a name="q"></a>Q

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 17 марта 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/72bb25c7-3644-4318-8249-a08e5493a520" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381433" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые ModuleQ в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Q |
| ID | WA104381433 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | ModuleQ |
| URL-адрес веб-сайта-партнера | [https://moduleq.com](https://moduleq.com) |
| URL-адрес политики конфиденциальности | [https://moduleq.com/privacy-policy/](https://moduleq.com/privacy-policy/) |
| URL-адрес терминов использования | [https://moduleq.com/terms-of-service/](https://moduleq.com/terms-of-service/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены moduleQ о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | приложение | сохраняет данные собраний, за исключением тела сообщения и любых вложений | Позволяет приложению читать события календаря пользователя, чтобы разумно понять бизнес-приоритеты пользователя. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Group.Read.All | делегирована | Нет | Позволяет приложению взаимодействовать в команде для обмена контентом. | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| Mail.Read | приложение | сохраняет данные электронной почты, за исключением тела сообщения и вложений | Позволяет приложению читать почту пользователя, чтобы разумно понимать бизнес-приоритеты пользователя | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read | делегирована | маркеры электронной почты и проверки подлинности пользователей | Позволяет пользователю войти и связать свою учетную запись Office 365 с учетной записью ModuleQ | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |
>| User.Read.All | делегирована | Нет | Разрешить приложению получить список Teams, в который входит пользователь. Используется только для совместного использования  | 418a1ee4-ca76-4b38-b4b3-8cca25417a6c |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы регистрим внутренний GUID пользователя и организационные имена и домены. На данный момент нет элементов управления архива или удаления.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные хранятся в облаке Microsoft Azure нескольких микрослужб в соответствии с их функцией. Все идентифицируемые пользователем данные шифруются на стороне клиента с помощью шифрования AES-256 перед передачей для хранения. Данные могут просматриваться инженерами для отладки с одобрения нашего высшего руководства. Доступ к данным контролируется с помощью внутреннего VPN.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35844" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

