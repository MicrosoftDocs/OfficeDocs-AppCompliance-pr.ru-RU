---
title: Информация о применении для Salesforce по salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: Вся доступная информация о безопасности и соответствии требованиям для Salesforce, ее политики обработки данных, Microsoft Cloud App Security информация каталога приложений и информация о безопасности/соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 29c00595a806c5144b34701ba54860353f9cafc0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553710"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчиком: 16 декабря 2019 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">Посмотреть в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Информация, предоставленная salesforce.com корпорацией Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Имя приложения | Salesforce |
| ID | WA104379334 |
| Office 365 клиенты поддержали | Outlook 2013 или позже Windows, Outlook 2016 или позже на Mac, Outlook в Интернете |
| Название компании-партнера | salesforce.com |
| URL-адрес веб-сайта партнера | [https://www.salesforce.com/](https://www.salesforce.com/) |
| URL политики конфиденциальности | [https://www.salesforce.com/company/privacy](https://www.salesforce.com/company/privacy) |
| URL условий использования | [https://pinpointprod.blob.core.windows.net/marketing/Partne...](https://pinpointprod.blob.core.windows.net/marketing/Partner_21474843361/Product_42949677285/Asset_540860c0-685e-4047-9f3a-082a748e57a2/LIGHTNINGFOROUTLOOKOrderFormSu.doc) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Как приложение обрабатывает данные

Эта информация была предоставлена salesforce.com о том, как это приложение собирает и хранит организационные данные и контроль, который ваша организация будет иметь над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Перечислите любые [разрешения Майкрософт Graph, которые](https://docs.microsoft.com/graph/permissions-reference) требуется этому приложению.

>Это приложение не использует Microsoft Graph.

#### <a name="data-access-using-other-microsoft-apis"></a>Доступ к данным с помощью других API Майкрософт

Приложения и надстройки, построенные на веб-Microsoft 365 могут использовать дополнительные API Майкрософт, кроме Microsoft Graph для сбора или обработки идентифицируемой организационной информации (OII). Перечислите все API Майкрософт, кроме Microsoft, Graph использует это приложение.

>| **API** |  **Собирается ли OII?** |  **Что такое OII?** | **Обоснование сбора OII?** | **Хранится ли OII?** | **Обоснование хранения OII?** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| API JavaScript для Office | Да | Надстройки используют функции от Office.js и EWS для копирования содержимого и вложений об электронной почте Outlook пользователь решил войти в Salesforce. Аналогичные возможности используются на стороне календаря для регистрации назначений в Salesforce. |  | Надстройка использует такие функции, как getUserIdentityTokenAsync, чтобы получить текущую личность пользователя Outlook, GetItem (.js и EWS), чтобы получить и установить дополнительныеПредложения и содержание текущего сообщения электронной почты при сохранении записей Salesforce, GetAttachment (EWS) для извлечения вложений из Exchange и добавить в пару Salesforce электронной почты, UpdateItem (.js), GetFolder (.js), чтобы получить папку проектов, CreateItem (.js), который используется для создания проекта сообщения. |  |
>| Веб-службы Exchange (EWS) | Да | Надстройки используют функции от Office.js и EWS для копирования содержимого и вложений об электронной почте Outlook пользователь решил войти в Salesforce. Аналогичные возможности используются на стороне календаря для регистрации назначений в Salesforce. |  | Надстройка использует такие функции, как getUserIdentityTokenAsync, чтобы получить текущую личность пользователя Outlook, GetItem (.js и EWS), чтобы получить и установить дополнительныеПредложения и содержание текущего сообщения электронной почты при сохранении записей Salesforce, GetAttachment (EWS) для извлечения вложений из Exchange и добавить в пару Salesforce электронной почты, UpdateItem (.js), GetFolder (.js), чтобы получить папку проектов, CreateItem (.js), который используется для создания проекта сообщения. |  |

#### <a name="non-microsoft-services-used"></a>Неутяхие службы Майкрософт используются

Если приложение передает или делится организационными данными с службой, не являяся корпорацией Майкрософт, перечислите не-Microsoft службы приложение использует, какие данные передаются, и включить обоснование того, почему приложение должно передать эту информацию.

>Неуготовные службы Майкрософт используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Появляется ли в телеметрии или журналах этого приложения какая-либо организационная идентифицируемая информация (OII) или информация, идентифицируемая конечных пользователей (EUII)? Если да, опишите, какие данные хранятся и каковы политики хранения и удаления?

>Нет

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационный контроль за данными, хранящимися партнером

Опишите, как администраторы организации могут контролировать свою информацию в партнерских системах? например, удаление, удержание, аудит, архивирование, политика конечных пользователей и т.д.

>Хранение Salesforce описано в Руководстве по безопасности по https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>Человеческий обзор организационной информации

Участвуют ли люди в анализе или анализе данных, идентифицируемых в организации (OII), которые собираются или хранятся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Информация из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) появляется ниже.

<iframe height='1020' title='Microsoft Cloud App Security информация' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11114" target="_blank">Просмотр в новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

