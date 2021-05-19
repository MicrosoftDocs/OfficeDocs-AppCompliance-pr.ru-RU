---
title: Информация о применении для ServiceDesk Plus для электронной почты от Зохо Корпорации Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для ServiceDesk Plus для электронной почты, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dc342375eba7084f5afb31b0f879e46e959fa970
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553660"
---
# <a name="servicedesk-plus-for-email"></a>ServiceDesk Plus для электронной почты

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381518" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная корпорацией Зохо Private Limited корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | ServiceDesk Plus для электронной почты |
| ID | WA104381518 |
| Office 365 клиенты поддержали | Outlook 2013 или позже Windows, Outlook 2016 или позже на Mac, Outlook в Интернете |
| Название компании-партнера | Zoho Corporation Private Limited |
| URL-адрес веб-сайта партнера | [https://www.zoho.com/](https://www.zoho.com/) |
| URL политики конфиденциальности | [https://www.manageengine.com/privacy.html](https://www.manageengine.com/privacy.html) |
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
>| Calendars.ReadWrite | приложение |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read | Делегированные |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| Files.Read.Selected | Делегированные |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read | Делегированные | Идентификатор электронной почты пользователя. | Позволяет пользователю войти в систему и предоставляет приложению доступ к их UPN, чтобы обеспечить бесшумный вход. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.Read.All | приложение |  |  | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| User.ReadBasic.All | Делегированные | Идентификатор электронной почты, имя, идентификатор сотрудника, название Телефон, мобильный, сайт, отдел, место, профиль фото пользователя. | Позволяет импортировать основную информацию пользователей из Azure Active Directory. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| email | Делегированные | Идентификатор электронной почты пользователя. | Просмотр адреса электронной почты пользователя. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| offline_access | Делегированные |  | Поддерживайте доступ к данным, к которые вы получили доступ. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |
>| profile | Делегированные |  | Просмотр основного профиля пользователя. | f6d7187a-b437-4eca-bbc5-c1331609fe07 |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Мы не собираем EUII / PII в телеметрии / журналы. У нас есть скрипты на месте, которые ищут шаблоны и оповещения для его фиксации

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Все данные зашифрованы в REST. Только уполномоченные лица имеют доступ к системе, которая в любом случае защищена доступом, полностью проверена на все виды доступа. МИД для доступа, авторизованные счета поддерживаются в корпоративном каталоге и принимающей


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/18802" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

