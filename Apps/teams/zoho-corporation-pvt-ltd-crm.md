---
title: Информация о заявке для ЗОХО CRM от Зохо Корпорации Pvt Ltd
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для CRM, политики обработки данных, Microsoft Cloud App Security каталога приложений и информации о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 5448307eeccd20e77b25282f299b52b094077b82
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550509"
---
# <a name="zoho-crm"></a>Zoho CRM

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://teams.microsoft.com/l/app/003a8a54-9d27-41cd-9c28-aec5875a3497" target="_blank">Посмотреть в Teams магазине</a>
* <a href="https://appsource.microsoft.com/product/office/WA104382094" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная корпорацией Зохо Pvt Ltd корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Zoho CRM |
| ID | WA104382094 |
| Office 365 клиенты поддержали | Microsoft Teams |
| Название компании-партнера | Zoho Corporation Pvt Ltd |
| URL-адрес веб-сайта партнера | [https://www.zoho.com/](https://www.zoho.com/) |
| URL-адрес Teams страницы информации о приложениях | [https://www.zoho.com/crm/help/microsoft-teams-integration.h...](https://www.zoho.com/crm/help/microsoft-teams-integration.html) |
| URL политики конфиденциальности | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL условий использования | [https://www.zoho.com/crm/zohocrm-terms.html](https://www.zoho.com/crm/zohocrm-terms.html) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена корпорацией Зохо Pvt Ltd о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые приложение собирает.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Делегированные | Календарь Folder Id хранится для синхронизации контактов от Цохо CRM до Microsoft &amp; наоборот. Информация о календаре, event_name, event_location, participant_details хранится. | Позволяет пользователю синхронизировать события Office365 с CRM Зохо. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Contacts.ReadWrite | Делегированные | Контакты Folder Id хранятся для синхронизации контактов от CRM зоохо до Microsoft &amp; наоборот. Хранится контактная информация, first_name, last_name, адрес электронной почты. | Позволяет пользователю синхронизировать контакты Office365 с CRM Зохо. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Делегированные |  | Позволяет пользователю импортировать файл Office365 в CRM Зохо. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.All | Делегированные |  | Позволяет пользователю импортировать файл Office365 в CRM Зохо. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Делегированные | UserPrincipalName хранится для идентификации пользователя | Позволяет пользователю импортировать файл Office365 в CRM Зохо. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Делегированные | Свойства пользователя, такие как first_name, last_name адрес электронной почты. | Чтение базовых профилей всех пользователей | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Делегированные | UserPrincipaName хранится для отступов пользователей | Просмотр адреса электронной почты пользователя | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Делегированные |  | Сохранение доступа к данным, к которым он был предоставлен | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | Делегированные |  | Просмотр основного профиля пользователя | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.

#### <a name="data-access-via-bots"></a>Доступ к данным через ботов

Если это приложение содержит бота или расширение обмена сообщениями, оно может получить доступ к информации, идентифицируемой конечного пользователя (EUII): реестр (имя, фамилия, имя дисплея, адрес электронной почты) любого члена команды в команде или чате, к которому оно добавлено. Использует ли это приложение эту возможность?

>Доступ к EUII не доступен.


#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Мы не собираем EUII / PII в телеметрии и журналах. У нас есть скрипты для и оповещения для фиксации любых таких данных, видимых

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Клиент может выбрать данные, которые должны быть зашифрованы через EAR (Encryption At Rest) с ограничениями certaat. Пароли будут хэшированы по умолчанию. Логический доступ к серверам обеспечивается через изолированную &amp; выделенную сеть и


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/22307" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

