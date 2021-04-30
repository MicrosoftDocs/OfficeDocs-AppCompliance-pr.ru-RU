---
title: Сведения о приложениях для COCO от Hexaware Technologies Ltd.
ms.author: elmalova
author: elenamalova
ms.date: 06/23/2020
ms.topic: article
ms.service: attestation
description: Все доступные сведения о безопасности и соответствия требованиям для COCO, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: bd1965766fabddf8350010b3aefca2ebf9ceedbf
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095111"
---
# <a name="coco"></a>COCO

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 23 июня 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/c3f021f9-1fe2-44c7-972e-58f3cd0e7762" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001468" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные корпорацией Майкрософт от Компании Hexaware Technologies Ltd.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | COCO |
| Идентификатор | WA200001468 |
| Возможности | Бот, вкладка |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Hexaware Technologies Ltd. |
| URL-адрес веб-сайта-партнера | [https://hexaware.com/](https://hexaware.com/) |
| URL-адрес политики конфиденциальности | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf) |
| URL-адрес терминов использования | [https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-...](https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf#page=6) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены hexaware Technologies Ltd. о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.AccessAsUser.All | делегирована | Нет | Каталог доступа в качестве подписанного пользователя | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| Directory.Read.All | приложение | Нет | Чтение данных каталога | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| Directory.ReadWrite.All | делегирована | Нет | Чтение и запись данных каталога | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| User.Read | делегирована | Нет | Вход и чтение профиля пользователя | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| User.Read.All | приложение | Нет | Чтение полных профилей всех пользователей | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| User.ReadWrite.All | делегирована | Нет | Чтение и запись полных профилей всех пользователей | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |
>| openid | делегирована | Нет | Вход пользователей | 82eb2bf2-969c-46da-9e89-1db59ac4fbb3 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Ведение данных сеанса | Имя, id электронной почты |  |



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Н/Д

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>https://hexaware.com/wp-content/uploads/2020/03/Teams_COCO-Privacy-Policy-and-Additional-Terms_V2.1.pdf

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35906" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

