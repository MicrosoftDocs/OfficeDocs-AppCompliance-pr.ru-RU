---
title: Информация о приложениях для Smartsheet по Smartsheet
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Smartsheet, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ddf77e7e73cc0bef1a21e72d1db328a4845a12f5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551529"
---
# <a name="smartsheet"></a>Smartsheet

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/f4d81e8e-4500-44c2-8328-9e06cbe037c5" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104380975" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Smartsheet корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Smartsheet |
| ID | WA104380975 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Smartsheet |
| URL-адрес веб-сайта партнера | [https://help.smartsheet.com/articles/2476201](https://help.smartsheet.com/articles/2476201) |
| URL-адрес Teams страницы информации о приложениях | [https://help.smartsheet.com/articles/2476201-interact-with-...](https://help.smartsheet.com/articles/2476201-interact-with-smartsheet-items-in-microsoft-teams) |
| URL политики конфиденциальности | [https://www.smartsheet.com/privacy](https://www.smartsheet.com/privacy) |
| URL условий использования | [https://www.smartsheet.com/user-agreement](https://www.smartsheet.com/user-agreement) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Smartsheet о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| AppCatalog.ReadWrite.All | Делегированные | Нет. | Позволяет нашему приложению устанавливать приложения от имени пользователя. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Directory.Read.All | Делегированные | tenantId для получения информации, чтобы показать в пользовательском интерфейсе. | Позволяет нам читать, какие приложения этот арендатор использует, чтобы мы могли проверить, если нам нужно установить приложение для них. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.Read.All | Делегированные | teamId/groupId для доставки сообщений. | Позволяет нашему приложению читать основную информацию о группе (или Teams команды), а также разговоры. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| Group.ReadWrite.All | Делегированные | teamId/groupId для доставки сообщений. | Позволяет нашему приложению начать новые разговоры в командах. Это разрешение также включает в себя выше Read.All области, но нам нужен этот, а также по техническим причинам. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| User.Read.All | Делегированные | userId. | Позволяет нам читать основную информацию о пользователе во время процесса аута. | c68947ae-a07f-44ce-9a13-7b559251731d |
>| offline_access | Делегированные | обновитьТокен. | Позволяет нашему приложению получать токены обновления и обновлять маркер auth от имени пользователя, когда они используют приложение. | c68947ae-a07f-44ce-9a13-7b559251731d |

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на веб-Microsoft 365 могут использовать дополнительные API Майкрософт, кроме Microsoft Graph для сбора или обработки идентифицируемой организационной информации (OII). Перечислите все API Майкрософт, кроме Microsoft, Graph использует это приложение.

>| **API** |  **Собирается ли OII?** |  **Что такое OII?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| Api-файлы Bot Framework | Да | Мы используем API Bot Framework для доставки сообщений в качестве приложения для команд. Smartsheet хранит информацию userId, чтобы отслеживать, с кем разговаривает бот Smartsheet. |  | Нет |  |

#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>| **Все неосуществимые службы Майкрософт OII передаются** |  **Какой OII передается?** | **Обоснование передачи OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Smartsheet хранит информацию в зашифрованном состоянии в состоянии покоя в среде нашего производственного центра обработки данных, размещенной с Equinix и в AWS S3, где мы храним вложения клиентов в частных зашифрованных ведрах. |  | Мы используем API-фреймворка бота для доставки сообщений в качестве приложения для приложения команд. Smartsheet хранит информацию userId, чтобы отслеживать, с кем разговаривает бот Smartsheet. |

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| Smartsheet использует его, чтобы помочь отслеживать, кто бот говорит тоже. Во время первоначального потока аут мы создаем запись бота для пользователя в системе уведомлений Smartsheet. | Для Smartsheet для Teams бота, мы храним электронную почту пользователя и userId Teams, чтобы помочь отслеживать, с кем говорит бот.  Smartsheet хранит tenantIds, чтобы помочь перечислить группы, в которые пользователь входит в каталог, и groupIds для доставки сообщений. |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Нет

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Smartsheet шифрует всю сохраненную информацию о пользователе, и наши администраторы обязаны использовать 2FA. Smartsheet работает как не-вид SaaS провайдера и по умолчанию, мы не рассматриваем содержание, которое клиенты выбирают для загрузки или ввести в платформу.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11934" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

