---
title: Сведения о приложении для текста по утвержденному контакту
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Text, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 2cc4abf4924ca9af1ddd5b49b6a38c4427f3404a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552390"
---
# <a name="text"></a>Текст

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/a622ceb4-b6e2-4557-8218-e22e80975ba4" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000383" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные утвержденным контактом в Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Текст |
| ID | WA200000383 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Approved Contact |
| URL-адрес веб-сайта-партнера | [https://sales.approvedcontact.com/syniverse-microsoft-teams...](https://sales.approvedcontact.com/syniverse-microsoft-teams-text/) |
| URL-адрес политики конфиденциальности | [https://sales.approvedcontact.com/wp-content/uploads/text-p...](https://sales.approvedcontact.com/wp-content/uploads/text-privacy-policy.pdf) |
| URL-адрес терминов использования | [https://sales.approvedcontact.com/wp-content/uploads/text-t...](https://sales.approvedcontact.com/wp-content/uploads/text-terms-of-use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена в Approved Contact о том, как это приложение собирает и хранит организационные данные, а также о том, как организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | делегирована | Для text BOT мы захватим идентификатор Team для создания будущих каналов для входящие текстовые сообщения. | Позволяет создавать каналы Teams для пользователей. | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| email | делегирована |  | Получение контактных данных пользователей. | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| offline_access | делегирована | Маркеры обновления хранятся в нашей базе данных. | Используется для сохраняющихся маркеров обновления в нашей базе данных для синхронизации календарей пользователей, когда они не присутствуют. | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| openid | делегирована |  | Позволяет пользователю войти в систему. | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| profile | делегирована |  |  | a622ceb4-b6e2-4557-8218-e22e80975ba4 |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (s)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Мы используем реестр для сравнения свободного и загруженного времени для всех в команде, чтобы планировать собрания в открытое время. | Мы просто храним адрес электронной почты, чтобы можно было сравнить время свободного и загруженного времени. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Да, мы регистрируем адреса электронной почты для подключения покупки лицензий к коммерческим appsource. Мы предоставляем возможность удаления этой информации из журналов.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Доступ к нашим журналам есть только у разработчиков. Мы применяем 2FA для доступа ко всем платформам разработки.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

