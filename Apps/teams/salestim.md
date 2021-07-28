---
title: Сведения о приложениях для salesTim от SalesTim
ms.author: elmalova
author: elenamalova
ms.date: 10/27/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Все доступные сведения о безопасности и соответствия требованиям для SalesTim, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения, а также сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: b15cf2f87b6707b6fa82dfc3968444d7cad85e8a
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53524763"
---
# <a name="salestim"></a>SalesTim

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 27 октября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/589748de-ec98-4616-9063-e91c629bd1a4" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001393" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые службой SalesTim Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | SalesTim |
| Идентификатор | WA200001393 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | SalesTim |
| URL-адрес веб-сайта-партнера | [https://www.salestim.com/](https://www.salestim.com/) |
| URL-адрес политики конфиденциальности | [https://www.salestim.com/legal/privacy/](https://www.salestim.com/legal/privacy/) |
| URL-адрес терминов использования | [https://www.salestim.com/legal/tos/](https://www.salestim.com/legal/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения были предоставлены salesTim о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет иметь данные, собираемые приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.ReadWrite.All | делегирована | Нет | Разрешить приложению устанавливать и обновлять собственные пакеты в корпоративном каталоге приложений. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Directory.AccessAsUser.All | делегирована | Мы&#8217;только некоторые ID пользователей, а не данные профилей. | Позволяет пользователю выбирать других пользователей в различных местах в приложении, таких как выбор одобрений в рабочего процесса. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Group.ReadWrite.All | делегирована | Мы&#8217;только для хранения ID групп и команд,&#8217;не храним содержимое групп и команд. | Позволяет приложению создавать группы, читать все свойства группы и членство от имени подписанного пользователя. Кроме того, владельцы групп смогут управлять своими группами, а участники групп — обновлять содержимое групп. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Mail.Send | делегирована | Мы&#8217;хранение метаданных этого действия, таких как дата уведомления, только получатель (только для ID), запрос ID. | Позволяет приложению отправлять уведомления, например, во время рабочего процесса утверждения. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| Sites.ReadWrite.All | делегирована | Мы используем некоторые службы Azure для хранения данных, особенно Redis в Azure и Cosmos DB | Позволяет приложению управлять дисками (файлами и папками), связанными с командой, во время процесса создания команды. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| User.Read.All | делегирована | Мы&#8217;только некоторые ID пользователей, а не данные профилей. | Позволяет приложению читать полный набор свойств профилей, отчетов и менеджеров любого пользователя. Он используется особенно во время процесса таргетации аудитории, чтобы отфильтровать содержимое на основе текущего профиля пользователя. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |
>| offlineaccess | делегирована | Нет | Позволяет приложению выполнять некоторые фоновые операции и действия в качестве пользователя. | [2a651f59-97ce-42bb-97d7-cf7a2af4b635](https://docs.microsoft.com/microsoft-365-app-certification/azure/2a651f59-97ce-42bb-97d7-cf7a2af4b635) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>| **Все не службы Майкрософт OII передаются** |  **Какие OII передаются?** | **Обоснование переноса OII?** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Мы используем Intercom в качестве основного приложения поддержки. Интерком может содержать некоторые основные сведения о профиле пользователя, как описано здесь: https://developers.salestim.com/platform/datamanagement.html#support-data |  | Мы используем GitHub API для автоматического создания проблем из нашей производственной среды. Мы также храним некоторые технические журналы в GitHub (как описано здесь: https://developers.salestim.com/platform/datamanagement.html#error-reporting-data) . Эти проблемы и журналы могут содержать некоторые основные сведения о профиле пользователя. Эти проблемы и журналы удаляются автоматически каждые 15 дней. |

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Все собранные данные описаны здесь: как описано, журналы временно хранятся в течение 15 дней, а затем https://developers.salestim.com/platform/datamanagement.html#application-data удаляются автоматически.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Большинство данных хранятся в Azure Cosmos DB.
Доступ к производственной среде ограничен двумя людьми, и эти учетные записи администратора применяются к MFA.
Эти учетные записи выделены и отличаются от наших корпоративных учетных записей.
Данные шифруются в покое во всех службах Azure, которые мы используем.
Развертывание в производственных средах автоматизировано с помощью выделенного защищенного филиала в GitHub среде, где только два человека могут утверждать изменения.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35853" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

