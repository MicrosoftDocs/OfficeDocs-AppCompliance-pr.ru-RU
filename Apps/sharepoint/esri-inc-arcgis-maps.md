---
title: Общие сведения о Карты ArcGIS
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/21/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствии для ArcGIS Карты, политики обработки данных, сведения о каталоге приложений Microsoft Cloud App Security, а также сведения о безопасности и соответствии в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: ae6a908d70cb8714676832c6dacee5f189f73998
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225153"
---
# <a name="arcgis-maps-overview"></a>Общие сведения о Карты ArcGIS

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 21 июля 2021 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003118" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые Esri, Inc. корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | ArcGIS Maps |
| ID | WA200003118 |
| Office 365 поддерживаемые клиенты | SharePoint 2016 или более поздней версии |
| Название партнерской компании | Esri, Inc. |
| URL-адрес веб-сайта партнера | [https://www.esri.com](https://www.esri.com) |
| URL-адрес политики конфиденциальности | [https://www.esri.com/legal/privacy-arcgis](https://www.esri.com/legal/privacy-arcgis) |
| URL-адрес условий использования | [https://www.esri.com/en-us/legal/terms/master-agreement-pro...](https://www.esri.com/en-us/legal/terms/master-agreement-product) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена корпорацией Esri, Inc. о том, как это приложение собирает и хранит данные организации, а также о том, как ваша организация будет контролировать данные, собираемые приложением.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Выведите [список Graph майкрософт, необходимых](/graph/permissions-reference) этому приложению.

>Это приложение не использует microsoft Graph.


#### <a name="non-microsoft-services-used"></a>Не службы Майкрософт

Если приложение передает или предоставляет общий доступ к данным организации службе сторонних поставщиков, выведите список используемых приложением сторонних служб, какие данные передаются, и укажите обоснование, по которым приложение должно передавать эти сведения.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

Отображаются ли в телеметрии или журналах этого приложения какие-либо идентифицируемые сведения организации (OII) или определяемые пользователем сведения (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>В телеметрии или журналах приложений не отображаются OII или EUII.

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления для данных, хранящихся партнером

Описать, как администраторы организации могут управлять своей информацией в партнерских системах? например удаление, хранение, аудит, архивирование, политика конечных пользователей и т. д.

>Администраторы клиентов могут контролировать доступ пользователей к данным на уровне организации или проекта. Запросы проверяются в списках управления доступом перед чтением или записью данных. Данные, передаваемые конечным пользователям и внешним службам и от них, шифруются с помощью ПРОТОКОЛА HTTPS (только TLS 1.2).

#### <a name="human-review-of-organizational-information"></a>Проверка информации организации человеком

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранящихся в этом приложении?

>Нет

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Ниже приведены сведения [из Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) каталога.

<iframe height='1020' title='Microsoft Cloud App Security сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/27233' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/27233" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>Сведения об удостоверении

Эта информация предоставлена корпорацией Esri, Inc. о том, как это приложение обрабатывает проверку подлинности, авторизацию, рекомендации по регистрации приложений и другие критерии идентификации.

| **Information** | **Отклик** |
|:----------------|:-------------|
| Вы интегрируете с Microsoft Identify Platform (Azure AD)?  | Да |
| Вы просматривали и соблюдали все применимые рекомендации, описанные в платформа удостоверений Майкрософт интеграции?  | Да |
| Использует ли ваше приложение MSAL (библиотека проверки подлинности Майкрософт) для проверки подлинности? | Нет |
| Поддерживает ли ваше приложение политики условного доступа? | Да |
| Перечисление поддерживаемых типов политик | ArcGIS Online использует модель контроль доступа ролей (RBAC). Все пользователи в решении должны иметь роль, к которой им предоставляется доступ. |
| Запрашивает ли ваше приложение минимальные разрешения для вашего сценария? | Да |
| Точно ли статически зарегистрированные разрешения вашего приложения отражают разрешения, которые приложение будет запрашивать динамически и постепенно? | Нет |
| Поддерживает ли ваше приложение мультитенантность? | Да |
| Имеет ли ваше приложение конфиденциальный клиент? | Да |
| У вас есть все URI перенаправления, зарегистрированные для вашего приложения? | Да |
| Предоставляет ли ваше приложение какие-либо веб-API? | Да |
| Разрешает ли модель разрешений выполнять вызовы только в том случае, если клиентское приложение получает соответствующее согласие? | Да |
| Использует ли ваше приложение API предварительной версии? | Нет |
| Использует ли ваше приложение нерекомендуемые API? | Нет |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
