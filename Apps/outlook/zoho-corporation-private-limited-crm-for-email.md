---
title: Информация о применении для ЗОХО CRM для электронной почты от Зохо Корпорации Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для электронной почты, политики обработки данных, информации о каталоге приложений Microsoft Cloud App Security и информации о безопасности/соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4f06fd2f6a14bbad4d1265df9754884d515f6cb6
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553681"
---
# <a name="zoho-crm-for-email"></a>Зохо CRM для электронной почты

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379468" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная корпорацией Зохо Private Limited корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Зохо CRM для электронной почты |
| ID | WA104379468 |
| Office 365 клиенты поддержали | Outlook 2013 или позже Windows, Outlook 2016 или позже на Mac, Outlook в Интернете |
| Название компании-партнера | Zoho Corporation Private Limited |
| URL-адрес веб-сайта партнера | [https://www.zoho.com/](https://www.zoho.com/) |
| URL политики конфиденциальности | [https://www.zoho.com/privacy.html](https://www.zoho.com/privacy.html) |
| URL условий использования | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;омктюен-США](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена корпорацией Зохо Private Limited о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые приложение собирает.

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

