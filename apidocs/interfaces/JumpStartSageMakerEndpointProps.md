[@cdklabs/generative-ai-cdk-constructs](../README.md) / JumpStartSageMakerEndpointProps

# Interface: JumpStartSageMakerEndpointProps

## Table of contents

### Properties

- [endpointName](JumpStartSageMakerEndpointProps.md#endpointname)
- [environment](JumpStartSageMakerEndpointProps.md#environment)
- [instanceCount](JumpStartSageMakerEndpointProps.md#instancecount)
- [instanceType](JumpStartSageMakerEndpointProps.md#instancetype)
- [model](JumpStartSageMakerEndpointProps.md#model)
- [role](JumpStartSageMakerEndpointProps.md#role)
- [startupHealthCheckTimeoutInSeconds](JumpStartSageMakerEndpointProps.md#startuphealthchecktimeoutinseconds)
- [vpcConfig](JumpStartSageMakerEndpointProps.md#vpcconfig)

## Properties

### endpointName

• `Optional` `Readonly` **endpointName**: `string`

___

### environment

• `Optional` `Readonly` **environment**: `Object`

#### Index signature

▪ [key: `string`]: `string`

___

### instanceCount

• `Optional` `Readonly` **instanceCount**: `number`

___

### instanceType

• `Optional` `Readonly` **instanceType**: [`SageMakerInstanceType`](../classes/SageMakerInstanceType.md)

___

### model

• `Readonly` **model**: [`JumpStartModel`](../classes/JumpStartModel.md)

___

### role

• `Optional` `Readonly` **role**: `Role`

___

### startupHealthCheckTimeoutInSeconds

• `Optional` `Readonly` **startupHealthCheckTimeoutInSeconds**: `number`

___

### vpcConfig

• `Optional` `Readonly` **vpcConfig**: `VpcConfigProperty`
