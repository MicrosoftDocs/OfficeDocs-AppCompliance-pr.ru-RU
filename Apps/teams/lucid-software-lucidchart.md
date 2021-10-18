---
title: Сведения о приложениях для Lucidchart lucid Software
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Lucidchart, политики обработки данных, сведения Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 753a8a5b68734d35d3d752812b14f80eb75ff2d6
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60438815"
---
# <a name="lucidchart"></a>Lucidchart

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/7f905be6-3226-4a4c-9c54-ab1edce3c99c" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381935" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые программным обеспечением Lucid в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Lucidchart |
| Идентификатор | WA104381935 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Lucid Software |
| URL-адрес веб-сайта-партнера | [https://www.lucidchart.com](https://www.lucidchart.com) |
| URL-адрес страницы Teams приложения | [https://lucidchart.zendesk.com/](https://lucidchart.zendesk.com/) |
| URL-адрес политики конфиденциальности | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL-адрес терминов использования | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены lucid Software о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | делегирована | Имя и адрес электронной почты. | Разрешения электронной почты, openid и профилей позволяют Lucidchart создавать маркер openid для пользователя и получать достаточно базовых данных о пользователе для регистрации учетной записи Lucidchart для них при необходимости. Для проверки данных, возвращаемой из Корпорации Майкрософт, мы запрашиваем общедоступный ключ, с помощью который подписан их ответ. Никакие другие данные не получаются из Корпорации Майкрософт и не отправляются в рамках нашего потока SSO. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| openid | делегирована | Имя и адрес электронной почты. | Разрешения электронной почты, openid и профилей позволяют Lucidchart создавать маркер openid для пользователя и получать достаточно базовых данных о пользователе для регистрации учетной записи Lucidchart для них при необходимости. Для проверки данных, возвращаемой из Корпорации Майкрософт, мы запрашиваем общедоступный ключ, с помощью который подписан их ответ. Никакие другие данные не получаются из Корпорации Майкрософт и не отправляются в рамках нашего потока SSO. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | делегирована | Имя и адрес электронной почты. | Разрешения электронной почты, openid и профилей позволяют Lucidchart создавать маркер openid для пользователя и получать достаточно базовых данных о пользователе для регистрации учетной записи Lucidchart для них при необходимости. Для проверки данных, возвращаемой из Корпорации Майкрософт, мы запрашиваем общедоступный ключ, с помощью который подписан их ответ. Никакие другие данные не получаются из Корпорации Майкрософт и не отправляются в рамках нашего потока SSO. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на Microsoft 365, могут использовать дополнительные API Microsoft, кроме Microsoft Graph для сбора или обработки идентифицируемых сведений об организации (OII). Список любых API Майкрософт, кроме microsoft Graph, которые использует это приложение.

>| **API** |  **Собран ли OII?** |  **Какие OII собираются?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| API JavaScript для Office | Да | Мы используем Office OneDrive javascript SDK для открытия выбора OneDrive файла с помощью OneDrive.open(). Мы не генерируем маркеры доступа и не запрашиваем OneDrive API. выбор OneDrive файла SDK делает это для нас. Мы видим только имена файлов, которые выбирает пользователь. |  | Если пользователь выбирает файл с OneDrive выбора файла, мы храним имя файла. |  |

#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Данные Lucidchart хранятся в AWS. |  | Мы не используем API Майкрософт. Мы используем openID для получения базовых пользовательских данных для выполнения SSO. Мы используем API их выборщика файлов, но это не дает нам доступа к файлам пользователя, кроме файлов, которые они представляют нам через выборщик. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы внося в журнал электронные почты и IP-адреса по соображениям безопасности и поддержки. В системе сторонних сторон все журналы записывают &amp; журналы. Доступ к журналам требует MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные Lucidchart хранятся в AWS. Он шифруется в покое и в пути. Lucidchart использует правила наименьших привилегий и MFA.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/12761" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

