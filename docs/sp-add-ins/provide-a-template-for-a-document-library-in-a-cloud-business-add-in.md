---
title: Provide a template for a document library in a cloud business add-in
description: Add a template for a SharePoint document library.
ms.date: 11/07/2017
ms.prod: sharepoint
---

# Provide a template for a document library in a cloud business add-in

In addition to the Office templates that are available when you add a document to a SharePoint document library, you can provide your own templates. For example, you might have your own sales quote template that you want to use when new orders are added.

If you haven't already done so, associate a document library with your cloud business add-in by following the instructions at [Associate a document library with an entity](associate-a-document-library-with-an-entity.md).

## To add a template

1. Go to your SharePoint developer site, and on the **Developer** page, select **Site Contents**.

2. On the **Site Contents** page, select **SETTINGS**, as shown in Figure 1.
    
   *Figure 1. The SETTINGS link*

   ![Site Settings link](../images/CBA_IM_8b.PNG)

3. On the **Site Settings** page, in the **Web Designer Galleries** list, select **Site content types**, as shown in Figure 2.
    
   *Figure 2. The Site content types link*

   ![Site content types link](../images/CBA_IM_26.PNG)
 
4. On the **Site Content Types** page, select **Create**, as shown in Figure 3.
    
   *Figure 3. The Create link*

   ![Create link](../images/CBA_IM_27.PNG)
 
5. On the **New Site Content Type** page, enter a name and description for your template. For the **Parent Content Type**, select **Document Content Types** and **Document**, as shown in Figure 4.
    
   *Figure 4. Parent Content Type selections*

   ![Parent Content Type selections](../images/CBA_IM_28.PNG)

6. In the **Group** section, in the **Existing group** list, select **Document Content Types**, as shown in Figure 5, and then select **OK**.
    
   *Figure 5. Group setting*

   ![Group setting](../images/CBA_IM_28a.PNG)

7. On the **Site Content Type** page, select **Advanced settings**.

8. On the **Advanced Settings** page, either enter the URL of an existing document template or upload a new document template, as shown in Figure 6, and then select **OK**.
    
   *Figure 6. Specify the document template*

   ![Specify the document template](../images/CBA_IM_29.PNG)

9. Go to the **Site Contents** page, select your document library, and then go to the **Settings** page.

10. On the **Settings** page, select **Add from existing site content types**.

11. On the **Add Content Types** page, add your template, as shown in Figure 7, and then select **OK**.
    
   *Figure 7. Adding the template*

   ![Adding the template](../images/CBA_IM_29a.PNG)

12. Run your add-in and add a document. You should see your template in the **Create a new file** dialog box, as shown in Figure 8.
    
   *Figure 8. The Create a new file dialog box with the new template*

   ![The Create a new file dialog with the new template](../images/CBA_IM_30.PNG)


## Additional resources
<a name="bk_addresources"> </a>

- [Develop cloud business add-ins](develop-cloud-business-add-ins.md)
- [Associate a document library with an entity](associate-a-document-library-with-an-entity.md)
    
 

