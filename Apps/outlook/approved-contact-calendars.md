---
title: Информация о заявках для утвержденных календарей контактов от утвержденного контакта
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии утвержденным календарям контактов, политикам обработки данных, информации каталога приложений Microsoft Cloud App Security и информации о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57dd499fe648ed9a9b481d4175056977a0d6fa61
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552560"
---
# <a name="approved-contact-calendars"></a>Утвержденные календари контактов

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Утвержденным контактом с корпорацией Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Утвержденные календари контактов |
| ID | WA104380294 |
| Office 365 клиенты поддержали | Outlook 2013 или позже Windows, Outlook 2016 или позже на Mac, Outlook в Интернете |
| Название компании-партнера | Approved Contact |
| URL-адрес веб-сайта партнера | [https://approvedcontact.com/](https://approvedcontact.com/) |
| URL политики конфиденциальности | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| URL условий использования | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;омктюен-США](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Утвержденным Контактом о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Делегированные | Для календаря BOT мы храним пользователей бесплатно / занят время для поиска свободного времени для нескольких человек.  | Мы читаем и сравниваем свободное/занятое время и расписание встреч. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | Делегированные | Да, мы храним контактную информацию. | Импорт и синхронизация контактов. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | Делегированные | Да | Базовая информация профиля. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | Делегированные | Нет | Используется для просмотра профилей сотрудников, сравнения свободного времени и планирования конференц-залов. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | Делегированные | Да, бесплатное/занятое время для пользователей в автономном режиме. | Звоните Graph, когда пользователь не активно использует наш сайт. | adef9811-448f-4dd5-88d9-68734050fe58 |
>| openid | Делегированные | Нет | Office 365 ССО. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Да, мы включаем адреса электронной почты для подключения лицензионных покупок к коммерческому Appsource. Мы предоставляем возможность удалять эту информацию из наших журналов.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Только разработчики имеют доступ к нашим журналам. Мы применяем 2FA для доступа ко всем платформам разработки.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

