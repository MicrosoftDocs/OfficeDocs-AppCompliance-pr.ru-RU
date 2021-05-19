---
title: Информация о применении для мелочей от Springworks HR Tech
ms.author: elmalova
author: elenamalova
ms.date: 01/13/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Trivia, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: fbd1b9f5f308f3690a9d55a40993ba6122e8f81b
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553850"
---
# <a name="trivia"></a>Trivia

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 13 января 2021 г.</p>

* <a href="https://teams.microsoft.com/l/app/391082c3-968b-47b1-9c92-b5daf008000b" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001956" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Springworks HR Tech корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Trivia |
| ID | WA200001956 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Springworks HR Tech |
| URL-адрес веб-сайта партнера | [https://springworks.in/](https://springworks.in/) |
| URL-адрес Teams страницы информации о приложениях | [https://www.springworks.in/trivia](https://www.springworks.in/trivia) |
| URL политики конфиденциальности | [https://trivia.springworks.in/policy](https://trivia.springworks.in/policy) |
| URL условий использования | [https://trivia.springworks.in/tnc](https://trivia.springworks.in/tnc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Springworks HR Tech о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.Read.All | Делегированные | Нет | Чтобы получить список Teams, что пользователь является частью | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| Team.ReadBasic.All | Делегированные | Да, хранение списка команд, в которые был добавлен бот | Сбор основной информации обо всех командах, присутствующих в рабочем пространстве | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| User.Read.All | Делегированные | Да, для хранения уникального aadObjectId пользователя. Кроме того, различные детали пользователя, как имя пользователя, электронная почта и т.д. и отобразить его на панели мониторинга Trivia | Чтобы получить подробную информацию о всех пользователей, присутствующих в рабочем пространстве | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| openid | Делегированные | Да, для хранения пользователей, во всех в которых есть приложение. |  Разрешить пользователю использовать Приложение со своей учетной записью и приложением для использования данных пользователя | 43bc466a-7678-476f-b904-2d933c5bbfc3 |
>| profile | Делегированные | Да, для хранения пользовательских идентификации и имен хостов викторин и других функций, и однозначно определить их | Чтобы прочитать основную информацию о профиле пользователя, такую как имя пользователя, напишите по электронной почте | 43bc466a-7678-476f-b904-2d933c5bbfc3 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>| **Все неосуществимые службы Майкрософт OII передаются** |  **Какой OII передается?** | **Обоснование передачи OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| AWS, Майнчимп, Полоса.  | Имя клиента, электронная почта, IP, платежная информация | Мы используем эти третьи стороны, чтобы обеспечить лучший опыт клиентов для наших клиентов |

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Эти данные используются для отображения и хранения списка участников викторины и других подобных функций | Имя, Электронная почта | Да, хранение данных хозяина и участников викторин и других функций для аналитики и общения с хозяином в случае ошибок |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>OII: название организации, идентификатор арендатора отображаются в журналах; EUII: идентификатор объекта aad, полное имя, электронная почта отображаются в журналах. у нас есть 30 дней удержания период пост, который журналы автоматически удаляется. 


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Данные, хранящиеся в RDS, AWS. он зашифрован. Доступ только к DevOps инженеру, инженеру-лидеру и основателю

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36138" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Идентификационная информация

Эта информация была предоставлена Springworks HR Tech о том, как это приложение обрабатывает аутентификацию, авторизацию, лучшие практики регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интегрируесь ли вы с платформой Microsoft Identify Platform (Azure AD)?  | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
