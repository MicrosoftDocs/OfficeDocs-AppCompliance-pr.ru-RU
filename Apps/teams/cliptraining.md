---
title: Сведения о приложениях для ClipTraining с помощью ClipTraining
ms.author: elmalova
author: elenamalova
ms.date: 07/08/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для ClipTraining, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f69ccfc65a7f5b3f27610b424bf27817436bc065
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413861"
---
# <a name="cliptraining"></a>ClipTraining

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 14 июня 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/6cb4b701-2a4f-4080-8a8a-d99f93905e15" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001687" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые ClipTraining в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | ClipTraining |
| Идентификатор | WA200001687 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | ClipTraining |
| URL-адрес веб-сайта-партнера | [https://www.cliptraining.com](https://www.cliptraining.com) |
| URL-адрес страницы Teams приложения | [https://www.cliptraining.com](https://www.cliptraining.com) |
| URL-адрес политики конфиденциальности | [https://www.cliptraining.com/privacy-policy/](https://www.cliptraining.com/privacy-policy/) |
| URL-адрес терминов использования | [https://www.cliptraining.com/eula/](https://www.cliptraining.com/eula/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены ClipTraining о том, как это приложение собирает и хранит организационные данные, а также о контроле, которое будет иметь организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| email | делегирована | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| offline_access | делегирована | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| openid | делегирована | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |
>| profile | делегирована | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | Адрес электронной почты, имя, фамилия для входа пользователя и переписки.  | [af089bb5-48be-413d-ad34-53c32799da7d](https://docs.microsoft.com/microsoft-365-app-certification/azure/af089bb5-48be-413d-ad34-53c32799da7d) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| не microsoft hosting service, non-Microsoft CRM | Имя, фамилия, адрес электронной почты | Необходимый для использования в бизнесе |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Имя, фамилия, адрес электронной почты. Хранение и удаление для политики ClipTraining, доступной по запросу

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Любые партнерские системы, к которые ClipTraining использует и имеет доступ, следует политикам ClipTraining. 

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/40836' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/40836" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения были предоставлены ClipTraining о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

