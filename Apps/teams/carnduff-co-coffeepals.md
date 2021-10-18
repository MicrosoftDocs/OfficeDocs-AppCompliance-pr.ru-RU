---
title: Сведения о приложениях для CoffeePals от Carnduff Co
ms.author: elmalova
author: elenamalova
ms.date: 07/27/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для CoffeePals, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 67ef18f421c6934a7f03d774e607884152da76ea
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/18/2021
ms.locfileid: "60427161"
---
# <a name="coffeepals"></a>CoffeePals

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 9 июля 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/0905c41d-9f67-4ab7-8d94-4e2da3d2ff08" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003040" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Корпорацией Майкрософт от Компании Карндафф Ко:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | CoffeePals |
| Идентификатор | WA200003040 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Carnduff Co |
| URL-адрес веб-сайта-партнера | [https://coffeepals.co](https://coffeepals.co) |
| URL-адрес страницы Teams приложения | [https://coffeepals.co/product](https://coffeepals.co/product) |
| URL-адрес политики конфиденциальности | [https://coffeepals.co/privacy](https://coffeepals.co/privacy) |
| URL-адрес терминов использования | [https://coffeepals.co/terms-of-service](https://coffeepals.co/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена Carnduff Co о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google Analytics, Stripe, Mailchimp, Heroku, MongoDB Atlas, AWS, Logentries | Адрес электронной почты пользователя, сведения об оплате (обрабатываются полосой), имя и фамилия | Наше приложение оплачивается, поэтому оно требует сведений о кредитных картах и контактных данных. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Мы обращаемся к их имени, чтобы ссылаться на пользователя в сообщениях, которые совпадают между пользователями для кофе и хранения электронного адреса, чтобы войти их в веб-приложение для сбора оплаты. Использование их имени делает работу более персонализированной, и мы используем адрес электронной почты в качестве уникального идентификатора и отправим им ссылку на вход. | Адрес электронной почты, имя и фамилия. | Данные хранятся, поэтому их не нужно извлекать каждый раз, когда они необходимы для совпадения, обмена сообщениями и входа пользователей. |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии приложений или журналах не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы можем изменять данные в системе, если отсутствуют данные из ошибки. Кроме того, мы можем добавлять и удалять данные по запросу наших клиентов. Мы следуем строгим протоколам защиты данных, описанным в https://coffeepals.co/security .

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/41839' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/41839" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения о удостоверениях

Эта информация предоставлена Carnduff Co о том, как это приложение обрабатывает проверку подлинности, авторизацию, лучшие практики регистрации приложений и другие критерии удостоверения.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интеграция с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
