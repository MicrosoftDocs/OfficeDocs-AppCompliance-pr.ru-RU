---
title: Информация о заявке для CalendarHero от CalendarHero Inc
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для CalendarHero, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d27858000c591c320cfadc301ea16ddf2fac89bd
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553335"
---
# <a name="calendarhero"></a>КалендарьГеро

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком на: 17 марта 2020</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная CalendarHero Inc корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | КалендарьГеро |
| ID | WA200000150 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | КалендарьГеро Инк |
| URL-адрес веб-сайта партнера | [https://calendarhero.com](https://calendarhero.com) |
| URL-адрес Teams страницы информации о приложениях | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| URL политики конфиденциальности | [https://calendarhero.com/privacy](https://calendarhero.com/privacy) |
| URL условий использования | [https://calendarhero.com/terms-of-use](https://calendarhero.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена CalendarHero Inc о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | оба | Встречи кэшируются в нашем mongoDB на Azure, но описания зашифрованы. | Доступ к событиям календаря пользователя. |  |
>| Contacts.ReadWrite | оба | Контакты имя и адрес электронной почты. | Прочитайте контакты пользователя (чтобы мы могли пригласить их на собрание). |  |
>| Group.Read.All | оба | Название группы и члены. | (Необязательно) читать корпоративные группы пользователей (для планирования с группами). |  |
>| Mail.Read | оба | Контактная электронная почта/имя, частота/правоты взаимодействий. | (Опционально) используется для чтения метаданных электронной почты под кто наиболее важных контактов пользователя (через Машинное обучение). |  |
>| MailboxSettings.ReadWrite | оба | Часовой пояс пользователя. | Часовой пояс пользователя. |  |
>| User.Read.All | оба | Электронная почта имени &amp; пользователя (хранится в качестве контакта). | (Необязательно) читать корпоративных пользователей (для планирования с коллегами) |  |
>| offline_access | приложение | Нет | Мы должны читать и писать через наш бэк-энд в любое время, без пользователя присутствует. |  |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| импортировать имена/электронные письма сотрудников, чтобы наш помощник по встрече бота можно было запланировать встречи с ними | имя &amp; электронной почты. оба хранятся в нашей базе данных для быстрого поиска и для частичного поиска имени (например. встретиться с Джо P) |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Адрес электронной почты пользователя и/или контакта используется для регистрации событий в LogDNA, нашем поставщике журналов.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Все данные хранятся в облачном центре обработки данных MS Azure, расположенном в Квебеке, Канада. Несколько полей зашифрованы с помощью AES256. Доступ к базе данных доступен только инженерам и нашим серверам с серверами на уровне пользователя/сервиса.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

