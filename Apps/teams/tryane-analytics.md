---
title: Информация о применении для Tryane Analytics от Tryane
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Tryane Analytics, ее политики обработки данных, ее Microsoft Cloud App Security информации каталога приложений и информации о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 265fa798414c907f25690252e1714bebfdbdde1b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551109"
---
# <a name="tryane-analytics"></a>Tryane Analytics

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 28 сентября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/87631b95-fcd9-46e9-8d86-3d5205c04fec" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001827" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Tryane корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Tryane Analytics |
| ID | WA200001827 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Tryane |
| URL-адрес веб-сайта партнера | [https://tryane.com/en/produit/tat/](https://tryane.com/en/produit/tat/) |
| URL политики конфиденциальности | [https://tryane.com/tryane-analytics/privacy_policy.html](https://tryane.com/tryane-analytics/privacy_policy.html) |
| URL условий использования | [https://tryane.com/tryane-analytics/terms_of_use.html](https://tryane.com/tryane-analytics/terms_of_use.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Tryane о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые приложение собирает.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| ActivityFeed.Read | приложение |  | Читать все действия пользователей в командах | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Channel.ReadBasic.All | приложение |  | Все список всех каналов с именами, описаниями | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| ChannelMessage.Read.All | приложение |  | Перечислите все сообщения каналов&#8217; метаданные | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Directory.Read.All | приложение |  | Идентификация пользователей с лицензией команды в арендаторе | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Member.Read.Hidden | приложение |  | Получить список всех команд, членов команды&#8217;и скрытых членов | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Reports.Read.All | приложение |  | Читать все действия пользователей в командах | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| Team.ReadBasic.All | приложение |  | Перечислите все каналы и свойства команд | 9b03f15d-1219-4b2f-9699-640be54e1319 |
>| User.Read | Делегированные | Идентификатор пользователя, имя, адрес электронной почты, дата создания. Мы храним эти данные для того, чтобы обеспечить аналитику использования Teams | Определить текущего пользователя во время подписки | 9b03f15d-1219-4b2f-9699-640be54e1319 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Организационное правило, описанное в нашей политике ИТ-безопасности и стандартах кодирования, не позволяет нам отображать EUII и OII в журналах

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Где/как: База данных Azure/Azure для серверов PostgreS-L Кто получить к ней доступ: наше приложение и управление авторизацией администраторов баз данных: 
 - Индивидуальный контроль авторизации: RBAC
 - Управление системой авторизации: частные конечные точки в лазурных виртуальных сетях

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36057" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

