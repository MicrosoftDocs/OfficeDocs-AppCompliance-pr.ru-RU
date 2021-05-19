---
title: Информация о применении для DisasterTech DICE от DisasterTech
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для DisasterTech DICE, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29d53402a9bbf635e83d6d262227a8363577e261
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552240"
---
# <a name="disastertech-dice"></a>DisasterTech DICE

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 24 августа 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/7df3e67b-ed62-48e9-a950-c95bd7ebce80" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001909" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная DisasterTech корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | DisasterTech DICE |
| ID | WA200001909 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | DisasterTech |
| URL-адрес веб-сайта партнера | [https://dice.disastertech.com](https://dice.disastertech.com) |
| URL политики конфиденциальности | [https://dice.disastertech.com/privacy.html](https://dice.disastertech.com/privacy.html) |
| URL условий использования | [https://dice.disastertech.com/tos.html](https://dice.disastertech.com/tos.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена DisasterTech о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Делегированные | Адрес электронной почты пользователя, хранящийся для установления прав доступа, а также имя пользователя для идентификации пользователей по имени | Позволяет пользователю войти в систему и дает приложению доступ к их UPN, чтобы обеспечить бесшумный логин, а также Teams, а также установить имена пользователей и адреса электронной почты. | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| email | Делегированные | Нет | Требуется для Teams одной Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| offline_access | Делегированные | Нет | Требуется для Teams одной Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| openid | Делегированные | Нет | Требуется для Teams одной Sign-On | 36d23b76-c58b-4a34-a60f-dceac6962bad |
>| profile | Делегированные | Нет | Требуется для Teams одного знака.On. | 36d23b76-c58b-4a34-a60f-dceac6962bad |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Мы храним имя пользователя, имя и фамилию в базе данных PostgreS'L, размещенной Azure, чтобы позволить пользователям сотрудничать в приложении. Элементы управления в том, что только сотрудники аварийного технологического управления имеют прямой доступ к базе данных. Когда пользователь удаляется из приложения, мы архивировать информацию. Пользователи сохраняют за собой право удалить свои персональные данные из системы в любое время. Однако удаление такой информации также запретит их использование приложения.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Данные приложения хранятся в базе данных PostgreS'L в Azure, которая зашифрована в покое. Ни один пользователь не имеет прямого доступа к базе данных или API задней части. Все вызовы API защищены токеном Active Directory Access Token.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35993" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

