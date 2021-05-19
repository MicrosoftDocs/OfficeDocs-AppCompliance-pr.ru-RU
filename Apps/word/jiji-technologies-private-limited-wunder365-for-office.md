---
title: Информация о применении для Wunder365 для Office, представленная JiJi Technologies Private Limited
ms.author: elmalova
author: elenamalova
ms.date: 12/15/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Wunder365 для Office, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 84138d8471b342ad67e2bad34b70166ddb77a539
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52550399"
---
# <a name="wunder365-for-office"></a>Wunder365 для Office

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком на: Декабрь 15, 2020</p>

* <a href="https://appsource.microsoft.com/product/office/WA200001529" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная JiJi Technologies Private Limited корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Wunder365 для Office |
| ID | WA200001529 |
| Office 365 клиенты поддержали | Excel 2016 или позже на Mac, Excel 2013 или позже Windows, Excel в Интернете, Word 2016 или позже на Mac, Word в Интернете, Word 2013 или позже Windows, OneNote в Интернете |
| Название компании-партнера | JiJi Технологии Частная Лимитед |
| URL-адрес веб-сайта партнера | [https://appsource.microsoft.com/marketplace/apps?product=of...](https://appsource.microsoft.com/marketplace/apps?product=office) |
| URL политики конфиденциальности | [https://www.wunder365.com/office-addin-privacy-policy](https://www.wunder365.com/office-addin-privacy-policy) |
| URL условий использования | [https://go.microsoft.com/fwlink/?linkid=2041178](https://go.microsoft.com/fwlink/?linkid=2041178) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена JiJi Technologies Private Limited о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | Делегированные | Данные не хранятся. | Чтобы получить/обновить задачи планировщика, опубликовать обновления задач в канале команды | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| Mail.Send | Делегированные | Данные не хранятся. | Разрешить приложению отправлять пользователям уведомления по электронной почте | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| offline_access | Делегированные | Данные не хранятся. | Чтобы пользователь не вошел в систему. | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| openid | Делегированные | Данные не хранятся. | Позволяет пользователям войти в систему с организационной учетной записью | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |
>| profile | Делегированные | UPN, Идентификатор пользователя, Идентификатор электронной почты, Идентификатор арендатора для проверки лицензирования, бесплатная лицензия. | Позволяет пользователям войти в систему с организационной учетной записью | 3c95a8b6-b71c-4c4a-8a1a-c7b9b80d9e9c |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Мы за входя в Azure Application Insights. Мы регистрим идентификатор клиента и идентификатор электронной почты пользователя, чтобы выявить проблемы и помочь клиентам решить проблемы.


#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Все веб-приложения служба хранилища ресурсы расположены в подписке, которая не подключена к нашей компании AAD только с администраторами, которые имеют доступ к ресурсам. Для этих администраторов требуется 2FA. 


#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36250" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Идентификационная информация

Эта информация была предоставлена JiJi Technologies Private Limited о том, как это приложение обрабатывает аутентификацию, авторизацию, лучшие практики регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Интегрируесь ли вы с платформой Microsoft Identify Platform (Azure AD)?  | Да |
| Рассмотрели ли вы и соблюдали все применимые передовой опыт, изложенные в контрольном платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (Библиотека аутентификации Майкрософт) для проверки подлинности? | Да |
| Поддерживает ли ваше приложение политику условного доступа? | Да |
| Перечислите типы поддерживаемых политик | Требование многофакторной аутентификации для пользователей с административными ролями, требование многофакторной аутентификации для задач управления Azure, блокирование вовсов для пользователей, пытающихся использовать устаревшие протоколы аутентификации, требование доверенных мест для регистрации Multi-Factor Authentication Azure, блокирование или предоставление доступа из определенных мест, блокирование рискованного поведения в системе регистрации |
| Запрашивает ли приложение наименьшее разрешение на привилегии для вашего сценария? | Да |
| Точно ли зарегистрированные разрешения вашего приложения отражают разрешения, которые ваше приложение будет запрашивать динамически и постепенно? | Да |
| Поддерживает ли ваше приложение мульти-аренду? | Да |
| Есть ли у вашего приложения конфиденциальный клиент? | Да |
| У вас есть все перенаправление идентификатора объединенных ресурсов (URI), зарегистрированного для вашего приложения? | Да |
| Что следует избегать использования приложения для вашего приложения? | - Wildcard перенаправить URIs,<br/>- OAuth2 Неявные Flow, если требуется для SPA<br/>- Ресурс Владелец пароль учетных данных (ROPC) поток |
| Предоставляет ли ваше приложение какие-либо веб-API? | Нет |
| Использует ли приложение API-версии предварительного просмотра? | Да |
| Использует ли приложение увеные API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
