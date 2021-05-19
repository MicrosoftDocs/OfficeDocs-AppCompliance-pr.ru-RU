---
title: Информация о применении для FormMachines для SharePoint от ENTERPRISE DIGITAL MACHINES PTY LTD
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для FormMachines для SharePoint, ее политики обработки данных, ее Microsoft Cloud App Security информация каталога приложений, а также информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4c423cac4f879ba4f73a9bba5f9004acb4cfa21a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553550"
---
# <a name="formmachines-for-sharepoint"></a>Форм-мейчины для SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 3 ноября 2020 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация предоставлена ENTERPRISE DIGITAL MACHINES PTY LTD корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Форм-мейчины для SharePoint |
| ID | WA200000357 |
| Office 365 клиенты поддержали | SharePoint 2016 г. или позже |
| Название компании-партнера | ПРЕДПРИЯТИЕ ЦИФРОВЫЕ МАШИНЫ PTY LTD |
| URL-адрес веб-сайта партнера | [https://www.formmachines.com/](https://www.formmachines.com/) |
| URL политики конфиденциальности | [https://www.formmachines.com/?dirKey=fm-privacy](https://www.formmachines.com/?dirKey=fm-privacy) |
| URL условий использования | [https://www.formmachines.com/?dirKey=fm-terms-of-use](https://www.formmachines.com/?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена ENTERPRISE DIGITAL MACHINES PTY LTD о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>| **Permission**  | **Тип разрешения (Делегировано/Применение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование для его хранения?** | **Идентификатор приложения Azure AD** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | Делегированные | (Вход, электронная почта, Azure Guid, displayName, first_login_date_time) | позволяет пользователю войти в систему и дает приложению доступ к их UPN, чтобы обеспечить бесшумный логин, позволяет нам уникально идентифицировать каждого пользователя | 8c87660f-d36f-41f6-b0ae-025253f380aa |


#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>. Мы только журнал ошибок . В нашем журнале ошибок мы логируем только информацию об ошибках. Какой клиент или клиент спровоцировал определенную ошибку, не собирается. Только инженеры поддержки имеют доступ к журналам ошибок. Журналы ошибок просматриваются в Интернете, не загружаются и не просматриваются. Записи ошибок удаляются автоматически через 30 дней

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>. Данные хранятся в американских центрах обработки данных Azure. Предоставленные клиентом данные, такие как шаблоны и материалы, шифруются в DB. Файл вложения хранятся в частных контейнерах Azure BLOB, пользователи должны проверить подлинность перед доступом к ним. У нас есть максимум два администратора, которые могут получить доступ к нашим производственным активам, для устранения неполадок и развертывания. Эти две учетные записи администратора разделены по-разному на все другие учетные записи. Количество доступа администратора никогда не превысит двух

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

