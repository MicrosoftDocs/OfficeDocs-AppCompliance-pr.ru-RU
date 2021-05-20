---
title: Сведения о приложениях для retro by Baltic Amadeus
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Retro, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553460"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 ноября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Майкрософт в компании Baltic Amadeus:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Retro |
| ID | WA200001892 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Baltic Amadeus |
| URL-адрес веб-сайта-партнера | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| URL-адрес политики конфиденциальности | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| URL-адрес терминов использования | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены Baltic Amadeus о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Приложение Retro имеет собственный веб-API, который не считается службой Майкрософт. Как упоминалось ранее, в нем хранится имя электронной почты и fullname для идентификации и соответствующих целей отображения контента. Эти данные больше нигде не отправляются. Кроме того, Retro имеет необязательный функционал для экспорта данных спринта в пространство слияния Atlassian. Для этого пользователю необходимо ввести имя пользователя и пароль. Эти данные используются только для проверки подлинности запросов для слияния API от имени пользователя и не хранятся и не регистрируются нигде. |  | Ретро имеет собственный веб-API, который также зарегистрирован в azure. Для его использования пользователю необходимо пройти проверку подлинности с помощью платформы удостоверений Майкрософт. Пользователю необходимо проверить подлинность, чтобы приложение Retro можно было серверировать определенный контент пользователя. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Бот имеет доступ к реестру, чтобы проверить, кто из членов присоединился или покинул команду. Исходя из этого, он добавляет или отключает пользователя из проекта, чтобы пользователь больше не отображался в списке участников спринта. | Электронная почта и FullName связаны друг с другом и хранятся в базе данных. Электронная почта используется для идентификации пользователей для отображения соответствующего контента для в журнале пользователя. FullName используется для отображения пупроз, чтобы другие пользователи могли знать, для кого они оценивают или пишут отзывы.  |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Нет. Единственный процесс, который создает телеметрию и журналы в приложении Retro, это ведение журнала ошибок. Журналы ошибок не включают euII или OII

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Данные хранятся в базе данных сервера azure sql server. Он хранится через приложение Retro и ретро-бот.
По умолчанию база данных azure sql имеет прозрачное шифрование данных включено.
База данных заблокирована за базовой проверкой подлинности.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

