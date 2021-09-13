---
title: Сведения о приложениях для средства отчетности iPlanner для Office 365 планировщика по iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Все доступные сведения о безопасности и соответствия требованиям для средства отчетности iPlanner для Office 365 Planner, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3591c67721188d8dc70bf4f2cf0e34bdb9ffc506
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287585"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>средство отчетности iPlanner для Office 365 планировщика

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчика: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые iGlobe Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | средство отчетности iPlanner для Office 365 планировщика |
| Идентификатор | WA104380686 |
| Office 365 поддерживаемые клиенты | Excel 2016 или более поздней Windows, Excel в Интернете, Excel 2016 или позднее на Mac |
| Имя компании-партнера | iGlobe |
| URL-адрес веб-сайта-партнера | [https://iglobecrm.com/](https://iglobecrm.com/) |
| URL-адрес политики конфиденциальности | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| URL-адрес терминов использования | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена iGlobe о том, как это приложение собирает и хранит организационные данные, а также о том, как ваша организация будет управлять данными, собираемой приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Создание записи календаря в календаре пользователя&#8217;календаря в срок действия задачи. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.AccessAsUser.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы проверить, у пользователя есть согласие и доступ к использованию API. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить задачу планирования Outlook To Do, помечайте и обновляйте их. Создание новой задачи планировщика. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Доступ к файлу в виде вложения и отправка файлов в задачу. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить список планов и обновить задачу. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить задачу планировщика и добавить новые задачи, обновим ковш и линию плавания. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | делегирована | Данные не хранятся в базах данных приложений. | User.Read, чтобы получить задачу планирования Outlook To Do, помеченные электронные почты и их обновление. Создание новой задачи планировщика | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтобы показать почту и отправить почту. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite.All | делегирована | Данные не хранятся в базах данных приложений. | Получите тему почты из выбранной почты. Позволяет приложению получать сведения из выбранной электронной почты, что позволяет скопировать поле описания в описание задачи и сохранить вложения от почты или самой почты к задаче. Отправить уведомление. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Tasks.ReadWrite | делегирована | Данные не хранятся в базах данных приложений. | Чтобы получить подписанный в пользователях Outlook To Do и обновить User.Read, чтобы получить задачу планирования Outlook To Do, помечены электронные почты и обновить их. Создание новой задачи планировщика. | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | делегирована | Данные не хранятся в базах данных приложений. | Вход и чтение профиля пользователя | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>iGlobe собирает данные для эффективной работы и предоставляет наилучшие сведения о наших продуктах и услугах. Для лицензирования. Данные, собранные для администрирования вашей&#8217;учетной записи лицензирования, например при развертывании бесплатных надстройок, создании пробной подписки или покупке подписки. Собираются следующие сведения. 
- Для финансовых целей: имя и адрес компании
- Подписанные пользователи: имя пользователя и электронная почта

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>Все данные принадлежат клиенту. Данные приложения не хранятся. Современная надстройка запускается в песочнице браузера, &#8220;из процесса&#8221;. Он взаимодействует с данными пользователей с помощью службы Майкрософт. Надстройка может получать доступ только к данным, с которыми работает пользователь.

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

