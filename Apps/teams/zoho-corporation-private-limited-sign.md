---
title: Сведения о приложениях для знака Zoho от Zoho Corporation Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствия требованиям для знака Zoho, политики обработки данных, Microsoft Cloud App Security каталога приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: f164b4afadb0d85971cdaa40ab1bb43828ecb290
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/22/2021
ms.locfileid: "53528335"
---
# <a name="zoho-sign"></a>Zoho Sign

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/7a22873b-81e6-48ed-aee3-6f0e7dd5a104" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382011" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые корпорацией Zoho Private Limited корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Zoho Sign |
| Идентификатор | WA104382011 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Zoho Corporation Private Limited |
| URL-адрес веб-сайта-партнера | [https://zoho.com](https://zoho.com) |
| URL-адрес страницы Teams приложения | [https://www.zoho.com/sign/help/teams-extension.html](https://www.zoho.com/sign/help/teams-extension.html) |
| URL-адрес политики конфиденциальности | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL-адрес терминов использования | [https://www.zoho.com/terms.html](https://www.zoho.com/terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена корпорацией Zoho Private Limited о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Contacts.ReadWrite | делегирована |  | Полный доступ к контактам пользователей. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Contacts.ReadWrite.Shared | делегирована |  | Чтение и написание пользовательских и общих контактов. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite | делегирована |  | Полный доступ к файлам пользователей. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | делегирована |  | Полный доступ ко всем файлам, к которые пользователь может получить доступ. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.Selected | делегирована |  | Чтение и написание файлов, выбранных пользователем. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.ReadBasic.All | делегирована |  | Ознакомьтесь со всеми основными профилями пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| email | делегирована |  | Просмотр адреса электронной почты пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| offline_access | делегирована |  | Поддержив доступ к данным, к ним вы получили доступ. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| profile | делегирована |  | Просмотр основного профиля пользователя. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы не собираем EUII /PII в телеметрии и журналах. У нас есть скрипты для того, чтобы искать и предупреждать о том, как исправить все видимые данные.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Клиенты, как контроллер данных, имеют доступ к данным все время. Администраторы могут добавлять или удалять пользователей из знака Zoho. Они смогут просматривать все сведения, хранимые в приложении, включая полные маршруты аудита, отчеты об использовании. Они могут удалять данные и пользователей, передавать управление данными между пользователями.


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35679" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

