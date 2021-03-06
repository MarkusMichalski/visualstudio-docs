---
title: "Customize Control Binding Dialog Box | Microsoft Docs"
ms.custom: ""
ms.date: "2018-06-30"
ms.prod: "visual-studio-dev14"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
f1_keywords: 
  - "vs.datasource.datauicustomization"
dev_langs: 
  - "VB"
  - "CSharp"
  - "C++"
  - "aspx"
helpviewer_keywords: 
  - "Customize Control Binding dialog box"
ms.assetid: abcc0be3-a18e-4f47-b354-d6b0c618e087
caps.latest.revision: 9
author: gewarren
ms.author: gewarren
manager: "ghogen"
robots: noindex,nofollow
---
# Customize Control Binding Dialog Box
[!INCLUDE[vs2017banner](../includes/vs2017banner.md)]

Use the **Customize Control Binding** dialog box to specify which controls are available for items in the [Data Sources Window](http://msdn.microsoft.com/library/0d20f699-cc95-45b3-8ecb-c7edf1f67992).  
  
 Each item in the **Data Sources** window has an associated list of controls that can be bound to the item. The controls available for each item are determined by the data type of the item. Each data type has a list of valid associated controls defined in this dialog box, including a default control.  
  
 Before you drag an item to a design surface to create a data-bound control, you can select which control to create. If you drag an item from the **Data Sources** window onto a design surface without selecting a control, the default control for the data type of the selected item is added to the design surface.  
  
 For more information about how to use this dialog box to customize the list of controls for items in the **Data Sources** window, see [Add custom controls to the Data Sources window](../data-tools/add-custom-controls-to-the-data-sources-window.md).  
  
## UIElement List  
 **Data type**  
 Displays a list of types that you associate with controls:  
  
-   Tables, entities, and objects are represented as **[List]** types.  
  
-   Columns or public properties of entities and objects are represented as the actual data type of the column or property in the underlying data store.  
  
-   Objects with user-defined shapes are represented as **[Other]**. For example, if your application has a custom control that displays data from more than one property of an object, select the **[Other]** data type for your control.  
  
 **Associated controls**  
 Displays a list of controls that you can associate with a particular data type. If you want to associate a particular control with the data type selected in the **Data Type** list, select the corresponding check box. Clear the check box to remove an association. Checked controls appear in the shortcut menu presented by the **Data Sources** window for an item of the associated data type.  
  
 You can add controls to the list by adding controls that have one of several data-binding attributes to the **Toolbox**. For more information, see [Add custom controls to the Data Sources window](../data-tools/add-custom-controls-to-the-data-sources-window.md).  
  
 **Set Default**  
 Assigns the selected control type to be the default for items of the selected data type. The default control appears as the first selection in the shortcut menu presented by the **Data Sources** window for an item. Only one control type can be assigned as the default for a data type.  
  
 **Clear Default**  
 Removes the designation of a control as the default for the selected data type. If there is no default for the selected data type, **[None]** appears as the first selection in the shortcut menu presented by the **Data Sources** window for an item of the associated type.  
  
## See Also  
 [Data Sources Window](http://msdn.microsoft.com/library/0d20f699-cc95-45b3-8ecb-c7edf1f67992)   
 [Add new data sources](../data-tools/add-new-data-sources.md)   
 [Bind Windows Forms controls to data in Visual Studio](../data-tools/bind-windows-forms-controls-to-data-in-visual-studio.md)   
 [Add custom controls to the Data Sources window](../data-tools/add-custom-controls-to-the-data-sources-window.md)   
 [Set the control to be created when dragging from the Data Sources window](../data-tools/set-the-control-to-be-created-when-dragging-from-the-data-sources-window.md)