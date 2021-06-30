---
title: Руководство по пользователю для приложений SaaS
author: LGerrard
ms.author: legerrar
description: Руководство пользователя ISV для Microsoft 365 SaaS программы соответствия требованиям к приложениям
keywords: Руководство пользователя ISV для Microsoft 365 SaaS программы соответствия требованиям к приложениям
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: b3b8c37a1babf2f941f5764fddd30523319d9a34
ms.sourcegitcommit: f6f3551bf1c00013efb6313ca3dc280de697137d
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/29/2021
ms.locfileid: "53202780"
---
# <a name="partners-user-guide-for-microsoft-365-app-compliance-program---saas"></a><span data-ttu-id="f406b-104">Руководство для пользователей партнеров для Microsoft 365 приложения - SaaS</span><span class="sxs-lookup"><span data-stu-id="f406b-104">Partner's User Guide for Microsoft 365 App Compliance Program - SaaS</span></span>

|<span data-ttu-id="f406b-105">Этап</span><span class="sxs-lookup"><span data-stu-id="f406b-105">Phase</span></span>|<span data-ttu-id="f406b-106">Название</span><span class="sxs-lookup"><span data-stu-id="f406b-106">Title</span></span>|
|---|---|
|<span data-ttu-id="f406b-107">Этап 1</span><span class="sxs-lookup"><span data-stu-id="f406b-107">Phase 1</span></span>| <span data-ttu-id="f406b-108">Аттестация издателя</span><span class="sxs-lookup"><span data-stu-id="f406b-108">Publisher Attestation</span></span>|
|<span data-ttu-id="f406b-109">Этап 2</span><span class="sxs-lookup"><span data-stu-id="f406b-109">Phase 2</span></span>| <span data-ttu-id="f406b-110">Сертификация Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="f406b-110">Microsoft 365 Certification</span></span>|

## <a name="1-overview"></a><span data-ttu-id="f406b-111">1. Обзор</span><span class="sxs-lookup"><span data-stu-id="f406b-111">1. Overview</span></span> 

<span data-ttu-id="f406b-112">Этот документ выступает в качестве пошагового руководства пользователя для наших партнеров, зарегистрированных для Microsoft 365 программы соответствия требованиям к приложениям с целью пройти Publisher аттестацию и сертификацию для своих приложений SaaS, хотя портал Центра партнеров.</span><span class="sxs-lookup"><span data-stu-id="f406b-112">This document acts as a step-by-step user guide for our partners, enrolled for Microsoft 365 App Compliance program aiming to undergo Publisher Attestation and Certification for their SaaS apps, though the Partner Center portal.</span></span>

