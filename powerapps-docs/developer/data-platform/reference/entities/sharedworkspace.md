---
title: "Shared Workspace (sharedworkspace) table/entity reference (Microsoft Dataverse)"
description: "Includes schema information and supported messages for the Shared Workspace (sharedworkspace) table/entity with Microsoft Dataverse."
ms.date: 11/09/2024
ms.service: powerapps
ms.topic: reference
author: phecke
ms.author: pehecke
search.audienceType: 
  - developer
---

# Shared Workspace (sharedworkspace) table/entity reference

References a container that stores real-time collaboration data.

## Messages

The following table lists the messages for the Shared Workspace (sharedworkspace) table.
Messages represent operations that can be performed on the table. They may also be events.

| Name <br />Is Event? |Web API Operation |SDK for .NET |
| ---- | ----- |----- |
| `Create`<br />Event: True |`POST` /sharedworkspaces<br />See [Create](/powerapps/developer/data-platform/webapi/create-entity-web-api) |[Create records](/power-apps/developer/data-platform/org-service/entity-operations-create#basic-create)|
| `Delete`<br />Event: True |`DELETE` /sharedworkspaces(*sharedworkspaceid*)<br />See [Delete](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-delete) |[Delete records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-delete)|
| `Retrieve`<br />Event: True |`GET` /sharedworkspaces(*sharedworkspaceid*)<br />See [Retrieve](/powerapps/developer/data-platform/webapi/retrieve-entity-using-web-api) |[Retrieve records](/power-apps/developer/data-platform/org-service/entity-operations-retrieve)|
| `RetrieveMultiple`<br />Event: True |`GET` /sharedworkspaces<br />See [Query data](/power-apps/developer/data-platform/webapi/query-data-web-api) |[Query data](/power-apps/developer/data-platform/org-service/entity-operations-query-data)|
| `Update`<br />Event: True |`PATCH` /sharedworkspaces(*sharedworkspaceid*)<br />See [Update](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#basic-update) |[Update records](/power-apps/developer/data-platform/org-service/entity-operations-update-delete#basic-update)|
| `Upsert`<br />Event: False |`PATCH` /sharedworkspaces(*sharedworkspaceid*)<br />See [Upsert a table row](/powerapps/developer/data-platform/webapi/update-delete-entities-using-web-api#upsert-a-table-row) |<xref:Microsoft.Xrm.Sdk.Messages.UpsertRequest>|

## Properties

The following table lists selected properties for the Shared Workspace (sharedworkspace) table.

|Property|Value|
| --- | --- |
| **DisplayName** | **Shared Workspace** |
| **DisplayCollectionName** | **Shared Workspaces** |
| **SchemaName** | `sharedworkspace` |
| **CollectionSchemaName** | `sharedworkspaces` |
| **EntitySetName** | `sharedworkspaces`|
| **LogicalName** | `sharedworkspace` |
| **LogicalCollectionName** | `sharedworkspaces` |
| **PrimaryIdAttribute** | `sharedworkspaceid` |
| **PrimaryNameAttribute** |`name` |
| **TableType** | `Standard` |
| **OwnershipType** | `None` |

## Writable columns/attributes

These columns/attributes return true for either **IsValidForCreate** or **IsValidForUpdate** (usually both). Listed by **SchemaName**.

- [DiscoveryEndpoint](#BKMK_DiscoveryEndpoint)
- [ImportSequenceNumber](#BKMK_ImportSequenceNumber)
- [LastManaged](#BKMK_LastManaged)
- [LastUsed](#BKMK_LastUsed)
- [Name](#BKMK_Name)
- [OrdererEndpoint](#BKMK_OrdererEndpoint)
- [OverriddenCreatedOn](#BKMK_OverriddenCreatedOn)
- [sharedworkspaceId](#BKMK_sharedworkspaceId)
- [statecode](#BKMK_statecode)
- [statuscode](#BKMK_statuscode)
- [StorageEndpoint](#BKMK_StorageEndpoint)
- [TenantId](#BKMK_TenantId)
- [TimeZoneRuleVersionNumber](#BKMK_TimeZoneRuleVersionNumber)
- [UTCConversionTimeZoneCode](#BKMK_UTCConversionTimeZoneCode)
- [WorkspaceSchema](#BKMK_WorkspaceSchema)
- [WorkspaceSchemaVersion](#BKMK_WorkspaceSchemaVersion)

### <a name="BKMK_DiscoveryEndpoint"></a> DiscoveryEndpoint

|Property|Value|
|---|---|
|Description|**Discovery Endpoint**|
|DisplayName|**Discovery Endpoint**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`discoveryendpoint`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|256|

### <a name="BKMK_ImportSequenceNumber"></a> ImportSequenceNumber

|Property|Value|
|---|---|
|Description|**Sequence number of the import that created this record.**|
|DisplayName|**Import Sequence Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`importsequencenumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-2147483648|

### <a name="BKMK_LastManaged"></a> LastManaged

|Property|Value|
|---|---|
|Description|**The last time the workspace was managed.**|
|DisplayName|**Last Managed**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`lastmanaged`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_LastUsed"></a> LastUsed

|Property|Value|
|---|---|
|Description|**The last time the workspace was used**|
|DisplayName|**Last Used**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`lastused`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|TimeZoneIndependent|
|Format|DateAndTime|
|ImeMode|Auto|
|SourceTypeMask|0|

### <a name="BKMK_Name"></a> Name

|Property|Value|
|---|---|
|Description|**The name of the container.**|
|DisplayName|**Name**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`name`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|256|

### <a name="BKMK_OrdererEndpoint"></a> OrdererEndpoint

|Property|Value|
|---|---|
|Description|**Orderer Endpoint**|
|DisplayName|**Orderer Endpoint**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`ordererendpoint`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|256|

### <a name="BKMK_OverriddenCreatedOn"></a> OverriddenCreatedOn

|Property|Value|
|---|---|
|Description|**Date and time that the record was migrated.**|
|DisplayName|**Record Created On**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`overriddencreatedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateOnly|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_sharedworkspaceId"></a> sharedworkspaceId

|Property|Value|
|---|---|
|Description|**The documentId identifying the container**|
|DisplayName|**SharedWorkspaceId**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`sharedworkspaceid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_statecode"></a> statecode

|Property|Value|
|---|---|
|Description|**Status of the workspace**|
|DisplayName|**Status**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statecode`|
|RequiredLevel|SystemRequired|
|Type|State|
|DefaultFormValue||
|GlobalChoiceName|`sharedworkspace_statecode`|

#### statecode Choices/Options

|Value|Details|
|---|---|
|0|Label: **Active**<br />DefaultStatus: 1<br />InvariantName: `Active`|
|1|Label: **Inactive**<br />DefaultStatus: 2<br />InvariantName: `Inactive`|

### <a name="BKMK_statuscode"></a> statuscode

|Property|Value|
|---|---|
|Description|**Reason for the status of the workspace.**|
|DisplayName|**Status Reason**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`statuscode`|
|RequiredLevel|None|
|Type|Status|
|DefaultFormValue||
|GlobalChoiceName|`sharedworkspace_statuscode`|

#### statuscode Choices/Options

|Value|Details|
|---|---|
|1|Label: **Active**<br />State:0<br />TransitionData: None|
|2|Label: **Inactive**<br />State:1<br />TransitionData: None|

### <a name="BKMK_StorageEndpoint"></a> StorageEndpoint

|Property|Value|
|---|---|
|Description|**Storage Endpoint**|
|DisplayName|**Storage Endpoint**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`storageendpoint`|
|RequiredLevel|SystemRequired|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|256|

### <a name="BKMK_TenantId"></a> TenantId

|Property|Value|
|---|---|
|Description|**The tenant where the workspace resides**|
|DisplayName|**Tenant ID**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`tenantid`|
|RequiredLevel|SystemRequired|
|Type|Uniqueidentifier|

### <a name="BKMK_TimeZoneRuleVersionNumber"></a> TimeZoneRuleVersionNumber

|Property|Value|
|---|---|
|Description|**For internal use only.**|
|DisplayName|**Time Zone Rule Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`timezoneruleversionnumber`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|

### <a name="BKMK_UTCConversionTimeZoneCode"></a> UTCConversionTimeZoneCode

|Property|Value|
|---|---|
|Description|**Time zone code that was in use when the record was created.**|
|DisplayName|**UTC Conversion Time Zone Code**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`utcconversiontimezonecode`|
|RequiredLevel|None|
|Type|Integer|
|MaxValue|2147483647|
|MinValue|-1|

### <a name="BKMK_WorkspaceSchema"></a> WorkspaceSchema

|Property|Value|
|---|---|
|Description|**The schema of the workspace**|
|DisplayName|**Workspace Schema**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`workspaceschema`|
|RequiredLevel|None|
|Type|Memo|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|20000|

### <a name="BKMK_WorkspaceSchemaVersion"></a> WorkspaceSchemaVersion

|Property|Value|
|---|---|
|Description|**The version of the schema.**|
|DisplayName|**Workspace Schema Version**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`workspaceschemaversion`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|256|


## Read-only columns/attributes

These columns/attributes return false for both **IsValidForCreate** and **IsValidForUpdate**. Listed by **SchemaName**.

- [AccessToken](#BKMK_AccessToken)
- [CreatedBy](#BKMK_CreatedBy)
- [CreatedOn](#BKMK_CreatedOn)
- [CreatedOnBehalfBy](#BKMK_CreatedOnBehalfBy)
- [ModifiedBy](#BKMK_ModifiedBy)
- [ModifiedOn](#BKMK_ModifiedOn)
- [ModifiedOnBehalfBy](#BKMK_ModifiedOnBehalfBy)
- [VersionNumber](#BKMK_VersionNumber)

### <a name="BKMK_AccessToken"></a> AccessToken

|Property|Value|
|---|---|
|Description|**Access token**|
|DisplayName|**Access Token**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`accesstoken`|
|RequiredLevel|None|
|Type|String|
|Format|Text|
|FormatName|Text|
|ImeMode|Auto|
|IsLocalizable|False|
|MaxLength|256|

### <a name="BKMK_CreatedBy"></a> CreatedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who created the record.**|
|DisplayName|**Created By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_CreatedOn"></a> CreatedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was created.**|
|DisplayName|**Created On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_CreatedOnBehalfBy"></a> CreatedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who created the record.**|
|DisplayName|**Created By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`createdonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedBy"></a> ModifiedBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the user who modified the record.**|
|DisplayName|**Modified By**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_ModifiedOn"></a> ModifiedOn

|Property|Value|
|---|---|
|Description|**Date and time when the record was modified.**|
|DisplayName|**Modified On**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedon`|
|RequiredLevel|None|
|Type|DateTime|
|CanChangeDateTimeBehavior|False|
|DateTimeBehavior|UserLocal|
|Format|DateAndTime|
|ImeMode|Inactive|
|SourceTypeMask|0|

### <a name="BKMK_ModifiedOnBehalfBy"></a> ModifiedOnBehalfBy

|Property|Value|
|---|---|
|Description|**Unique identifier of the delegate user who modified the record.**|
|DisplayName|**Modified By (Delegate)**|
|IsValidForForm|True|
|IsValidForRead|True|
|LogicalName|`modifiedonbehalfby`|
|RequiredLevel|None|
|Type|Lookup|
|Targets|systemuser|

### <a name="BKMK_VersionNumber"></a> VersionNumber

|Property|Value|
|---|---|
|Description|**Version Number**|
|DisplayName|**Version Number**|
|IsValidForForm|False|
|IsValidForRead|True|
|LogicalName|`versionnumber`|
|RequiredLevel|None|
|Type|BigInt|
|MaxValue|9223372036854775807|
|MinValue|-9223372036854775808|

## Many-to-One relationships

These relationships are many-to-one. Listed by **SchemaName**.

- [lk_sharedworkspace_createdby](#BKMK_lk_sharedworkspace_createdby)
- [lk_sharedworkspace_createdonbehalfby](#BKMK_lk_sharedworkspace_createdonbehalfby)
- [lk_sharedworkspace_modifiedby](#BKMK_lk_sharedworkspace_modifiedby)
- [lk_sharedworkspace_modifiedonbehalfby](#BKMK_lk_sharedworkspace_modifiedonbehalfby)

### <a name="BKMK_lk_sharedworkspace_createdby"></a> lk_sharedworkspace_createdby

One-To-Many Relationship: [systemuser lk_sharedworkspace_createdby](systemuser.md#BKMK_lk_sharedworkspace_createdby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdby`|
|ReferencingEntityNavigationPropertyName|`createdby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_sharedworkspace_createdonbehalfby"></a> lk_sharedworkspace_createdonbehalfby

One-To-Many Relationship: [systemuser lk_sharedworkspace_createdonbehalfby](systemuser.md#BKMK_lk_sharedworkspace_createdonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`createdonbehalfby`|
|ReferencingEntityNavigationPropertyName|`createdonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_sharedworkspace_modifiedby"></a> lk_sharedworkspace_modifiedby

One-To-Many Relationship: [systemuser lk_sharedworkspace_modifiedby](systemuser.md#BKMK_lk_sharedworkspace_modifiedby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedby`|
|ReferencingEntityNavigationPropertyName|`modifiedby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|

### <a name="BKMK_lk_sharedworkspace_modifiedonbehalfby"></a> lk_sharedworkspace_modifiedonbehalfby

One-To-Many Relationship: [systemuser lk_sharedworkspace_modifiedonbehalfby](systemuser.md#BKMK_lk_sharedworkspace_modifiedonbehalfby)

|Property|Value|
|---|---|
|ReferencedEntity|`systemuser`|
|ReferencedAttribute|`systemuserid`|
|ReferencingAttribute|`modifiedonbehalfby`|
|ReferencingEntityNavigationPropertyName|`modifiedonbehalfby`|
|IsHierarchical||
|CascadeConfiguration|Archive: `NoCascade`<br />Assign: `NoCascade`<br />Delete: `NoCascade`<br />Merge: `NoCascade`<br />Reparent: `NoCascade`<br />RollupView: `NoCascade`<br />Share: `NoCascade`<br />Unshare: `NoCascade`|


## One-to-Many relationships

These relationships are one-to-many. Listed by **SchemaName**.

- [sharedworkspace_AsyncOperations](#BKMK_sharedworkspace_AsyncOperations)
- [sharedworkspace_BulkDeleteFailures](#BKMK_sharedworkspace_BulkDeleteFailures)
- [sharedworkspace_MailboxTrackingFolders](#BKMK_sharedworkspace_MailboxTrackingFolders)
- [sharedworkspace_PrincipalObjectAttributeAccesses](#BKMK_sharedworkspace_PrincipalObjectAttributeAccesses)
- [sharedworkspace_ProcessSession](#BKMK_sharedworkspace_ProcessSession)
- [sharedworkspace_sharedobject](#BKMK_sharedworkspace_sharedobject)
- [sharedworkspace_SyncErrors](#BKMK_sharedworkspace_SyncErrors)

### <a name="BKMK_sharedworkspace_AsyncOperations"></a> sharedworkspace_AsyncOperations

Many-To-One Relationship: [asyncoperation sharedworkspace_AsyncOperations](asyncoperation.md#BKMK_sharedworkspace_AsyncOperations)

|Property|Value|
|---|---|
|ReferencingEntity|`asyncoperation`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sharedworkspace_AsyncOperations`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sharedworkspace_BulkDeleteFailures"></a> sharedworkspace_BulkDeleteFailures

Many-To-One Relationship: [bulkdeletefailure sharedworkspace_BulkDeleteFailures](bulkdeletefailure.md#BKMK_sharedworkspace_BulkDeleteFailures)

|Property|Value|
|---|---|
|ReferencingEntity|`bulkdeletefailure`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sharedworkspace_BulkDeleteFailures`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sharedworkspace_MailboxTrackingFolders"></a> sharedworkspace_MailboxTrackingFolders

Many-To-One Relationship: [mailboxtrackingfolder sharedworkspace_MailboxTrackingFolders](mailboxtrackingfolder.md#BKMK_sharedworkspace_MailboxTrackingFolders)

|Property|Value|
|---|---|
|ReferencingEntity|`mailboxtrackingfolder`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sharedworkspace_MailboxTrackingFolders`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sharedworkspace_PrincipalObjectAttributeAccesses"></a> sharedworkspace_PrincipalObjectAttributeAccesses

Many-To-One Relationship: [principalobjectattributeaccess sharedworkspace_PrincipalObjectAttributeAccesses](principalobjectattributeaccess.md#BKMK_sharedworkspace_PrincipalObjectAttributeAccesses)

|Property|Value|
|---|---|
|ReferencingEntity|`principalobjectattributeaccess`|
|ReferencingAttribute|`objectid`|
|ReferencedEntityNavigationPropertyName|`sharedworkspace_PrincipalObjectAttributeAccesses`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sharedworkspace_ProcessSession"></a> sharedworkspace_ProcessSession

Many-To-One Relationship: [processsession sharedworkspace_ProcessSession](processsession.md#BKMK_sharedworkspace_ProcessSession)

|Property|Value|
|---|---|
|ReferencingEntity|`processsession`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sharedworkspace_ProcessSession`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sharedworkspace_sharedobject"></a> sharedworkspace_sharedobject

Many-To-One Relationship: [sharedobject sharedworkspace_sharedobject](sharedobject.md#BKMK_sharedworkspace_sharedobject)

|Property|Value|
|---|---|
|ReferencingEntity|`sharedobject`|
|ReferencingAttribute|`sharedworkspaceid`|
|ReferencedEntityNavigationPropertyName|`sharedworkspace_sharedobject`|
|IsCustomizable|`False`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `UseCollectionName`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: 10000<br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|

### <a name="BKMK_sharedworkspace_SyncErrors"></a> sharedworkspace_SyncErrors

Many-To-One Relationship: [syncerror sharedworkspace_SyncErrors](syncerror.md#BKMK_sharedworkspace_SyncErrors)

|Property|Value|
|---|---|
|ReferencingEntity|`syncerror`|
|ReferencingAttribute|`regardingobjectid`|
|ReferencedEntityNavigationPropertyName|`sharedworkspace_SyncErrors`|
|IsCustomizable|`True`|
|AssociatedMenuConfiguration|AvailableOffline: True<br />Behavior: `DoNotDisplay`<br />Group: `Details`<br />Label: <br />MenuId: null<br />Order: <br />QueryApi: null<br />ViewId: `00000000-0000-0000-0000-000000000000`|



### See also

[Dataverse table/entity reference](../about-entity-reference.md)  
[Dataverse Web API Reference](/power-apps/developer/data-platform/webapi/reference/about)   
<xref:Microsoft.Dynamics.CRM.sharedworkspace?displayProperty=fullName>
