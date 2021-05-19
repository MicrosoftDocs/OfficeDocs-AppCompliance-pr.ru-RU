---
title: Информация о заявке на напоминание от 88 Ventures Limited
ms.author: elmalova
author: elenamalova
ms.date: 09/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Remind, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 8e2124ed68b2e9d750c8bc6a229eca0ccad200b5
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552450"
---
# <a name="remind"></a>Remind

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 28 сентября 2020 г.</p>

* <a href="https://teams.microsoft.com/l/app/88546d4f-9973-4716-98e4-cd181c04bc2d" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001444" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация предоставлена 88 Ventures Limited корпорацией Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Remind |
| ID | WA200001444 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | 88 Ventures Limited |
| URL-адрес веб-сайта партнера | [https://www.teamsreminder.app](https://www.teamsreminder.app) |
| URL политики конфиденциальности | [https://www.teamsreminder.app/#privacy](https://www.teamsreminder.app/#privacy) |
| URL условий использования | [https://www.teamsreminder.app/#terms](https://www.teamsreminder.app/#terms) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена 88 Ventures Limited о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Directory.Read.All | Делегированные | нет информации, хранящейся в базе данных | позволяет администратору просматривать каталог пользователей организации для пользователей, которые установили публичные напоминания | 88546d4f-9973-4716-98e4-cd181c04bc2d |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>| **Обоснование доступа к EUII?**  | **Хранится ли EUII в базе данных (ы)?** | **Обоснование хранения EUII?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| (1) Когда пользователь устанавливает напоминание о сообщении, бот пытается получить имя человека, который первоначально послал сообщение для отображения этой информации в списке напоминаний пользователя (2) Когда пользователь устанавливает напоминание для другого канала или члена чата, бот пытается получить личность (пользователя или бота) и имя упомянутого пользователя, чтобы отобразить его в списке напоминаний пользователя | (1) Когда пользователь устанавливает напоминание о сообщении, бот пытается получить имя человека, который первоначально послал сообщение для отображения этой информации в списке напоминаний пользователя (2) Когда пользователь устанавливает напоминание для другого канала или члена чата, бот пытается получить личность (пользователя или бота) и имя упомянутого пользователя, чтобы отобразить его в списке напоминаний пользователя |  |


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Ни один EEUI и OII не совместно с телеметрией или функциональностью регистрации

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Шифрование в покое, двухфакторная аутентификация (2FA) для ограничения доступа к нашей ИТ-инфраструктуре и данным клиентов, защищенный IP диапазон между системами

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36058" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

