---
title: Сведения о приложениях для CalendarHero от CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для CalendarHero, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 41a7dd8a2cb7d900ac26b228c4cc2522d76da59c
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287081"
---
# <a name="calendarhero"></a>CalendarHero

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 17 марта 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные корпорацией CalendarHero Inc корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | CalendarHero |
| Идентификатор | WA200000150 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | CalendarHero Inc |
| URL-адрес веб-сайта-партнера | [https://zoom.ai](https://zoom.ai) |
| URL-адрес страницы Teams приложения | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL-адрес политики конфиденциальности | [https://zoom.ai/privacy-policy](https://zoom.ai/privacy-policy) |
| URL-адрес терминов использования | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эти сведения предоставлены CalendarHero Inc о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | оба | Собрания кэшются в нашем mongoDB в Azure, но описания шифруются. | Доступ к событиям календаря пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Contacts.ReadWrite | оба | Имя и адрес электронной почты контактов. | Ознакомьтесь с контактами пользователя (чтобы мы могли пригласить их на собрание). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | оба | Имя и члены группы. | (Необязательный) чтение корпоративных групп пользователей (для планирования с группами). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | оба | Свяжитесь с электронной почтой/именем, частотой и регулярностью взаимодействий. | (Необязательный) используется для чтения метаданных электронной почты в соответствии с тем, кто наиболее важные контакты пользователя (через Машинное обучение). | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| MailboxSettings.ReadWrite | оба | Часовой пояс пользователя. | Часовой пояс пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read.All | оба | Электронная почта &amp; имени пользователя (хранится в качестве контакта). | (Необязательный) чтение корпоративных пользователей (для планирования с коллегами) | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | приложение | Нет | Мы должны читать и записывать через наш задний конец в любое время, без участия пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| импорт имен и сообщений электронной почты сотрудников, чтобы наш помощник по собранию бота может планировать встречи с ними | имя &amp; электронной почты. оба хранятся в нашей базе данных для быстрого поиска и частичного поиска имен (например. встреча с Джо P) |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Адрес электронной почты пользователя и/или контакта используется для входа событий в LogDNA, нашего поставщика журналов.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все данные хранятся в облачном центре обработки данных MS Azure, расположенном в Квебеке, Канада. Несколько полей шифруются с помощью AES256. Доступ к базе данных доступен только инженерам и нашим серверам с помощью учетных данных пользователя и службы.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

