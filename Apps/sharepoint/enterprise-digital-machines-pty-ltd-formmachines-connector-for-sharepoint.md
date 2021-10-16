---
title: Сведения о приложениях для соединиттеля FormMachines для SharePoint КОРПОРАТИВНЫЕ ЦИФРОВЫЕ МАШИНЫ PTY LTD
ms.author: elmalova
author: elenamalova
ms.date: 09/25/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Все доступные сведения о безопасности и соответствия требованиям для Connector FormMachines для SharePoint, политики обработки данных, сведения о каталоге Microsoft Cloud App Security приложений и сведения о безопасности и соответствии требованиям в реестре CSA STAR.
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3d5cab668924d0edfed32a807096be68519a775f
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/16/2021
ms.locfileid: "60410483"
---
# <a name="formmachines-connector-for-sharepoint"></a>Соединители FormMachines для SharePoint

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>Последнее обновление разработчика: 3 ноября 2020 г.</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">Просмотр в AppSource</a>

::: zone pivot="general"

### <a name="general-information"></a>Общие сведения

Сведения, предоставляемые КОРПОРАЦИЕЙ ЦИФРОВЫХ МАШИН PTY LTD Корпорации Майкрософт:

| **Information** | **Отклик** |
|:----------------|:-------------|
| Название приложения | Соединители FormMachines для SharePoint |
| Идентификатор | WA200000357 |
| Office 365 поддерживаемые клиенты | SharePoint 2016 или более поздней |
| Имя компании-партнера | КОРПОРАТИВНЫЕ ЦИФРОВЫЕ МАШИНЫ PTY LTD |
| URL-адрес веб-сайта-партнера | [https://www.formmachines.com](https://www.formmachines.com) |
| URL-адрес политики конфиденциальности | [https://www.formmachines.com?dirKey=fm-privacy](https://www.formmachines.com?dirKey=fm-privacy) |
| URL-адрес терминов использования | [https://www.formmachines.com?dirKey=fm-terms-of-use](https://www.formmachines.com?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>Обработка данных приложением

Эта информация предоставлена КОРПОРАТИВНЫМИ ЦИФРОВЫМИ МАШИНАМИ PTY LTD о том, как это приложение собирает и хранит организационные данные, а также управление, которое будет иметь ваша организация над данными, которые собирает приложение.

#### <a name="data-access-using-microsoft-graph"></a>Доступ к данным с помощью Microsoft Graph

Список всех [разрешений Graph Майкрософт,](https://docs.microsoft.com/graph/permissions-reference) которые требуется этому приложению.

>| **Разрешение**  | **Тип разрешения (Делегированная/ приложение)** | **Собираются ли данные? Обоснование для его сбора?** | **Хранятся ли данные? Обоснование его хранения?** | **Azure AD App ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| User.Read | делегирована | (вход, электронная почта, Azure Guid, displayName, first_login_date_time) | позволяет пользователю войти в систему и предоставляет приложению доступ к его upN для обеспечения бесшумного входа, позволяет нам идентифицировать каждого пользователя. | [8c87660f-d36f-41f6-b0ae-025253f380aa](https://docs.microsoft.com/microsoft-365-app-certification/azure/8c87660f-d36f-41f6-b0ae-025253f380aa) |


#### <a name="non-microsoft-services-used"></a>Не-службы Майкрософт используется

Если приложение передает или делится организационными данными с не-службой Майкрософт, укай список службы, не microsoft, которую использует приложение, какие данные передаются, и включай обоснование необходимости передачи этой информации приложением.

>Не службы Майкрософт не используются.



#### <a name="telemetry-data"></a>Данные телеметрии

В телеметрии или журналах этого приложения отображаются какие-либо идентифицируемые организационные сведения (OII) или данные, идентифицируемые конечным пользователем (EUII) ? Если да, опишите, какие данные хранятся и какие политики хранения и удаления?

>. Мы только журнал ошибок . В журнале ошибок мы внося только сведения об ошибках. Какой клиент или клиент спровоцировали определенную ошибку, не собирается. Доступ к журналам ошибок имеют только инженеры службы поддержки. Журналы ошибок просматриваются в Интернете, не загружаются и не просматриваются. Журналы ошибок удаляются автоматически через 30 дней

#### <a name="organizational-controls-for-data-stored-by-partner"></a>Организационные элементы управления данными, хранимые партнером

Описание того, как администраторы организации могут управлять своими сведениями в партнерских системах? например, удаление, хранение, аудит, архивация, политика конечных пользователей и т. д.

>. Данные хранятся в американских центрах обработки данных Azure. Предоставленные клиентом данные, такие как шаблоны и отправки, шифруются в DB. Вложения файлов хранятся в частных контейнерах Azure BLOB, перед доступом к ним пользователи должны пройти проверку подлинности. У нас есть максимум два администратора, которые могут получить доступ к нашим производственным активам для устранения неполадок и развертывания. Эти две учетные записи администратора разделяются по-разному со всеми другими учетными записями. Количество доступа администратора никогда не будет превышать двух

#### <a name="human-review-of-organizational-information"></a>Обзор сведений об организации

Участвуют ли люди в просмотре или анализе любых данных, идентифицируемых в организации (OII), собираемых или хранимых этим приложением?

>Да

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

Сведения из [Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) ниже.

<iframe height='1020' title='Microsoft Cloud App Security Сведения' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">Просмотр на новой вкладке</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


