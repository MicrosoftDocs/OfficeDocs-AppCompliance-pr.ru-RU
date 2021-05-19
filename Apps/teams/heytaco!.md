---
title: Информация о применении для HeyTaco! по HeyTaco!
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для HeyTaco!, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений, а также информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 66739977ba4aa3eef7456d4ec60530f94065a2b9
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553130"
---
# <a name="heytaco"></a>HeyTaco!

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 3 ноября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/be8d11cf-265a-4974-9912-4ff28c29fc21" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001346" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация предоставлена HeyTaco! корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | HeyTaco! |
| ID | WA200001346 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | HeyTaco! |
| URL-адрес веб-сайта партнера | [https://www.heytaco.chat](https://www.heytaco.chat) |
| URL политики конфиденциальности | [https://www.heytaco.chat/privacy](https://www.heytaco.chat/privacy) |
| URL условий использования | [https://www.heytaco.chat/terms](https://www.heytaco.chat/terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена HeyTaco! о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| email | Делегированные | используется для сопоставить пользователя для передачи данных из Slack в MS Teams | используется для сопоставить пользователя для передачи данных из Slack в MS Team | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| openid | Делегированные | используется для подписания человека в HeyTaco! | используется для подписания человека в HeyTaco! | be8d11cf-265a-4974-9912-4ff28c29fc21 |
>| profile | Делегированные | используется для захвата имени пользователя, изображения профиля, смещения тайм-зона, идентификатора арендатора и идентификатора команды | используется для захвата имени пользователя, аватара, смещения тайм-пояса, идентификатора арендатора и идентификатора команды | be8d11cf-265a-4974-9912-4ff28c29fc21 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Чтобы сказать пользователю, что они получили тако и кто это от. | Адрес электронной почты (для миграции тако с одной платформы на другую) Имя (для приветствия пользователя) Профиль изображения (для отображения на лидеров) Timezone (правильно показать тако, данные на странице активности) Арендатор ID (Для агрегирования данных арендатора) Team ID (Для агрегирования данных командой)  |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>EUII и OII не подключены ни к каким лесозаготовкам. Только типы ошибок и типы действий.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>HeyTaco! базы данных и резервные копии данных размещаются на Amazon Web Services (AWS). 

Операции центра обработки данных Amazon были аккредитованы в соответствии с ISO 27001 , SOC 1 и SOC 2/SSAE 16/ISAE 3402 (ранее SAS 70 Type II ), PCI Level 1 , FISMA Moderate и Sarbanes-Oxley (SOX).

Когда вы отправляете информацию через наш сервис, ваша информация защищена и зашифрована как в покое, так и в пути через защищенные соединения. Мы принимаем различные меры безопасности для обеспечения безопасности вашей личной информации.

У нас есть привилегированное управление доступом для защиты данных на наших серверах.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36139" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

