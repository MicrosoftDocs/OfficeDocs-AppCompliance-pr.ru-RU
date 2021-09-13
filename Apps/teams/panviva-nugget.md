---
title: Сведения о приложениях для Самородка от Panviva
ms.author: elmalova
author: elenamalova
ms.date: 10/12/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Nugget, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6108617e72e1996a335b53941989a707a6544337
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288409"
---
# <a name="nugget"></a>Nugget

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 12 октября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/4e85cc82-5187-4059-af36-a49e7db32bee" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001737" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Panviva Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Nugget |
| Идентификатор | WA200001737 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Panviva |
| URL-адрес веб-сайта-партнера | [https://www.panviva.com](https://www.panviva.com) |
| URL-адрес политики конфиденциальности | [https://www.panviva.com/privacy-policy/](https://www.panviva.com/privacy-policy/) |
| URL-адрес терминов использования | [https://www.panviva.com/terms-and-conditions](https://www.panviva.com/terms-and-conditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация была предоставлена Panviva о том, как это приложение собирает и хранит организационные данные и управление, которое будет иметь ваша организация над данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да.
Teams сохраняется: это необходимо, чтобы мы могли получить сведения о том, в котором находится клиент и является ли пользователь администратором или нет.
Teams id организации. Это сохраняется, чтобы мы могли получить пользователей в клиенте и получить сведения о подписке для этого конкретного клиента.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Мы используем Azure CosmosDB для хранения всех данных приложений. Для доступа к данным требуется конечная точка и ключ, которые вводятся в службу конфигурации, которая используется для доступа к данным. Служба конфигурации обрабатывает запросы только с помощью маркера носителей, который он получает в запросе от службы приложений-ботов. Этот маркер изначально создается okta, когда пользователь входит в бот в интерфейсе Team. Эти данные могут быть доступны администраторам Panviva, которым необходимо оговарить Microsoft Azure платформу с помощью проверки подлинности 2-х факторов. Имя электронной почты и пользователя хранятся в OKTA и могут быть доступны только с закрытым ключом, который хранится в хранилище ключей, которое затем получает доступ к службе конфигурации. Только служба конфигурации имеет доступ к хранилище ключей с помощью управляемых удостоверений, чтобы учетные данные не хранились в приложении.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36079" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

