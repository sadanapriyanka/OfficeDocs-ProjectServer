---
title: "What's deprecated or removed in Project Server 2016"
ms.author: efrene
author: efrene
ms.prod: scotv
ms.date: 12/20/2016
ms.audience: ITPro
ms.topic: overview
ms.prod: project-server-2016
localization_priority: Normal
ms.collection:
- IT_ProjectAdmin
- IT_ProjectAdmin_Top
ms.assetid: 04fee973-5623-4768-a3ba-c109e45dd7eb
description: "Learn what has been deprecated or removed in Project Server 2016."
---
**Applies to:** Project Server 2016

# What's deprecated or removed in Project Server 2016
Learn what has been deprecated or removed in Project Server 2016.
  
This article describes features and functionality that have been removed in Project Server 2016 that had been previously available in Project Server 2013.
  
- [Resource Plans](what-s-deprecated-or-removed-in-project-server-2016.md#RePlan)
    
- [My Tasks](what-s-deprecated-or-removed-in-project-server-2016.md#MyTasks)
    
- [Project Server Interface (PSI) Project class removed](what-s-deprecated-or-removed-in-project-server-2016.md#ProjectClass)
    
- [Project Server Interface (PSI) members](what-s-deprecated-or-removed-in-project-server-2016.md#PSImem)
    
- [Project Server Interface (PSI) extensions](what-s-deprecated-or-removed-in-project-server-2016.md#PSIext)
    
## Resource Plans
<a name="RePlan"> </a>

In Project Server 2016, what was previously known as Resource Plans in Project Server 2013 has now evolved into Resource Engagements. Resource Engagements will allow project managers working in Project Professional 2016 or the Project Online Desktop Client to systematically place resource requests in order to build their project teams. Resource managers working in Project Server 2016 will then be able to modify, accept or reject those requests. 
  
Existing Resource Plans can be converted to Resource Engagements when you upgrade from Project Server 2013 to Project Server 2016 as an optional part of the upgrade process. The Resource Plan view will no longer be available in Project Professional 2016.
  
> [!NOTE]
> For more information about Resource Engagements, see this [blog post](http://go.microsoft.com/fwlink/?LinkID=620823&amp;clcid=0x409). For more information about migrating your Project Server 2013 Resource Plans to Resource Engagements as part of the Project Server 2016 upgrade process, see [Upgrading to Project Server 2016](upgrading-to-project-server-2016.md). 
  
## My Tasks
<a name="MyTasks"> </a>

The My Tasks and associated Exchange Task Sync features have been removed in SharePoint Server 2016. The Work Management Service Application that is required for both features has also been removed.
  
## Project Server Interface (PSI) Project class removed
<a name="ProjectClass"> </a>

The Project class in the PSI is not supported in Project Server 2016. For all new development, use the [Project Client Side Object Model (CSOM)](http://go.microsoft.com/fwlink/p/?LinkId=798162&amp;clcid=0x409).
  
|||
|:-----|:-----|
|**WebSvcProject** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|Project  <br/> |All  <br/> |
|ProjectContextDataSet  <br/> |All  <br/> |
|ProjectDataSet  <br/> |All  <br/> |
|ProjectImpactDataSet  <br/> |All  <br/> |
|ProjectRelationsDataSet  <br/> |All  <br/> |
|ProjectTeamDataSet  <br/> |All  <br/> |
|SyncDataSet  <br/> |All  <br/> |
|SyncErrorsDataSet  <br/> |All  <br/> |
   
## Project Server Interface (PSI) members
<a name="PSImem"> </a>

In Project Server 2016, the following PSI members have been removed: 
  
> [!NOTE]
> For more information about the Project Server Interface, see [Project Server 2013 class library and web service reference](https://go.microsoft.com/fwlink/p/?LinkId=623030)
  
|||
|:-----|:-----|
|**Microsoft.Office.Project.Server.Library** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|Activity  <br/> |PROPOSAL_REVIEW_APPROVAL_FEATURE_UID  <br/> PROPOSAL_REVIEW_WORKFLOW_FEATURE_UID  <br/> |
|CubeStatus.CbsProcessErrorId  <br/> |DsoTranslatorNotFound  <br/> DsoNotInstalled  <br/> |
|IPSContextInfo  <br/> |Lcid  <br/> |
|PSContextInfo  <br/> |PSContextInfo(Boolean, String, Guid, Guid, Guid, String)  <br/> PSContextInfo(Boolean, String, Guid, Guid, Guid, Int32, String)  <br/> Lcid  <br/> SiteVersion  <br/> |
|PSErrorID  <br/> |LookupTableItemHasTrailingOrLeadingWhitespace  <br/> |
|PSEventID  <br/> |Deprecated8  <br/> Deprecated9  <br/> |
|PSDBUtility  <br/> |IntArrayListToCommaDelimitedString  <br/> |
|PSSecurityCategory  <br/> |MyPersonaIProjects  <br/> |
|PSSecurityGIobaIPermission  <br/> |ChangeProjectState  <br/> CreateNewProposalOrActivity  <br/> DownloadPwaOutlookAddIn  <br/> ManageStatusReports  <br/> ViewDataAnalysis  <br/> |
|PSSecurityObjectType  <br/> |MaxBuildInObjectType  <br/> Model  <br/> |
|Security  <br/> |PROPOSAL_APPROVERS_GROUP_UID  <br/> |
|ViewConstants.ViewType  <br/> |VISION  <br/> |
   
|||
|:-----|:-----|
|**Microsoft.Office.Project.Server.WebServiceProxy** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|LoginWindows  <br/> |<all>  <br/> |
   
|||
|:-----|:-----|
|**Microsoft.Office.Project.Server.Workflow** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|WorkflowStringIds  <br/> |SEND_EMAIL_PROJECT_COMPLETED_BODY  <br/> STATUS_INITIALIZE_FAILED_INVALID_PROJECT  <br/> |
   
|||
|:-----|:-----|
|**WebSvcCubeAdmin** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|CubeAdmin  <br/> |SetCubeBuiIdingSettings  <br/> |
   
|||
|:-----|:-----|
|**WebSvcEvents** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|PSEventID  <br/> |Deprecated8  <br/> Deprecated9  <br/> |
   
|||
|:-----|:-----|
|**WebSvcPortfolioAnalyses** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|AnalysisDataSet.AnalysisProjectsDataTable  <br/> |AddAnalysisProjectsRow (AnalysisDataSet.AnalysisRow, Guid, String, Double, Double, DateTime, DateTime, DateTime, Int32, DateTime, DateTime, Byte)  <br/> |
|AnalysisDataSet.AnalysisProjectsRow  <br/> |FNLT  <br/> SNET  <br/> |
   
|||
|:-----|:-----|
|**WebSvcStatusing** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|ProjectDataSet.TaskRow  <br/> |DurationType  <br/> PROJ_OPT_CURRENCY_DIGITS  <br/> PROJ_OPT_CURRENCY_POSITION  <br/> PROJ_OPT_CURRENCY_SYMBOL  <br/> |
   
|||
|:-----|:-----|
|**WebSvcTimeSheet** <br/> | |
| *Type*  <br/> | *Removed members*  <br/> |
|TimesheetListDataSet.TimesheetsRow  <br/> |TS_AUX_STATUS  <br/> |
   
## Project Server Interface (PSI) extensions
<a name="PSIext"> </a>

In Project Server 2016, Project Server Interface (PSI) extension scenarios are not supported. These scenarios enabled integration with custom Windows Communication Foundation (WCF) services. 
  
> [!NOTE]
> For more information about PSI extensions, see the MSDN article [Developing PSI Extensions](https://go.microsoft.com/fwlink/p/?LinkId=623772). 
  
## See also
<a name="PSIext"> </a>

#### 

[What's new for IT pros in Project Server 2016](what-s-new-for-it-pros-in-project-server-2016.md)

[What's deprecated or removed from SharePoint Server 2016 IT Preview](http://technet.microsoft.com/library/5af9ee8b-39b8-489b-bcb9-64099618db51.aspx)
  
[New and improved features in SharePoint Server 2016 IT Preview](http://technet.microsoft.com/library/e81557fb-5046-4a67-8ec8-fdfda648af68.aspx)
