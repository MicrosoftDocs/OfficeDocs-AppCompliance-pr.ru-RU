---
title: Информация о применении для Зохо Знак Зохо Корпорации Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для знака Зохо, его политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 356c8755ee40269ef4efe844d22ebbc20e53937d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552720"
---
# <a name="zoho-sign"></a>Zoho Sign

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/7a22873b-81e6-48ed-aee3-6f0e7dd5a104" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382011" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная корпорацией Зохо Private Limited корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Zoho Sign |
| ID | WA104382011 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Zoho Corporation Private Limited |
| URL-адрес веб-сайта партнера | [https://zoho.com](https://zoho.com) |
| URL-адрес Teams страницы информации о приложениях | [https://www.zoho.com/sign/help/teams-extension.html](https://www.zoho.com/sign/help/teams-extension.html) |
| URL политики конфиденциальности | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL условий использования | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена корпорацией Зохо Private Limited о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые приложение собирает.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Contacts.ReadWrite | Делегированные |  | Иметь полный доступ к контактам пользователей. |  |
>| Contacts.ReadWrite.Shared | Делегированные |  | Читать и писать пользователям и общим контактам. |  |
>| Files.ReadWrite | Делегированные |  | Иметь полный доступ к файлам пользователей. |  |
>| Files.ReadWrite.All | Делегированные |  | Иметь полный доступ ко всем файлам, к которые пользователь может получить доступ. |  |
>| Files.ReadWrite.Selected | Делегированные |  | Читайте и записывая файлы, выбранные пользователем. |  |
>| User.ReadBasic.All | Делегированные |  | Прочитайте все основные профили пользователя. |  |
>| email | Делегированные |  | Просмотр адреса электронной почты пользователя. |  |
>| offline_access | Делегированные |  | Поддерживайте доступ к данным, к которые вы получили доступ. |  |
>| profile | Делегированные |  | Просмотр основного профиля пользователя. |  |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Мы не собираем EUII / PII в телеметрии и журналах. У нас есть скрипты для и оповещения для фиксации любых таких данных, видимых.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Клиенты как контроллер данных имеют доступ к данным все время. Администраторы могут добавлять или удалять пользователей из знака Зохо. Они смогут просматривать всю информацию, хранящуюся в приложении, включая полные аудиторские трассы, отчеты об использовании. Они могут удалять данные и пользователей, передавать контроль над данными между пользователями.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

