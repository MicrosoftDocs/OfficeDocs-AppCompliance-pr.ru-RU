---
title: Информация о применении для инструмента отчетности iPlanner для Office 365 планировщика iGlobe
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Вся доступная информация о безопасности и соответствии требованиям для инструмента отчетности iPlanner для Office 365 Planner, политики обработки данных, сведения о каталоге приложений Microsoft Cloud App Security и информация о безопасности/соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: a577fcc75982703bfae0de740a7e69d9d13e509a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52548769"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>Инструмент отчетности iPlanner для Office 365 планировщика

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная iGlobe корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Инструмент отчетности iPlanner для Office 365 планировщика |
| ID | WA104380686 |
| Office 365 клиенты поддержали | Excel 2016 или позже Windows, Excel в Интернете, Excel 2016 или позже на Mac |
| Название компании-партнера | iGlobe |
| URL-адрес веб-сайта партнера | [https://www.iglobecrm.com/](https://www.iglobecrm.com/) |
| URL политики конфиденциальности | [https://iglobecrm.com/content/legal-information](https://iglobecrm.com/content/legal-information) |
| URL условий использования | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474836912/Product_42949680354/Asset_9d620695-979f-49e4-bc56-98259b0cdeb2/EULAPlanner.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена iGlobe о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | Делегированные | Данные не хранятся в базах данных приложений. | Для создания записи календаря в&#8217;в срок выполнения задачи. |  |
>| Directory.AccessAsUser.All | Делегированные | Данные не хранятся в базах данных приложений. | Для проверки пользователь имеет согласие и имеет доступ к использованию API. |  |
>| Directory.ReadWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Чтобы получить задание планировщика, Outlook To Do и обновлять их. Создание новой задачи планировщика. |  |
>| Files.ReadWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Доступ к файлу в виде вложения и загрузка файлов к задаче. |  |
>| Group.Read.All | Делегированные | Данные не хранятся в базах данных приложений. | Чтобы получить список плана и обновить задачу. |  |
>| Group.ReadWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Чтобы получить задание планировщика и добавить новые задачи обновить ведро и плавать линии. |  |
>| Mail.Read | Делегированные | Данные не хранятся в базах данных приложений. | User.Read, чтобы получить планировщик задачи для Outlook To Do, помечены письма и их обновления. Создание новой задачи планировщика |  |
>| Mail.ReadWrite | Делегированные | Данные не хранятся в базах данных приложений. | Чтобы показать почту и отправить почту. |  |
>| Mail.readWrite.All | Делегированные | Данные не хранятся в базах данных приложений. | Получить почтовую тему из выбранной почты. Позволяет приложению получать информацию из выбранной электронной почты, позволяющую скопировать поле описания в описание задачи и позволяющую сохранить вложения из почты или самой почты к задаче. Отправить уведомление. |  |
>| Tasks.ReadWrite | Делегированные | Данные не хранятся в базах данных приложений. | Чтобы получить подписанный в пользователей Outlook To Do обновления User.Read, чтобы получить планировщик задачу Outlook To Do, помечены письма и их обновления. Создание новой задачи планировщика. |  |
>| User.Read | Делегированные | Данные не хранятся в базах данных приложений. | Вход и чтение профиля пользователя |  |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>iGlobe собирает данные для эффективной работы и предоставления вам наилучшего опыта работы с нашими продуктами и сервисом. Для лицензирования: Данные, собранные для администрирования лицензионного счета организации&#8217;, например, при развертывании бесплатных надстройок, создании пробной подписки или покупке подписки. Собирается следующая информация. 
- Для финансовых целей: название и адрес компании
- Подписчики: имя пользователя и электронная почта

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Все данные на собственного арендатора клиента. Данные приложения не хранятся. Современное дополнение работает в песочнице браузера, &#8220;из процесса&#8221;. Он взаимодействует с данными пользователей с помощью службы Майкрософт. Надстройа может получить доступ только к данным, с которыми работает пользователь.

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

