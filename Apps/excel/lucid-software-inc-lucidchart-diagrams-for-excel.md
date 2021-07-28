---
title: Сведения о приложениях для диаграмм Lucidchart для Excel lucid Software Inc
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для диаграмм Lucidchart для Excel, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: eedc4340815926a96f52e2abebc2d553f07583e3
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526035"
---
# <a name="lucidchart-diagrams-for-excel"></a>Диаграммы Lucidchart для Excel

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380194" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт по программному обеспечению Lucid:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Диаграммы Lucidchart для Excel |
| Идентификатор | WA104380194 |
| Office 365 поддерживаемые клиенты | Excel 2016 или позже на Mac, Excel 2013 или более поздней Windows, Excel в Интернете |
| Имя компании-партнера | Lucid Software Inc |
| URL-адрес веб-сайта-партнера | [https://www.lucidchart.com](https://www.lucidchart.com) |
| URL-адрес политики конфиденциальности | [https://www.lucidchart.com/pages/privacy](https://www.lucidchart.com/pages/privacy) |
| URL-адрес терминов использования | [https://www.lucidchart.com/pages/tos](https://www.lucidchart.com/pages/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Lucid Software Inc о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
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

