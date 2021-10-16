---
title: Сведения о приложениях для prezi Video от Prezi
ms.author: elmalova
author: elenamalova
ms.date: 05/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии требованиям для Prezi Video, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a6e3cf632919160819471385eff35cdf82f005e3
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60414966"
---
# <a name="prezi-video"></a>Prezi Video

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 23 июня 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/78bbd675-511e-41a2-9a1a-8793920efa9e" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001577" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Prezi в Корпорацию Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Prezi Video |
| Идентификатор | WA200001577 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Prezi |
| URL-адрес веб-сайта-партнера | [https://prezi.com](https://prezi.com) |
| URL-адрес политики конфиденциальности | [https://prezi.com/privacy-policy/](https://prezi.com/privacy-policy/) |
| URL-адрес терминов использования | [https://prezi.com/terms-of-use/](https://prezi.com/terms-of-use/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Prezi о том, как это приложение собирает и хранит организационные данные и контроль, который будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Подробные сведения можно посетить https://prezi.com/privacy-policy/ |  | Для интеграции вместе с 1 используются следующие API/SDK. Botbuilder-SDK (python): с помощью этого SDK мы храним Azure Active Directory объекта (который API называется aad_object_id). Нам нужны эти сведения для Microsoft Teams пользователя с любым контентом, связанным с Prezi Video, созданным prezi.com.  2. Botbuilder-js (javascript): никакие Microsoft Teams не собираются с помощью этого SDK. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| Бот не имеет доступа к указанным данным реестра. | Бот не имеет доступа к указанным данным реестра. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В журналах приложения не отображаются EUII или OII.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>В базе данных RDS хранятся следующие сведения:

1. Azure Active Directory объекта (именуемая API как aad_object_id) хранится для получения видео Microsoft Teams пользователя&#8217;s. Данные aad_object_id надежно извлекаются с помощью&#8217;microsoft&#8217;ботстроитель sdk на наших серверах.

2. Видео ссылки, созданные на prezi.com. Контент, созданный prezi.com, хранится в разделе 14 в следующем URL-адресе: https://prezi.com/privacy-policy/ 

Права доступа к внешним системам с высоким уровнем риска (например, AWS) управляются через сторонную единую платформу управления удостоверениями и доступом (OneLogin).

Политика паролей и многофакторная проверка подлинности применяются для персонала в единой платформе управления удостоверением и доступом. В индивидуальном порядке многофакторная проверка подлинности с IP-адресов office не требуется.

Службы и базы данных, которые по умолчанию находятся в AWS, недоступны нигде; Явные правила входящие должны добавляться вручную.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/17887" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


