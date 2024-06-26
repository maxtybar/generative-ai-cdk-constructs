[@cdklabs/generative-ai-cdk-constructs](../README.md) / [amazonaurora](../modules/amazonaurora.md) / AmazonAuroraVectorStoreProps

# Interface: AmazonAuroraVectorStoreProps

[amazonaurora](../modules/amazonaurora.md).AmazonAuroraVectorStoreProps

Properties for configuring an Amazon Aurora Vector Store.

## Hierarchy

- [`BaseAuroraVectorStoreProps`](amazonaurora.BaseAuroraVectorStoreProps.md)

  ↳ **`AmazonAuroraVectorStoreProps`**

## Table of contents

### Properties

- [databaseName](amazonaurora.AmazonAuroraVectorStoreProps.md#databasename)
- [embeddingsModel](amazonaurora.AmazonAuroraVectorStoreProps.md#embeddingsmodel)
- [metadataField](amazonaurora.AmazonAuroraVectorStoreProps.md#metadatafield)
- [postgreSQLVersion](amazonaurora.AmazonAuroraVectorStoreProps.md#postgresqlversion)
- [primaryKeyField](amazonaurora.AmazonAuroraVectorStoreProps.md#primarykeyfield)
- [schemaName](amazonaurora.AmazonAuroraVectorStoreProps.md#schemaname)
- [tableName](amazonaurora.AmazonAuroraVectorStoreProps.md#tablename)
- [textField](amazonaurora.AmazonAuroraVectorStoreProps.md#textfield)
- [vectorField](amazonaurora.AmazonAuroraVectorStoreProps.md#vectorfield)

## Properties

### databaseName

• `Optional` `Readonly` **databaseName**: `string`

The name of the database for the Aurora Vector Store.

___

### embeddingsModel

• `Readonly` **embeddingsModel**: [`BedrockFoundationModel`](../classes/foundation_models.BedrockFoundationModel.md)

The embeddings model used for the Aurora Vector Store.
The vector dimensions of the model must match the dimensions
used in the KnowledgeBase construct.

#### Inherited from

[BaseAuroraVectorStoreProps](amazonaurora.BaseAuroraVectorStoreProps.md).[embeddingsModel](amazonaurora.BaseAuroraVectorStoreProps.md#embeddingsmodel)

___

### metadataField

• `Optional` `Readonly` **metadataField**: `string`

The field name for the metadata column in the Aurora Vector Store.

#### Inherited from

[BaseAuroraVectorStoreProps](amazonaurora.BaseAuroraVectorStoreProps.md).[metadataField](amazonaurora.BaseAuroraVectorStoreProps.md#metadatafield)

___

### postgreSQLVersion

• `Optional` `Readonly` **postgreSQLVersion**: `AuroraPostgresEngineVersion`

The version of PostgreSQL to use for the Aurora Vector Store.
By default, the latest supported version will be used.

___

### primaryKeyField

• `Optional` `Readonly` **primaryKeyField**: `string`

The primary key field for the Aurora Vector Store table.

#### Inherited from

[BaseAuroraVectorStoreProps](amazonaurora.BaseAuroraVectorStoreProps.md).[primaryKeyField](amazonaurora.BaseAuroraVectorStoreProps.md#primarykeyfield)

___

### schemaName

• `Optional` `Readonly` **schemaName**: `string`

The schema name for the Aurora Vector Store.

#### Inherited from

[BaseAuroraVectorStoreProps](amazonaurora.BaseAuroraVectorStoreProps.md).[schemaName](amazonaurora.BaseAuroraVectorStoreProps.md#schemaname)

___

### tableName

• `Optional` `Readonly` **tableName**: `string`

The name of the table for the Aurora Vector Store.

#### Inherited from

[BaseAuroraVectorStoreProps](amazonaurora.BaseAuroraVectorStoreProps.md).[tableName](amazonaurora.BaseAuroraVectorStoreProps.md#tablename)

___

### textField

• `Optional` `Readonly` **textField**: `string`

The field name for the text column in the Aurora Vector Store.

#### Inherited from

[BaseAuroraVectorStoreProps](amazonaurora.BaseAuroraVectorStoreProps.md).[textField](amazonaurora.BaseAuroraVectorStoreProps.md#textfield)

___

### vectorField

• `Optional` `Readonly` **vectorField**: `string`

The field name for the vector column in the Aurora Vector Store.

#### Inherited from

[BaseAuroraVectorStoreProps](amazonaurora.BaseAuroraVectorStoreProps.md).[vectorField](amazonaurora.BaseAuroraVectorStoreProps.md#vectorfield)
