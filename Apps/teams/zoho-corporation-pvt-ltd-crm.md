---
title: Сведения о приложениях для Zoho CRM от Zoho Corporation Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Zoho CRM, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложения и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5408c7dd2ce3a7cd27c98905156bdbb45c6edede
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59284878"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Просмотр в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставленные корпорацией Zoho Pvt Ltd корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Zoho CRM |
| Идентификатор | WA104382094 |
| Office 365 поддерживаемые клиенты | Microsoft Teams |
| Имя компании-партнера | Zoho Corporation Pvt Ltd |
| URL-адрес веб-сайта-партнера | [https://www.zoho.com/](https://www.zoho.com/) |
| URL-адрес страницы Teams приложения | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL-адрес политики конфиденциальности | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL-адрес терминов использования | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена zoho Corporation Pvt Ltd о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | ID папки календаря хранится для синхронизации контактов от Zoho CRM до Microsoft &amp; наоборот. Сведения о календаре event_name, event_location, participant_details хранятся. | Позволяет пользователю синхронизировать события Office365 с CRM Zoho. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Contacts.ReadWrite | делегирована | ID папки контактов хранится для синхронизации контактов из Zoho CRM в Microsoft &amp; наоборот. Сохраняются контактные first_name, last_name, адрес электронной почты. | Позволяет пользователю синхронизировать контакты Office365 с CRM Zoho. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read | делегирована |  | Позволяет пользователю импортировать файл Office365 в CRM Zoho. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read.All | делегирована |  | Позволяет пользователю импортировать файл Office365 в CRM Zoho. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| Files.Read.Selected | делегирована | UserPrincipalName хранится для идентификации пользователя | Позволяет пользователю импортировать файл Office365 в CRM Zoho. | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| User.ReadBasic.All | делегирована | Свойства пользователей, такие как first_name, last_name, адрес электронной почты. | Чтение базовых профилей всех пользователей | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| email | делегирована | UserPrincipaName хранится для отступа пользователя | Просмотр адреса электронной почты пользователя | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| offline_access | делегирована |  | Сохранение доступа к данным, к которым он был предоставлен | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |
>| profile | делегирована |  | Просмотр базового профиля пользователя | [f6d7187a-b437-4eca-bbc5-c1331609fe07](https://docs.microsoft.com/microsoft-365-app-certification/azure/f6d7187a-b437-4eca-bbc5-c1331609fe07) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.

#### <a name="data-access-via-bots"></a>Доступ к данным с помощью ботов

Если это приложение содержит бот или расширение обмена сообщениями, оно может получить доступ к идентифицируемым данным конечного пользователя (EUII): реестр (имя, фамилия, имя отображения, адрес электронной почты) любого члена группы или чата, в который он добавлен. Использует ли это приложение эту возможность?

>Доступ к EUII не имеется.


#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>Мы не собираем EUII /PII в телеметрии и журналах. У нас есть скрипты для того, чтобы искать и предупреждать о том, как исправить все видимые данные

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Клиент может выбрать данные, которые необходимо шифровать с помощью EAR (Шифрование в покое) с помощью ограничений certaat. Пароли будут иметь по умолчанию. Логический доступ к серверам предоставляется через изолированную выделенную сеть и &amp; обеспечивается высокой безопасностью и


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

