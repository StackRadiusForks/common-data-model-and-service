---
title: MCRContinuityCustomerPaymentEntity - Common Data Model | Microsoft Docs
description: undefined
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 5/5/2020
ms.author: nebanfic
---

# Customer payments

  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/operationsCommon/Entities/Finance/AccountsReceivable/MCRContinuityCustomerPaymentEntity.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.0.0"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.application.releaseVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>releaseVersion</td><td>"10.0.13.0"</td><td>string</td><td>semantic version number of the application introducing this entity</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Customer payments</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[Amount](#Amount)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[IsCheckAuthorized](#IsCheckAuthorized)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[CheckNumber](#CheckNumber)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[CurrencyCode](#CurrencyCode)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[CustomerAccount](#CustomerAccount)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[CustomerPaymentType](#CustomerPaymentType)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[IsPlanRefund](#IsPlanRefund)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[IsPrepay](#IsPrepay)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[AuthorizationRetryNumber](#AuthorizationRetryNumber)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[IsOnAccountAuthorized](#IsOnAccountAuthorized)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[PaymentSchedId](#PaymentSchedId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[PercentAmount](#PercentAmount)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[PostedAmount](#PostedAmount)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[UniqueCreditCardId](#UniqueCreditCardId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[IsCreditCardProcessed](#IsCreditCardProcessed)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[RetailGiftCardId](#RetailGiftCardId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[Status](#Status)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[RetailStoreCardTypeId](#RetailStoreCardTypeId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[RetailStoreTenderTypeId](#RetailStoreTenderTypeId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[RetailChannelId](#RetailChannelId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[ContinuityInventoryTransactionId](#ContinuityInventoryTransactionId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[ContinuityScheduleId](#ContinuityScheduleId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[LineNumber](#LineNumber)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|
|[Relationship_PrimaryCompanyContextRelationshipId](#Relationship_PrimaryCompanyContextRelationshipId)||<a href="MCRContinuityCustomerPaymentEntity.md" target="_blank">AccountsReceivable/MCRContinuityCustomerPaymentEntity</a>|

### <a href=#Amount name="Amount">Amount</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Amount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCheckAuthorized name="IsCheckAuthorized">IsCheckAuthorized</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCheckAuthorized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CheckNumber name="CheckNumber">CheckNumber</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CheckNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CurrencyCode name="CurrencyCode">CurrencyCode</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CurrencyCode attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerAccount name="CustomerAccount">CustomerAccount</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerAccount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#CustomerPaymentType name="CustomerPaymentType">CustomerPaymentType</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the CustomerPaymentType attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPlanRefund name="IsPlanRefund">IsPlanRefund</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPlanRefund attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsPrepay name="IsPrepay">IsPrepay</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsPrepay attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#AuthorizationRetryNumber name="AuthorizationRetryNumber">AuthorizationRetryNumber</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the AuthorizationRetryNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsOnAccountAuthorized name="IsOnAccountAuthorized">IsOnAccountAuthorized</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsOnAccountAuthorized attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PaymentSchedId name="PaymentSchedId">PaymentSchedId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PaymentSchedId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PercentAmount name="PercentAmount">PercentAmount</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PercentAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#PostedAmount name="PostedAmount">PostedAmount</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the PostedAmount attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#UniqueCreditCardId name="UniqueCreditCardId">UniqueCreditCardId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UniqueCreditCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#IsCreditCardProcessed name="IsCreditCardProcessed">IsCreditCardProcessed</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the IsCreditCardProcessed attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailGiftCardId name="RetailGiftCardId">RetailGiftCardId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailGiftCardId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Status name="Status">Status</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Status attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStoreCardTypeId name="RetailStoreCardTypeId">RetailStoreCardTypeId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStoreCardTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailStoreTenderTypeId name="RetailStoreTenderTypeId">RetailStoreTenderTypeId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailStoreTenderTypeId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#RetailChannelId name="RetailChannelId">RetailChannelId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the RetailChannelId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContinuityInventoryTransactionId name="ContinuityInventoryTransactionId">ContinuityInventoryTransactionId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityInventoryTransactionId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#ContinuityScheduleId name="ContinuityScheduleId">ContinuityScheduleId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ContinuityScheduleId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#LineNumber name="LineNumber">LineNumber</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>isNullable</td><td>true</td></tr></table>

#### Traits

<details>
<summary>List of traits for the LineNumber attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.nullable**  
The attribute value may be set to NULL.  

**is.dataFormat.character**  
**is.dataFormat.array**  
</details>

### <a href=#Relationship_PrimaryCompanyContextRelationshipId name="Relationship_PrimaryCompanyContextRelationshipId">Relationship_PrimaryCompanyContextRelationshipId</a>

First included in: AccountsReceivable/MCRContinuityCustomerPaymentEntity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>guid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the Relationship_PrimaryCompanyContextRelationshipId attribute are listed below.</summary>

**is.dataFormat.character**  
**is.dataFormat.big**  
**is.dataFormat.array**  
**is.dataFormat.guid**  
**means.identity.entityId**  
**is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>entityReferences</td><td><table><tr><th>entityReference</th><th>attributeReference</th></tr><tr><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md" target="_blank">/core/operationsCommon/Tables/Finance/Ledger/Main/CompanyInfo.cdm.json/CompanyInfo</a></td><td><a href="../../../Tables/Finance/Ledger/Main/CompanyInfo.md#RecId" target="_blank">RecId</a></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of entity references</td></tr></table>

**is.dataFormat.guid**  
**is.dataFormat.character**  
**is.dataFormat.array**  
</details>