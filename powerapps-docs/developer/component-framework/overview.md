---
title: "PowerApps component framework overview | Microsoft Docs"
description: "Use the PowerApps component framework to create code components to provide enhanced experience for people to view and work with data in forms, views, and dashboards."
keywords: "Component Framework, code components, PowerApps controls"
author: nkrb 
manager: kvivek
ms.date: 09/05/2019
ms.service: "powerapps"
ms.custom:
  - "dyn365-a11y"
  - "dyn365-developer"
ms.topic: article
ms.assetid: 7923e36d-3640-49f7-9f2f-c97358a632db
ms.author: nabuthuk
---

# PowerApps component framework overview

[!INCLUDE[cc-beta-prerelease-disclaimer](../../includes/cc-beta-prerelease-disclaimer.md)]

Use PowerApps component framework to create code components in model-driven apps and canvas apps (experimental preview) to provide an enhanced user experience for the users to view and work with data in forms, views and dashboards. For example:

- Replace a field that displays a numeric text value with a `dial` or `slider` component.
- Transform a list into an entirely different visual experience bound to the data set like a `Calendar` or `Map`.
 
> [!IMPORTANT]
> - PowerApps component framework is in public preview for model driven apps, and in experimental preview for canvas apps. This implies that all the APIs that are supported for model driven apps might not be supported on canvas apps yet.
> - By default PowerApps component framework is enabled for model-driven apps. To enable this feature for canvas apps, see [Availability for canvas apps](component-framework-for-canvas-apps.md)
> - [!INCLUDE[cc_preview_features_definition](../../includes/cc-preview-features-definition.md)]
> - Canvas apps only support the *field* type of code components, and not the *data-set* type.


PowerApps component framework enables professional developers  and ap makers to create code components that can be used across the full breadth of PowerApps capabilities. code components have access to a rich set of framework APIs which expose capabilities like component lifecycle management, contextual data and metadata access, seamless server access via Web API, utility and data formatting methods, device features like camera, location and microphone along with easy to invoke UX elements like dialogs, lookups, full page rendering etc.  

Developers and app makers can utilize the modern web practices and also harness the power of external libraries to create advanced user interactions. The framework automatically handles the component lifecycle, retains application business logic and optimizes for performance (no more async IFrames). Components created using the PowerApps component framework are fully configurable and can be reused on multiple surfaces in model-driven apps like forms, dashboards, grids, etc and on canvas apps. Component definition, dependencies, and configurations can all be packaged into a [solution](https://docs.microsoft.com/dynamics365/customer-engagement/customize/solutions-overview) and moved across environments and can be shipped via [app source](https://appsource.microsoft.com/en-us/marketplace/apps?page=1&product=dynamics-365).  

## Related topics

[What are code components](custom-controls-overview.md)<br/>
[Availability for canvas apps](component-framework-for-canvas-apps.md)<br/>
[Create and deploy code components](create-custom-controls-using-pcf.md)<br/>
[PowerApps for developers](https://docs.microsoft.com/powerapps/#pivot=home&panel=developer)

