---
title: Информация о применении для Asana для Outlook по Asana
ms.author: elmalova
author: elenamalova
ms.date: 11/02/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Asana за Outlook год, ее политики обработки данных, ее Microsoft Cloud App Security информация о каталоге приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: cd3d403d7b25c1ad5dda60dff8d93c18dfe59c30
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553750"
---
# <a name="asana-for-outlook"></a>Асана для Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 2 ноября 2020 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381833" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная Asana корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Асана для Outlook |
| ID | WA104381833 |
| Office 365 клиенты поддержали | Outlook 2016 или позже Windows, Outlook 2016 или позже на Mac, Outlook в Интернете |
| Название компании-партнера | Asana |
| URL-адрес веб-сайта партнера | [https://asana.com/](https://asana.com/) |
| URL политики конфиденциальности | [https://asana.com/terms#privacy-policy](https://asana.com/terms#privacy-policy) |
| URL условий использования | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;омктюен-США](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена Asana о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>Это приложение не использует Microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>| **Все неосуществимые службы Майкрософт OII передаются** |  **Какой OII передается?** | **Обоснование передачи OII?** |
>|:-------------------|:--------------------------|:--------------------------|
>| Надстройка передает основную информацию по электронной почте (отправитель, recepient, субъект, тело) и вложения в Asana по запросу пользователя. |  | Электронная почта - Читает в настоящее время открытую электронную почту при отображении в панели задач. - Читает в настоящее время открытые вложения электронной почты для загрузки на задачи Asana. - Это дает пользователям возможность быстро выполнять задачи в Asana с информацией из электронной почты. |



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Наше приложение регистрирует только информацию, относящуюся к данным Asana. Единственный раз, когда мы в журнале ничего, связанного с Outlook пользовательской информации, когда пользователь явно придает электронную почту или загружает вложение в Asana, и даже тогда мы не войти содержимое. Краткосрочные журналы существуют на серверах, которые могут включать некоторые пользовательские данные, но они эфемерны и ограничены периодами менее 72 часов.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Enterprise клиенты имеют гарантированное шифрование в покое с помощью AES-256. Данные хранятся на Amazon Web Services, а AWS управляет ключами шифрования с помощью системы управления ключами. У нас есть 2FA для всех администраторов. Доступ предоставляется по принципу наименьшей привилегии.
Ваши администраторы Asana Organizational имеют возможность настроить SAML, SCIM, учетные записи службы и иметь общее представление данных, которые вносят в инструмент. Администраторы могут запросить полный организационный экспорт из консоли администратора и аудита по мере необходимости.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/10417" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

