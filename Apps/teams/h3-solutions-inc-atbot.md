---
title: Информация о применении для AtBot от H3 Solutions, Inc.
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для AtBot, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3f56d0b3eb19f5bed8f7092507c8605af936b911
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552140"
---
# <a name="atbot"></a>AtBot

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/7c01af81-ae7d-416e-98a3-c139cae8cfb0" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381219" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная H3 Solutions, Inc. корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | AtBot |
| ID | WA104381219 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | H3 Solutions, Inc. |
| URL-адрес веб-сайта партнера | [https://atbot.io](https://atbot.io) |
| URL-адрес Teams страницы информации о приложениях | [https://admin.atbot.io/Docs/GettingStarted](https://admin.atbot.io/Docs/GettingStarted) |
| URL политики конфиденциальности | [https://admin.atbot.io/privacy](https://admin.atbot.io/privacy) |
| URL условий использования | [https://admin.atbot.io/terms](https://admin.atbot.io/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена H3 Solutions, Inc. о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | приложение | Название группы AAD, AAD Group GUID, UPN | Перечислите группы AAD, чтобы обеспечить безопасность обрезки навыков бота. Перечислите пользователей, чтобы иметь возможность применять лицензии. Перечислите пользователей для добавления в качестве администраторов/вкладчиков | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| Directory.Read.All | Делегированные | Название группы AAD, AAD Group GUID, UPN | Перечислите группы AAD, чтобы обеспечить безопасность обрезки навыков бота. Перечислите пользователей, чтобы иметь возможность применять лицензии. Перечислите пользователей для добавления в качестве администраторов/вкладчиков | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| People.Read | Делегированные | Нет | Перечислите людей в действии Get Person от Flow.  Позволяет боту извлекать людей из конечной точки /Люди в Microsoft Graph. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| User.Read | Делегированные | Идентификатор арендатора, UPN | Предоставляет нам доступ к идентификатору&#8217;и UPN, чтобы мы можно было связать созданные для пользователей flows/Logic Apps приложения. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| email | Делегированные | Нет | Предоставляет нам доступ к адресу электронной почты пользователя. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| offline_access | Делегированные | Токены доступа/Обновления. | Позволяет использовать маркер обновления для х/н пользователей. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| openid | Делегированные | Нет | Позволяет пользователям войти в систему. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |
>| profile | Делегированные | Имя участника-пользователя | Доступ к UPN пользователя. | 066a6b3a-f7a0-450a-98c7-34db1da31594 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Создание упоминаний в сообщениях чата, генерируемых ботами | Нет |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Идентификатор арендатора, UPN Мы используем Application Insights и наши журналы будут длиться в течение 90 дней, прежде чем автоматически архивировать. (https://docs.microsoft.com/azure/azure-monitor/app/data-retention-privacy)

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Администраторы имеют возможность удалять конфигурации ботов, которые могут содержать имена групп AAD/GUID.
После отмены сервиса все UPNs будут удалены из базы данных лицензирования.
Смотрите "Службы Azure" в Data Residency.  Большая часть данных, полученных с помощью AtBot, хранится в арендаторе клиента, и поэтому администраторы этого арендатора имеют полный контроль над данными там.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35672" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

