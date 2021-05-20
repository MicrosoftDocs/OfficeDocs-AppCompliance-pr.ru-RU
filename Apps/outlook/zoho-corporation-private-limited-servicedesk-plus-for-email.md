---
title: Сведения о приложениях для ServiceDesk Plus для электронной почты от Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для ServiceDesk Plus для электронной почты, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dc342375eba7084f5afb31b0f879e46e959fa970
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553660"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus для электронной почты

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Zoho Private Limited корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | ServiceDesk Plus для электронной почты |
| ID | WA104381518 |
| Office 365 поддерживаемые клиенты | Outlook 2013 или более поздней Windows, Outlook 2016 или более поздней Outlook в Интернете |
| Имя компании-партнера | Zoho Corporation Private Limited |
| URL-адрес веб-сайта-партнера | [https://www.zoho.com/](https://www.zoho.com/) |
| URL-адрес политики конфиденциальности | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
| URL-адрес терминов использования | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=ru-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена корпорацией Zoho Private Limited о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | приложение |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | делегирована |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | делегирована |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | делегирована | ID электронной почты пользователя. | Позволяет пользователю войти и предоставляет приложению доступ к его upN, чтобы включить бесшумный вход. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | приложение |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | делегирована | Email ID, Name, Employee ID, Job title, Телефон, Mobile, Site, Department, Locale, Profile photo of the user. | Позволяет импортировать основные сведения пользователей из Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | делегирована | ID электронной почты пользователя. | Просмотр адреса электронной почты пользователя. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | делегирована |  | Поддержив доступ к данным, к ним вы получили доступ. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | делегирована |  | Просмотр основного профиля пользователя. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы не собираем EUII /PII в телеметрии и журналах. У нас есть скрипты, которые ища шаблоны и оповещают о его исправлении

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все данные шифруются в REST. Только уполномоченные лица имеют доступ к системе, которая в любом случае защищена доступом, полностью проверяемой для всех типов доступа. MFA на месте для доступа, авторизованные учетные записи поддерживаются в корпоративном каталоге и хост


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

