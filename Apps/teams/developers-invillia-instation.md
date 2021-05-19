---
title: Информация о приложениях для InStation от разработчиков Invillia
ms.author: elmalova
author: elenamalova
ms.date: 08/06/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для InStation, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 40c86e4284ed201fedf63bfe3bbd7570b61049b7
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552250"
---
# <a name="instation"></a>InStation

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 6 августа 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/0c841985-9919-4c0a-b87d-b06b301148b3" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001701" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная разработчиками Invillia корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | InStation |
| ID | WA200001701 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Developers Invillia |
| URL-адрес веб-сайта партнера | [https://instation.invillia.com/](https://instation.invillia.com/) |
| URL политики конфиденциальности | [https://instation.invillia.com/terms#privacy-policy](https://instation.invillia.com/terms#privacy-policy) |
| URL условий использования | [https://instation.invillia.com/terms#terms-of-use](https://instation.invillia.com/terms#terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена разработчиками Invillia о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| OnlineMeetings.Read.All | Делегированные | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| OnlineMeetings.ReadWrite.All | Делегированные | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | магазины: id, join_url, join_web_url и chat_id. Позволяет приложению создавать собрания | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read | Делегированные | Позволяет приложению войти в организацию на первом шаге | деятельности и ответственности. Позволяет приложению захватить статус пользователя; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| Presence.Read.All | Делегированные | Позволяет приложению войти в организацию на первом шаге, | деятельности и ответственности. Позволяет приложению захватить статус пользователя; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read | Делегированные | магазины: id, почта, имя дисплея, фамилия и изображение. Позволяет приложению искать данные пользователей; | магазины: id, почта, имя дисплея, фамилия и изображение. Позволяет приложению искать данные пользователей; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| User.Read.All | Делегированные | магазины: id, почта, имя дисплея, фамилия и изображение. Позволяет приложению искать данные пользователей; | магазины: id, почта, имя дисплея, фамилия и изображение. Позволяет приложению искать данные пользователей; | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| email | Делегированные | Позволяет приложению захватить основную&#180;администратора на первом входе | Позволяет приложению захватить основную&#180;администратора на первом входе | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| offline_access | Делегированные | магазины: токен и токен обновления. Позволяет приложению выполнить обновление на токене MS | магазины: токен и токен обновления. Позволяет приложению выполнить обновление на токене MS | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| openid | Делегированные | Позволяет приложению войти в организацию на первом шаге | Позволяет приложению войти в организацию на первом шаге | 0c841985-9919-4c0a-b87d-b06b301148b3 |
>| profile | Делегированные | Позволяет приложению захватить основную&#180;администратора на первом входе; | Позволяет приложению захватить основную&#180;администратора на первом входе; | 0c841985-9919-4c0a-b87d-b06b301148b3 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Мы экономим только журналы использования пользователей в нашем приложении.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Мы экономим только журналы использования пользователей в нашем приложении. Ничего конфиденциального, не требуя шифрования, и только наши конкретные администраторы имеют доступ к этим данным.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35954" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

