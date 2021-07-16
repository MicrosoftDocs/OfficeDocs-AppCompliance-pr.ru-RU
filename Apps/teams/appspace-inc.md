---
title: Сведения о приложениях для Appspace по Appspace, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 07/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Appspace, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 7171a8574efe7757d024f4d9dd93056e7c206519
ms.sourcegitcommit: 419dd3878fdef5fdf3bc5a36d73a9c6b12eed6f9
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/16/2021
ms.locfileid: "53459570"
---
# <a name="appspace"></a>Appspace

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 8 июля 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/a9a866c4-e5cf-47f2-932c-db14cb89008f" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001738" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Корпорацией Майкрософт в Appspace, Inc.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Appspace |
| ID | WA200001738 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Appspace, Inc. |
| URL-адрес веб-сайта-партнера | [https://www.appspace.com](https://www.appspace.com) |
| URL-адрес страницы Teams приложения | [https://www.appspace.com](https://www.appspace.com) |
| URL-адрес политики конфиденциальности | [https://www.appspace.com/legal/privacy-policy/](https://www.appspace.com/legal/privacy-policy/) |
| URL-адрес терминов использования | [https://www.appspace.com/legal/user-agreement/](https://www.appspace.com/legal/user-agreement/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена Appspace, Inc. о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Team.ReadBasic.All | делегирована | Получите команды, к которой принадлежит пользователь. | Кэш приложения может содержать группы и ids, к которые имеет доступ учетная запись пользователя или службы. Эти данные остаются зашифрованными на протяжении всего жизненного цикла. | a9a866c4-e5cf-47f2-932c-db14cb89008f |
>| User.ReadBasic.All | делегирована | Ознакомьтесь с базовыми свойствами профилей других пользователей в организации от имени подписанного пользователя. К этим свойствам относятся отображаемое имя, имя и фамилия, адрес электронной почты, открытые расширения, а также фотография. Также позволяет приложению считывать весь профиль вошедшего пользователя. | Имя пользователя, подписанного пользователем, сохраняется, чтобы пользователи могли определять, какая учетная запись пользователя или службы связана с платформой Appspace. | a9a866c4-e5cf-47f2-932c-db14cb89008f |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы шифруем данные в наших системах, чтобы поддерживать полный контроль жизненного цикла данных.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35872' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35872" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена Appspace, Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
