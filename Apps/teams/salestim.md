---
title: Информация о применении для SalesTim по SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Вся доступная информация о безопасности и соответствии требованиям для SalesTim, ее политики обработки данных, Microsoft Cloud App Security информации каталога приложений и информации о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c9094f50723c7094f895d21f8a9569dedbb5863b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553920"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчиком на: 27 октября 2020</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная SalesTim корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | SalesTim |
| ID | WA200001393 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | SalesTim |
| URL-адрес веб-сайта партнера | [https://www.salestim.com](https://www.salestim.com) |
| URL политики конфиденциальности | [https://www.salestim.com/legal/privacy](https://www.salestim.com/legal/privacy) |
| URL условий использования | [https://www.salestim.com/legal/tos](https://www.salestim.com/legal/tos) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена SalesTim о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Делегированные | Нет | Разрешить приложению устанавливать и обновлять собственные пакеты в каталоге корпоративных приложений. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Directory.AccessAsUser.All | Делегированные | Мы&#8217;хранить только некоторые документы пользователей, а не данные профиля. | Позволяет пользователю выбирать других пользователей в различных местах приложения, таких как выбор утверждений в рабочем процессе. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Group.ReadWrite.All | Делегированные | Мы&#8217;только для повторного хранения групп/команд, мы&#8217;не хранить содержимое групп/команд. | Позволяет приложению создавать группы, читать все свойства группы и членство от имени вко ей. Кроме того, владельцы групп смогут управлять своими группами, а участники групп — обновлять содержимое групп. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Mail.Send | Делегированные | Мы&#8217;повторно хранить метаданные этого действия, такие как дата уведомления, получатель (только ID), идентификатор запроса. | Позволяет приложению отправлять уведомления, например, во время рабочего процесса утверждения. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| Sites.ReadWrite.All | Делегированные | Мы используем некоторые службы Azure для хранения данных, особенно Redis в Azure и Cosmos DB | Позволяет приложению управлять дисками (файлами и папками), связанными с командой, во время процесса подготовки команды. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| User.Read.All | Делегированные | Мы&#8217;хранить только некоторые документы пользователей, а не данные профиля. | Позволяет приложению читать полный набор свойств профиля, отчетов и менеджеров любого пользователя. Он используется особенно во время процесса таргетинга аудитории, чтобы фильтровать некоторые содержимое на основе текущего профиля пользователя. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |
>| оффлайнакцесс | Делегированные | Нет | Позволяет приложению выполнять некоторые фоновые операции и действия в качестве пользователя. | 2a651f59-97ce-42bb-97d7-cf7a2af4b635 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>| **Все неосуществимые службы Майкрософт OII передаются** |  **Какой OII передается?** | **Обоснование передачи OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Мы используем Intercom в качестве основного приложения поддержки. Intercom может содержать некоторые основные сведения профиля пользователя, как описано здесь: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Мы используем эти GitHub для автоматического создания проблем из нашей производственной среды. Мы также храним некоторые технические журналы в GitHub (как описано здесь: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Эти проблемы и журналы могут содержать некоторые основные сведения профиля пользователя. Эти проблемы и журналы автоматически удаляются каждые 15 дней. |

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Все собранные данные описаны здесь: https://developers.salestim.com/platform/datamanagement.html#application-data Как описано, журналы временно хранятся в течение 15 дней, а затем удаляются автоматически.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Большинство данных хранится в Azure Cosmos DB.
Доступ к производственной среде ограничен двумя людьми, и эти учетные записи администратора соблюдаются МИД.
Эти счета посвящены и отличаются от наших корпоративных счетов.
Данные шифруются в остальных службах Azure, которые мы используем.
Развертывание производственных сред автоматизировано через специальную защищенную ветвь в нашей GitHub, где только два человека могут одобрить изменения.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

