---
title: Сведения о приложениях Studi.ly в inLogic-Office Store
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Studi.ly, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d682e758d9632a2c3ac19296dda7083dc8379689
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59289065"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 24 августа 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые в магазине inLogic-Office Microsoft:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Studi.ly |
| Идентификатор | WA200001668 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | inLogic-Office Store |
| URL-адрес веб-сайта-партнера | [https://www.inlogic.dk](https://www.inlogic.dk) |
| URL-адрес политики конфиденциальности | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| URL-адрес терминов использования | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены в магазине inLogic-Office о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.Read.All | делегирована | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Напишите каталог в группах для назначений и материалов. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.ReadWrite.All | приложение | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Напишите каталог в группах для назначений и материалов. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.Read.All | приложение | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Ознакомьтесь с классами образования, школой, членами и терминами.Получите все классы и школы клиента для синхронизации в базу данных приложений. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadBasic | делегирована | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Ознакомьтесь с классами образования, школой, членами и терминами.Получите все классы и школы клиента для синхронизации в базу данных приложений. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadWrite.All | приложение | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Ознакомьтесь с классами образования, школой, членами и терминами.Получите все классы и школы клиента для синхронизации в базу данных приложений. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Files.ReadWrite.All | делегирована | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Файлы ReadWrite с одного диска | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.Read.All | делегирована | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Это разрешение позволяло приложению получать различные события claender для групп клиента.,subject, start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.ReadWrite.All | оба | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Это разрешение позволяло приложению получать различные события claender для групп клиента.,subject, start,end,extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Member.Read.Hidden | приложение |  |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Sites.ReadWrite.All | оба | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Файлы ReadWrite с одного диска | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.Read | делегирована | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Чтение сведений о пользователях | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.ReadBasic.All | делегирована | Мы храним в api классы, школы, члены и термины из api образования, и нам это нужно, потому что если мы получаем ее каждый раз из API графа, что заставляет наше приложение работать медленно. Мы синхронизируются с событием, основанным на времени, от API образования до базы данных. | Чтение сведений о пользователях | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Такие данные не отображаются в журналах

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Он хранится в базе данных Azure cosmos, и любое шифрование и хранилище, доступное по умолчанию с базой данных космоса, применимо к этому приложению.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