## <a name="2-acronyms--definitions"></a><span data-ttu-id="f406b-113">2. Акронимы & определения</span><span class="sxs-lookup"><span data-stu-id="f406b-113">2. Acronyms & Definitions</span></span>
|<span data-ttu-id="f406b-114">Сокращение</span><span class="sxs-lookup"><span data-stu-id="f406b-114">Acronym</span></span> | <span data-ttu-id="f406b-115">Определение</span><span class="sxs-lookup"><span data-stu-id="f406b-115">Definition</span></span> |
|----|----|
|[<span data-ttu-id="f406b-116">PC (Центр партнеров)</span><span class="sxs-lookup"><span data-stu-id="f406b-116">PC (Partner Center)</span></span>](https://partner.microsoft.com/)|<span data-ttu-id="f406b-117">Портал для всех партнеров Майкрософт.</span><span class="sxs-lookup"><span data-stu-id="f406b-117">A portal for all Microsoft partners.</span></span> <span data-ttu-id="f406b-118">Партнер входит в Центр партнеров и представляет анкету для самостоятельной оценки.</span><span class="sxs-lookup"><span data-stu-id="f406b-118">A partner logs in to Partner Center and submits self-assessment questionnaire.</span></span> <span data-ttu-id="f406b-119">Центр партнеров по [Microsoft 365 соответствия требованиям к приложениям](https://partner.microsoft.com/dashboard/home)</span><span class="sxs-lookup"><span data-stu-id="f406b-119">Partner Center for [Microsoft 365 App Compliance](https://partner.microsoft.com/dashboard/home)</span></span>|
|<span data-ttu-id="f406b-120">Независимый поставщик программного обеспечения</span><span class="sxs-lookup"><span data-stu-id="f406b-120">ISV</span></span> | <span data-ttu-id="f406b-121">Независимый поставщик программного обеспечения.</span><span class="sxs-lookup"><span data-stu-id="f406b-121">Independent Software Vendor a.k.a.</span></span> <span data-ttu-id="f406b-122">Партнер или разработчик</span><span class="sxs-lookup"><span data-stu-id="f406b-122">Partner or Developer</span></span> |
|<span data-ttu-id="f406b-123">Источник приложения</span><span class="sxs-lookup"><span data-stu-id="f406b-123">App Source</span></span> | <span data-ttu-id="f406b-124">Каталог приложений</span><span class="sxs-lookup"><span data-stu-id="f406b-124">Catalog of apps</span></span> |
|<span data-ttu-id="f406b-125">Пример</span><span class="sxs-lookup"><span data-stu-id="f406b-125">Example</span></span> |[<span data-ttu-id="f406b-126">Теперь виртуальный агент</span><span class="sxs-lookup"><span data-stu-id="f406b-126">Now virtual agent</span></span>](https://appsource.microsoft.com/product/office/WA104381816)|

## <a name="3-publisher-attestation-workflow"></a><span data-ttu-id="f406b-127">3. Publisher процесса проверки</span><span class="sxs-lookup"><span data-stu-id="f406b-127">3. Publisher Attestation Workflow</span></span>

<span data-ttu-id="f406b-128">**Главная страница.** Это посадочная страница после входа партнера в Центр партнеров.</span><span class="sxs-lookup"><span data-stu-id="f406b-128">**Home Page**: This is the landing page once a partner logs in to Partner Center.</span></span>

![Домашний экран Центра партнеров](../media/Saas1.PNG)
  
<span data-ttu-id="f406b-130">**Шаг 1:** слева от страницы на панели навигации:</span><span class="sxs-lookup"><span data-stu-id="f406b-130">**Step 1** : On the left side of the page, on the navigation bar:</span></span>

- <span data-ttu-id="f406b-131">Выбор коммерческого рынка</span><span class="sxs-lookup"><span data-stu-id="f406b-131">Select Commercial Marketplace</span></span>
- <span data-ttu-id="f406b-132">Выбор обзоров</span><span class="sxs-lookup"><span data-stu-id="f406b-132">Select Overview</span></span>

![Коммерческий рынок в Центре партнеров](../media/Saas2.PNG)
  
<span data-ttu-id="f406b-134">При выборе "Обзор" партнер может увидеть список приложений, доступных для запуска Microsoft 365 соответствия требованиям.</span><span class="sxs-lookup"><span data-stu-id="f406b-134">Upon selecting ‘Overview’, partner can see list of apps available to start the Microsoft 365 Compliance program.</span></span>
  
<span data-ttu-id="f406b-135">**Шаг 2.** Выберите приложение из списка, чтобы начать процесс Publisher проверки.</span><span class="sxs-lookup"><span data-stu-id="f406b-135">**Step 2**: Select an app from the list to begin the Publisher Attestation process.</span></span>

![Выбор приложения на коммерческом рынке](../media/Saas3.PNG)

<span data-ttu-id="f406b-137">При выборе приложения будет всплывающее другое панели навигации с параметром "Соответствие требованиям приложения".</span><span class="sxs-lookup"><span data-stu-id="f406b-137">On selecting an app, another navigation bar will pop up with option ‘App Compliance’.</span></span>
  
<span data-ttu-id="f406b-138">**Шаг 3.** Выберите "Соответствие требованиям приложения"</span><span class="sxs-lookup"><span data-stu-id="f406b-138">**Step 3**: Select 'App Compliance’</span></span>
  
![Соответствие требованиям приложений на коммерческом рынке](../media/Saas4.PNG)
  
<span data-ttu-id="f406b-140">**Шаг 4.** Заполните анкету самооценки для Publisher аттестации.</span><span class="sxs-lookup"><span data-stu-id="f406b-140">**Step 4**: Fill out the self-assessment questionnaire for Publisher Attestation.</span></span>

![Полное Publisher проверки](../media/UserGuidePhotos/5.5.png)
  
<span data-ttu-id="f406b-142">**ПРИМЕЧАНИЕ Если вы возвращались к обновлению или повторной отправке приложения, нажмите кнопку dropdown для "Выберите продукт", выберите приложение и нажмите кнопку "Клон".**</span><span class="sxs-lookup"><span data-stu-id="f406b-142">**NOTE If you are coming back to update/re-submit your application, click dropdown for ‘Choose the product’, select the app and click ‘Clone’.**</span></span>

![Функция клонирования](../media/UserGuidePhotos/05.png)

<span data-ttu-id="f406b-144">**Вы также можете использовать функцию импорт и экспорт, чтобы завершить форму автономной работы и импортировать ее после завершения.**</span><span class="sxs-lookup"><span data-stu-id="f406b-144">**You can also leverage the Import/Export feature to complete the form offline and import it once completed.**</span></span>

![Функция экспорта импорта](../media/UserGuidePhotos/06.png)
 
<span data-ttu-id="f406b-146">**Шаг 5.** После завершения нажмите кнопку "Отправить", теперь оценка будет "В стадии рассмотрения".</span><span class="sxs-lookup"><span data-stu-id="f406b-146">**Step 5**: Once completed, click on ‘Submit’, the assessment will now be ‘Under Review’.</span></span>
 
 <span data-ttu-id="f406b-147">![Отправка Publisher подтверждения ](../media/UserGuidePhotos/07.png) ![ отправки](../media/UserGuidePhotos/08.png)</span><span class="sxs-lookup"><span data-stu-id="f406b-147">![Submit Publisher Attesation](../media/UserGuidePhotos/07.png) ![Confirmation of submission](../media/UserGuidePhotos/08.png)</span></span>
  
<span data-ttu-id="f406b-148">**Утверждение и отклонение сценариев:**</span><span class="sxs-lookup"><span data-stu-id="f406b-148">**Approve/Reject Scenarios:**</span></span>
  
<span data-ttu-id="f406b-149">О.</span><span class="sxs-lookup"><span data-stu-id="f406b-149">A.</span></span> <span data-ttu-id="f406b-150">Publisher Отказ от проверки</span><span class="sxs-lookup"><span data-stu-id="f406b-150">Publisher Attestation Rejection</span></span>
- <span data-ttu-id="f406b-151">В случае отказа партнер может:</span><span class="sxs-lookup"><span data-stu-id="f406b-151">In case of rejection, a partner can:</span></span>
     - <span data-ttu-id="f406b-152">Просмотр отчета о сбое</span><span class="sxs-lookup"><span data-stu-id="f406b-152">View failure report</span></span>
          - <span data-ttu-id="f406b-153">Партнер будет уведомлен по электронной почте, и он может просматривать отчет о сбое в Центре партнеров</span><span class="sxs-lookup"><span data-stu-id="f406b-153">Partner will be notified via email, and they can view the failure report in Partner Center</span></span>
     - <span data-ttu-id="f406b-154">Обновление и повторное отправка анкеты самооценки.</span><span class="sxs-lookup"><span data-stu-id="f406b-154">Update and re-submit self-assessment questionnaire.</span></span>
        
![Publisher Заверение отклонено](../media/UserGuidePhotos/09.png)

<span data-ttu-id="f406b-156">B.</span><span class="sxs-lookup"><span data-stu-id="f406b-156">B.</span></span>  <span data-ttu-id="f406b-157">Publisher Утверждение проверки</span><span class="sxs-lookup"><span data-stu-id="f406b-157">Publisher Attestation Approval</span></span>
- <span data-ttu-id="f406b-158">После утверждения партнер может:</span><span class="sxs-lookup"><span data-stu-id="f406b-158">Upon approval, the partner can:</span></span>
     - <span data-ttu-id="f406b-159">Обновление и повторное тестирование</span><span class="sxs-lookup"><span data-stu-id="f406b-159">Update and resubmit attestation</span></span>
     - <span data-ttu-id="f406b-160">Просмотр завершенной Publisher проверки</span><span class="sxs-lookup"><span data-stu-id="f406b-160">View completed Publisher Attestation</span></span>
     - <span data-ttu-id="f406b-161">Запуск процесса Microsoft 365 сертификации</span><span class="sxs-lookup"><span data-stu-id="f406b-161">Start the Microsoft 365 Certification process</span></span>
        
 ![Publisher Завершено тестирование](../media/UserGuidePhotos/10.png)       
  
 ![Запуск Microsoft 365 сертификации](../media/UserGuidePhotos/11.png)
  
<span data-ttu-id="f406b-164">**Утверждение Publisher проверки: пример ссылки в AppSource для заверенных приложений издателя.**</span><span class="sxs-lookup"><span data-stu-id="f406b-164">**Post Publisher Attestation Approval: Example of link in AppSource for publisher attested apps.**</span></span>
  
![Пример утвержденных контактов](../media/UserGuidePhotos/12.png)
   
## <a name="4---microsoft-365-certification-workflow"></a><span data-ttu-id="f406b-166">4. Microsoft 365 процесса сертификации</span><span class="sxs-lookup"><span data-stu-id="f406b-166">4.   Microsoft 365 Certification Workflow</span></span>
  
<span data-ttu-id="f406b-167">Партнер может начать процесс сертификации, выбрав почтовый ящик и нажав кнопку "Отправить"</span><span class="sxs-lookup"><span data-stu-id="f406b-167">A partner can begin the Certification process by selecting the checkbox and clicking ‘Submit’</span></span>
  
![Начало Microsoft 365 сертификации](../media/UserGuidePhotos/13.png) 
  
<span data-ttu-id="f406b-169">**Шаг 1.** Начальная отправка документов</span><span class="sxs-lookup"><span data-stu-id="f406b-169">**Step 1** : Initial Document Submission</span></span>

<span data-ttu-id="f406b-170">Заполните все сведения, загрузите соответствующие документы и нажмите кнопку "Отправить"</span><span class="sxs-lookup"><span data-stu-id="f406b-170">Fill out all the details, upload relevant documents and click ‘Submit’</span></span>
  
<span data-ttu-id="f406b-171">![Начальная отправка ](../media/UserGuidePhotos/14.png) 
 ![ документа Отправка начальной отправки документа](../media/UserGuidePhotos/15.png)</span><span class="sxs-lookup"><span data-stu-id="f406b-171">![Initial Document Submission](../media/UserGuidePhotos/14.png) 
![Submit Initial Document Submission](../media/UserGuidePhotos/15.png)</span></span>
  
<span data-ttu-id="f406b-172">При нажатии кнопки отправка исходного документа будет рассмотрена.</span><span class="sxs-lookup"><span data-stu-id="f406b-172">On clicking submit, the initial document submission will be under review.</span></span>

![Начальная отправка документов в стадии рассмотрения](../media/UserGuidePhotos/16.png)
  
<span data-ttu-id="f406b-174">Аналитик запрашивает пересмотр, если исходные документы не являются достаточными или релевантны.</span><span class="sxs-lookup"><span data-stu-id="f406b-174">An analyst requests a revision in case the initial documents are not sufficient or relevant.</span></span> <span data-ttu-id="f406b-175">Аналитик будет работать с партнером, чтобы помочь получить нужные документы для утверждения.</span><span class="sxs-lookup"><span data-stu-id="f406b-175">The analyst will work with the partner to help get the right documents for approval.</span></span>

![Необходимые обновления](../media/UserGuidePhotos/17.png)

<span data-ttu-id="f406b-177">После утверждения аналитиком первоначальной отправки документа партнеру необходимо представить требования к контролю.</span><span class="sxs-lookup"><span data-stu-id="f406b-177">Once the analyst approves the initial document submission, the partner needs to submit the control requirements.</span></span>
  
<span data-ttu-id="f406b-178">**Шаг 2.** Отправка требований к контролю</span><span class="sxs-lookup"><span data-stu-id="f406b-178">**Step 2**: Control Requirement Submission</span></span>
  
<span data-ttu-id="f406b-179">Заполните все сведения, загрузите соответствующие документы и нажмите кнопку "Отправить"</span><span class="sxs-lookup"><span data-stu-id="f406b-179">Fill out all the details, upload relevant documents and Click ‘Submit’</span></span>

![Полные требования к контролю](../media/UserGuidePhotos/18.png)
  
![Upload Требования к контролю](../media/UserGuidePhotos/19.png)

![Требования по контролю](../media/UserGuidePhotos/20.png)
 
<span data-ttu-id="f406b-183">При нажатии кнопки Отправка будет рассмотрена первоначальная отправка документа.</span><span class="sxs-lookup"><span data-stu-id="f406b-183">On clicking Submit, the initial document submission will be under review.</span></span>

![Отправка в стадии рассмотрения](../media/UserGuidePhotos/21.png)
  
<span data-ttu-id="f406b-185">Аналитик запрашивает пересмотр в случае, если документы, необходимые для управления, не являются достаточными или релевантны.</span><span class="sxs-lookup"><span data-stu-id="f406b-185">An analyst requests a revision in case the control requirement documents are not sufficient or relevant.</span></span> <span data-ttu-id="f406b-186">Аналитик будет работать с партнером, чтобы помочь получить нужные документы для утверждения.</span><span class="sxs-lookup"><span data-stu-id="f406b-186">The analyst will work with the partner to help get the right documents for approval.</span></span>

![Необходимо обновить данные](../media/UserGuidePhotos/22.png)

![Какие элементы управления нуждаются в обновлении](../media/UserGuidePhotos/23.png)
  
![Обзор в процессе](../media/UserGuidePhotos/24.png) 
 
<span data-ttu-id="f406b-190">В случае, если отправка не удовлетворяет стандартам утверждения, аналитик отклоняет отправку.</span><span class="sxs-lookup"><span data-stu-id="f406b-190">In case the submission does not satisfy the approval standards, the analyst will reject the submission.</span></span>
  
<span data-ttu-id="f406b-191">Партнер может работать с аналитиком для предоставления соответствующих сведений и документов.</span><span class="sxs-lookup"><span data-stu-id="f406b-191">The partner can work with the analyst to provide the relevant information and documents.</span></span>

![Сертификация отклонена](../media/UserGuidePhotos/25.png)
  
<span data-ttu-id="f406b-193">После того как все стандарты безопасности будут выполнены, аналитик утвердит отправку и партнер будет Microsoft 365 сертифицирован.</span><span class="sxs-lookup"><span data-stu-id="f406b-193">Once all the security standards have been met, the analyst will approve the submission and the partner will be Microsoft 365 Certified.</span></span>

![Microsoft 365 Утверждена сертификация приложений](../media/UserGuidePhotos/26.png)
  
<span data-ttu-id="f406b-195">**Утверждение после сертификации: пример Microsoft 365 сертификата в AppSource.**</span><span class="sxs-lookup"><span data-stu-id="f406b-195">**Post Certification Approval: Example of Microsoft 365 certification badge in AppSource.**</span></span> 

![Утверждение сертификации после публикации](../media/UserGuidePhotos/27.png)
 
## <a name="5---microsoft-365-renewal-workflow"></a><span data-ttu-id="f406b-197">5. Microsoft 365 обновления рабочего процесса:</span><span class="sxs-lookup"><span data-stu-id="f406b-197">5.   Microsoft 365 Renewal Workflow:</span></span>
  
<span data-ttu-id="f406b-198">**Microsoft 365Publisher процесса аттестации и обновления сертификации:**</span><span class="sxs-lookup"><span data-stu-id="f406b-198">**Microsoft 365 Publisher Attestation and Certification Renewal Workflow:**</span></span>  

<span data-ttu-id="f406b-199">Microsoft 365 Программа соответствия требованиям приложений теперь предлагает ежегодный процесс обновления.</span><span class="sxs-lookup"><span data-stu-id="f406b-199">Microsoft 365 App Compliance program now offers an annual renewal process.</span></span> <span data-ttu-id="f406b-200">В ходе этого процесса разработчики приложений могут обновить существующий Publisher аттестации и документы, необходимые для Microsoft 365 сертификации.</span><span class="sxs-lookup"><span data-stu-id="f406b-200">During this process, app developers can update their existing Publisher Attestation questionnaire and documents required for Microsoft 365 Certification.</span></span> 
 
<span data-ttu-id="f406b-201">**Преимущества:**</span><span class="sxs-lookup"><span data-stu-id="f406b-201">**Benefits:**</span></span> 

- <span data-ttu-id="f406b-202">Сохраните значок сертификации в AppSource, Office Store, Teams Store и различных порталах администрирования, чтобы отличать ваше приложение от других.</span><span class="sxs-lookup"><span data-stu-id="f406b-202">Maintain your certification badge in AppSource, the Office Store, the Teams Store and various admin portals to differentiate your app from others.</span></span> 
- <span data-ttu-id="f406b-203">Повышение доверия клиентов к использованию сертифицированного приложения.</span><span class="sxs-lookup"><span data-stu-id="f406b-203">Increase customer confidence in using your certified app.</span></span> 
- <span data-ttu-id="f406b-204">Помощь ИТ-администраторам в принятии обоснованных решений с помощью обновленных сведений о сертификации.</span><span class="sxs-lookup"><span data-stu-id="f406b-204">Help IT admins make informed decisions with updated certification information.</span></span>

<span data-ttu-id="f406b-205">Новый процесс обновления доступен в [Центре партнеров для](https://partner.microsoft.com/dashboard/home) обеспечения бесперебойного работы.</span><span class="sxs-lookup"><span data-stu-id="f406b-205">The new renewal process is available in [Partner Center](https://partner.microsoft.com/dashboard/home) to provide a seamless experience.</span></span> <span data-ttu-id="f406b-206">Напоминание о возобновлении будет показано в Центре партнеров, начиная с 90 дней до истечения срока действия.</span><span class="sxs-lookup"><span data-stu-id="f406b-206">A renewal reminder will be shown in Partner Center starting 90 days before the expiration date.</span></span> <span data-ttu-id="f406b-207">Периодические напоминания также будут отправляться по электронной почте за 90, 60 и 30 дней до истечения срока действия.</span><span class="sxs-lookup"><span data-stu-id="f406b-207">Periodic reminders will also be sent via email at 90, 60 and 30 days before expiration.</span></span> 
 
<span data-ttu-id="f406b-208">**Этап 1. Publisher проверки:**</span><span class="sxs-lookup"><span data-stu-id="f406b-208">**Phase 1: Publisher Attestation Renewal:**</span></span>
  
<span data-ttu-id="f406b-209">Ответы на Publisher проверки приложения необходимо будет повторно повторно переподавлить на ежегодной основе.</span><span class="sxs-lookup"><span data-stu-id="f406b-209">The app’s Publisher Attestation answers will need to be resubmitted on an annual basis.</span></span> <span data-ttu-id="f406b-210">Когда заверение близит к 1-летней отметке, будет отправлено напоминание по электронной почте, поощряющее повторное повторное тестирование.</span><span class="sxs-lookup"><span data-stu-id="f406b-210">When the attestation nears the 1-year mark, an email reminder will be sent encouraging a resubmission of the attestation.</span></span> 
 
<span data-ttu-id="f406b-211">**Шаг 1.** **Выберите обновление** для обновления Publisher проверки.</span><span class="sxs-lookup"><span data-stu-id="f406b-211">**Step 1**: Select **Renew** to renew the Publisher Attestation.</span></span>
  
![Renewel approved](../media/UserGuidePhotos/31.png)
  
<span data-ttu-id="f406b-213">**Шаг 2.** Просмотрите предыдущие ответы Publisher проверки и обновив при необходимости последнюю информацию.</span><span class="sxs-lookup"><span data-stu-id="f406b-213">**Step 2**: Review the previous Publisher Attestation answers and update with the latest information as needed.</span></span> 
  
<span data-ttu-id="f406b-214">Отправка Publisher для обновления при готовности.</span><span class="sxs-lookup"><span data-stu-id="f406b-214">Submit Publisher Attestation for renewal when ready.</span></span> <span data-ttu-id="f406b-215">Он будет рассмотрен аналитиком соответствия требованиям приложений M365.</span><span class="sxs-lookup"><span data-stu-id="f406b-215">It will be reviewed by an M365 App Compliance analyst.</span></span>

![Обновление до проверки](../media/UserGuidePhotos/29.png)
  
<span data-ttu-id="f406b-217">**Publisher Продление проверки утверждено:**</span><span class="sxs-lookup"><span data-stu-id="f406b-217">**Publisher Attestation Renewal Approved:**</span></span>
  
![Отправка для обновления](../media/UserGuidePhotos/30.png)
  
<span data-ttu-id="f406b-219">**Publisher Истек срок проверки:**</span><span class="sxs-lookup"><span data-stu-id="f406b-219">**Publisher Attestation Expired:**</span></span>
  
<span data-ttu-id="f406b-220">Сведения о приложении должны быть обновлены до истечения срока действия, чтобы сохранить страницу Publisher проверки в документы Майкрософт. Вовремяе обновление также обеспечит продолжение работы и значки для приложения в различных витринах.</span><span class="sxs-lookup"><span data-stu-id="f406b-220">The app’s information needs to be renewed before the expiration date to maintain the app’s Publisher Attestation page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in various storefronts.</span></span> 
 
![Renewel approved](../media/UserGuidePhotos/31.png)

<span data-ttu-id="f406b-222">**Примечание.** По истечении срока действия Publisher проверки можно начать в любое время, нажав кнопку "Обновить".</span><span class="sxs-lookup"><span data-stu-id="f406b-222">**Note**: Once expired, Publisher Attestation renewal process can be started anytime by clicking ‘Renew’.</span></span>
 
<span data-ttu-id="f406b-223">**Этап 2: Microsoft 365 сертификации**</span><span class="sxs-lookup"><span data-stu-id="f406b-223">**Phase 2: Microsoft 365 Certification Renewal**</span></span>
  
<span data-ttu-id="f406b-224">Сведения о сертификации приложения должны быть повторно перенаблюированы на ежегодной основе.</span><span class="sxs-lookup"><span data-stu-id="f406b-224">The app’s certification information needs to be resubmitted on an annual basis.</span></span> <span data-ttu-id="f406b-225">Для этого потребуется переоценка элементов управления в области текущей среды.</span><span class="sxs-lookup"><span data-stu-id="f406b-225">This will require revalidation of the in-scope controls of your current environment.</span></span> <span data-ttu-id="f406b-226">Когда сертификация близит к 1-летней отметке, будет отправлено уведомление по электронной почте с призывом к повторной отправке документов и доказательств.</span><span class="sxs-lookup"><span data-stu-id="f406b-226">When the Certification nears 1-year mark an email notification will be sent encouraging a resubmission of the documents and evidence.</span></span>
 
![Обновление attestation](../media/UserGuidePhotos/32.png) 

<span data-ttu-id="f406b-228">**Сценарии утверждения и отказа от сертификации:**</span><span class="sxs-lookup"><span data-stu-id="f406b-228">**Certification Renewal Approve/Reject Scenarios:**</span></span>

<span data-ttu-id="f406b-229">**Сценарий 1.**</span><span class="sxs-lookup"><span data-stu-id="f406b-229">**Scenario 1:**</span></span> 

<span data-ttu-id="f406b-230">Обновление сертификации началось и находится на рассмотрении.</span><span class="sxs-lookup"><span data-stu-id="f406b-230">Certification renewal has started and is under review.</span></span>
 
![Обновление сертификации](../media/UserGuidePhotos/33.png) 

<span data-ttu-id="f406b-232">Сценарий 1A:</span><span class="sxs-lookup"><span data-stu-id="f406b-232">Scenario 1A:</span></span> 

<span data-ttu-id="f406b-233">Отказ от продления сертификации:</span><span class="sxs-lookup"><span data-stu-id="f406b-233">Certification renewal rejection:</span></span> 
- <span data-ttu-id="f406b-234">Сертификация может быть отклонена, если:</span><span class="sxs-lookup"><span data-stu-id="f406b-234">Certification may be rejected if:</span></span> 
     - <span data-ttu-id="f406b-235">Приложение не имеет необходимых инструментов, процессов или конфигураций на месте и не сможет реализовать необходимые изменения в окне сертификации.</span><span class="sxs-lookup"><span data-stu-id="f406b-235">The app does not have the required tooling, processes, or configurations in place and will not be able to implement required changes within the certification window.</span></span> 
     - <span data-ttu-id="f406b-236">Приложение имеет непогашенные уязвимости и не может быть исправлено в окне сертификации.</span><span class="sxs-lookup"><span data-stu-id="f406b-236">The app has outstanding vulnerabilities in place and cannot be fixed within the certification window.</span></span> 
 
![Отказ от сертификации](../media/UserGuidePhotos/34.png)

<span data-ttu-id="f406b-238">Сценарий 1B:</span><span class="sxs-lookup"><span data-stu-id="f406b-238">Scenario 1B:</span></span> 

<span data-ttu-id="f406b-239">Утверждено продление сертификации</span><span class="sxs-lookup"><span data-stu-id="f406b-239">Certification renewal is approved</span></span>

![Утверждение обновления сертификации](../media/UserGuidePhotos/35.png)

<span data-ttu-id="f406b-241">**Срок действия сертификации:**</span><span class="sxs-lookup"><span data-stu-id="f406b-241">**Certification Expiration:**</span></span>

<span data-ttu-id="f406b-242">Сведения о приложении необходимо обновлять до истечения срока действия, чтобы сохранить страницу сертификации приложения в документы Майкрософт. Вовремяе обновление также обеспечит продолжение работы и значки для приложения в AppSource и Team Store.</span><span class="sxs-lookup"><span data-stu-id="f406b-242">The app’s information needs to be renewed before the expiration date to maintain app’s Certification page on the Microsoft docs. Timely renewal will also ensure continued badging and icons for the app in AppSource and Team Store.</span></span>

![Утверждение обновления сертификации](../media/UserGuidePhotos/36.png)
  
<span data-ttu-id="f406b-244">Примечание. По истечении срока действия Publisher аттестации и сертификации можно начать в любое время, нажав кнопку "Обновить".</span><span class="sxs-lookup"><span data-stu-id="f406b-244">Note: Once expired, Publisher Attestation and Certification process can be started anytime by clicking ‘Renew’.</span></span> 
