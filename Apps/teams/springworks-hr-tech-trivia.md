---
title: Сведения о приложениях для Trivia по hr Tech Springworks
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
description: Вся доступная информация о безопасности и соответствии требованиям для Trivia, политики обработки данных, сведения Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f13ce283151405688c68d16c79d7d68498a3635e
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/30/2021
ms.locfileid: "52094272"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 13 января 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые hr Tech Springworks в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Trivia |
| Идентификатор | WA200001956 |
| Возможности | Бот, вкладка |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Springworks HR Tech |
| URL-адрес веб-сайта-партнера | [https://springworks.in/](https://springworks.in/) |
| URL-адрес страницы Teams приложения | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL-адрес политики конфиденциальности | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL-адрес терминов использования | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены hr Tech Springworks о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | делегирована | Нет | Чтобы получить список Teams, что пользователь является частью | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Team.ReadBasic.All | делегирована | Да, хранение списка команд, в которые был добавлен бот | Сбор базовых сведений обо всех командах, присутствующих в рабочей области | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | делегирована | Да, для хранения уникального aadObjectId пользователя. Кроме того, различные сведения о пользователе, как имя пользователя, электронная почта и т.д. и отобразить его на панели мониторинга Trivia | Сведения о всех пользователях, присутствующих в рабочей области | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| openid | делегирована | Да, для хранения пользователей, которые впишутся в приложение. |  Разрешить как пользователю использовать приложение со своей учетной записью, так и приложение для использования данных пользователя | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| profile | делегирована | Да, для хранения пользовательских ИД и имен хостов викторин и других функций и уникально их идентифицировать. | Чтобы прочитать основные сведения о профиле пользователя, например имя пользователя, по электронной почте | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, Mailchimp, Stripe.  | Имя клиента, электронная почта, IP-адрес, сведения об оплате | Мы используем эти третьи стороны, чтобы предоставить нашим клиентам наилучший клиентский опыт |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Эти данные используются для отображения и хранения списка участников викторины и других таких функций. | Имя, электронная почта | Да, хранение данных хозяина и участников викторин и других функций для аналитики и связи с хостом в случае ошибок |



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>OII: имя организации, ID клиента отображаются в журналах; EUII: aad Object ID, полное имя, электронная почта отображаются в журналах. у нас есть период хранения 30 дней, который журналы автоматически удаляются. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные, хранимые в RDS, AWS. шифруется. Доступ имеется только к DevOps инженеру, инженеру и основателю

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эти сведения были предоставлены hr Tech Springworks о том, как это приложение обрабатывает проверку подлинности, авторизацию, передовую практику регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
