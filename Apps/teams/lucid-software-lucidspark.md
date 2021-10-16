---
title: Сведения о приложениях для Lucidspark от Lucid software
ms.author: elmalova
author: elenamalova
ms.date: 06/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Lucidspark, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 97dd4245e0bba6f82adea01c08638f6cfc20698e
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60412228"
---
# <a name="lucidspark"></a>Lucidspark

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 13 мая 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/e9ab21fa-5fd5-48bb-a85d-4de7ced89cd1" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002583" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые программным обеспечением Lucid в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Lucidspark |
| Идентификатор | WA200002583 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Lucid Software |
| URL-адрес веб-сайта-партнера | [https://lucid.co](https://lucid.co) |
| URL-адрес страницы Teams приложения | [https://lucidchart.zendesk.com](https://lucidchart.zendesk.com) |
| URL-адрес политики конфиденциальности | [https://lucid.co/privacy](https://lucid.co/privacy) |
| URL-адрес терминов использования | [https://lucid.co/tos](https://lucid.co/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены lucid Software о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | делегирована | Имя и адрес электронной почты. | Разрешения электронной почты, openid и профилей позволяют Lucidspark создавать маркер openid для пользователя и получать достаточно базовых данных о пользователе для регистрации учетной записи Lucidspark для них при необходимости. Для проверки данных, возвращаемой из Корпорации Майкрософт, мы запрашиваем общедоступный ключ, с помощью который подписан их ответ. Никакие другие данные не получаются из Корпорации Майкрософт и не отправляются в рамках нашего потока SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| openid | делегирована | Имя и адрес электронной почты. | Разрешения электронной почты, openid и профилей позволяют Lucidspark создавать маркер openid для пользователя и получать достаточно базовых данных о пользователе для регистрации учетной записи Lucidspark для них при необходимости. Для проверки данных, возвращаемой из Корпорации Майкрософт, мы запрашиваем общедоступный ключ, с помощью который подписан их ответ. Никакие другие данные не получаются из Корпорации Майкрософт и не отправляются в рамках нашего потока SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |
>| profile | делегирована | Имя и адрес электронной почты. | Разрешения электронной почты, openid и профилей позволяют Lucidspark создавать маркер openid для пользователя и получать достаточно базовых данных о пользователе для регистрации учетной записи Lucidspark для них при необходимости. Для проверки данных, возвращаемой из Корпорации Майкрософт, мы запрашиваем общедоступный ключ, с помощью который подписан их ответ. Никакие другие данные не получаются из Корпорации Майкрософт и не отправляются в рамках нашего потока SSO. | [3557d5c0-bcab-410b-8a03-f7045aa48de0](https://docs.microsoft.com/microsoft-365-app-certification/azure/3557d5c0-bcab-410b-8a03-f7045aa48de0) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Данные Lucidspark и lucidchart хранятся в AWS и Snowflake | Имя организации, контактные данные и уровень лицензии | Мы не используем API Майкрософт. Мы используем openID для получения базовых пользовательских данных для выполнения SSO. Мы используем API их выборщика файлов, но это не дает нам доступа к файлам пользователя, кроме файлов, которые они представляют нам через выборщик. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы внося в журнал электронные почты и IP-адреса по соображениям безопасности и поддержки. В системе сторонних сторон все журналы записывают &amp; журналы. Доступ к журналам требует MFA.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные Lucidspark и lucidchart хранятся в AWS. Он шифруется в покое и в пути. Lucid использует правила наименьших привилегий и MFA.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/39482" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения предоставлены программным обеспечением Lucid о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

