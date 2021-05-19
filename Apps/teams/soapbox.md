---
title: Информация о применении для Soapbox от Soapbox
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Soapbox, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений, а также информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 6e2b43df38aac6307c36c4a2cc8d00fe1c3fb629
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552780"
---
# <a name="soapbox"></a>Soapbox

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/b49e7913-3b3f-4125-adde-2b698fc12c8b" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381501" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Soapbox корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Soapbox |
| ID | WA104381501 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Soapbox |
| URL-адрес веб-сайта партнера | [https://soapboxhq.com](https://soapboxhq.com) |
| URL-адрес Teams страницы информации о приложениях | [https://msteams.services.soapboxhq.com/faqs](https://msteams.services.soapboxhq.com/faqs) |
| URL политики конфиденциальности | [https://soapboxhq.com/privacy-policy/microsoft-teams](https://soapboxhq.com/privacy-policy/microsoft-teams) |
| URL условий использования | [https://soapboxhq.com/terms-of-service](https://soapboxhq.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Soapbox о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Делегированные | Токен синхронизации. | Доступ к календарю необходим для синхронизации встреч SoapBox с событиями календаря |  |
>| User.Read | Делегированные | Имя, электронная почта, идентификатор пользователя Майкрософт. | Имя и электронная почта используются для создания пользователей SoapBox. |  |
>| offline_access | Делегированные |  | Оффлайн-доступ к календарям необходим для того, чтобы время уведомлений SoapBox было актуальным для синхронизированных событий календаря. |  |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Приложение получает доступ к команде реестра и чат реестра мы используем это для создания командных каналов в SoapBox с членами команды / чат | Имя, электронная почта, идентификатор пользователя Майкрософт для улучшения внешний вид приложения для пользователей команд Майкрософт и обеспечения того, чтобы каждый пользователь может в полной мере участвовать в заседании программного обеспечения. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Да. Идентификатор имени, электронной почты и идентификатор пользователя Майкрософт отображаются в нашей единой платформе регистрации в течение максимум 30 дней, чтобы помочь в выявлении проблем и помочь пользователям использовать платформу. Через 30 дней данные удаляются с серверов регистрации.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Наша основная инфраструктура хранится на AWS в частной сети. У нас также есть боты, настроенные на Heroku и Azure. Доступ к серверам ограничен с помощью ключевых требований SSH. Все запросы прогначала SSL (TLS 1.3). Мы используем подписанные запросы, чтобы обеспечить безопасность трафика от наших ботов до платформы. Данные шифруются в покое. Dev ops сотрудники требуют 2FA для доступа к своим счетам

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35464" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

