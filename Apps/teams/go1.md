---
title: Сведения о приложениях для Go1 по Go1
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Go1, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f812e25e3e5b894d7b54da886637513cb677702a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553120"
---
# <a name="go1"></a>Go1

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 июня 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/c859de61-8a6b-42e6-ba88-f639df33bc72" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001484" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Go1 в Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Go1 |
| ID | WA200001484 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Go1 |
| URL-адрес веб-сайта-партнера | [https://www.go1.com/](https://www.go1.com/) |
| URL-адрес политики конфиденциальности | [https://www.go1.com/en-au/terms/privacy-policy](https://www.go1.com/en-au/terms/privacy-policy) |
| URL-адрес терминов использования | [https://www.go1.com/en-au/terms/user-terms](https://www.go1.com/en-au/terms/user-terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена в Go1 о том, как это приложение собирает и хранит организационные данные, а также о контроле, которое будет иметь организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Files.ReadWrite.All | приложение | приложение не хранит данные файлов | позволяет пользователям загружать и обмениваться файлами из onedrive | c859de61-8a6b-42e6-ba88-f639df33bc72 |
>| Group.ReadWrite.All | приложение | Teams и имя канала и уникальный id хранятся для поддержки среды обучения, управляющей приложением | позволяет приложению динамически настроить Teams и каналы для поддержки структурированного обучения в Teams среде | c859de61-8a6b-42e6-ba88-f639df33bc72 |
>| User.Read.All | приложение | имена пользователей, электронная почта и UPN, хранимые для предоставления непосредственного личного опыта для пользователя | позволяет использовать для подписания и поддержки обмена ресурсами обучения между членами группы | c859de61-8a6b-42e6-ba88-f639df33bc72 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Пользователи первого и последнего имени могут быть совместно с поставщиками контента GO1 во время воспроизведения контента курса. Это общий доступ только в тех случаях, когда поставщик контента требует этого для поставщика персонализированого обучения. |  | Недоступно |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>GO1 минимизирует хранение любых персональных или организационных данных. Журналы приложений, которые хранят эти данные, удаляются в течение 90 дней после создания.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>2FA требуется для всех систем персонала. Доступ к системе GO1, управляемый ролью. Доступ к производственным системам предоставляется только ролям, которые требуют доступа к выполнению своих заданий. Внутренние политики требуют, чтобы данные всегда шифролись при транзите и в покое.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/16262" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

