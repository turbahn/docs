# KeystoreWalletWrapper

Convenience wrapper of the LocalWallet to connect to a keystore

## Hierarchy

* **KeystoreWalletWrapper**

## Index

### Constructors

* [constructor]()

### Methods

* [getKeystore]()
* [getLocalWallet]()
* [importPrivateKey]()
* [lockAccount]()
* [unlockAccount]()

## Constructors

### constructor

+ **new KeystoreWalletWrapper**\(`keystore`: [KeystoreBase]()\): [_KeystoreWalletWrapper_]()

_Defined in_ [_keystore-wallet-wrapper.ts:9_](https://github.com/celo-org/celo-monorepo/blob/master/packages/sdk/keystores/src/keystore-wallet-wrapper.ts#L9)

**Parameters:**

| Name | Type |
| :--- | :--- |
| `keystore` | [KeystoreBase]() |

**Returns:** [_KeystoreWalletWrapper_]()

## Methods

### getKeystore

▸ **getKeystore**\(\): [_KeystoreBase_]()

_Defined in_ [_keystore-wallet-wrapper.ts:25_](https://github.com/celo-org/celo-monorepo/blob/master/packages/sdk/keystores/src/keystore-wallet-wrapper.ts#L25)

**Returns:** [_KeystoreBase_]()

### getLocalWallet

▸ **getLocalWallet**\(\): _LocalWallet_

_Defined in_ [_keystore-wallet-wrapper.ts:21_](https://github.com/celo-org/celo-monorepo/blob/master/packages/sdk/keystores/src/keystore-wallet-wrapper.ts#L21)

**Returns:** _LocalWallet_

### importPrivateKey

▸ **importPrivateKey**\(`privateKey`: string, `passphrase`: string\): _Promise‹void›_

_Defined in_ [_keystore-wallet-wrapper.ts:16_](https://github.com/celo-org/celo-monorepo/blob/master/packages/sdk/keystores/src/keystore-wallet-wrapper.ts#L16)

**Parameters:**

| Name | Type |
| :--- | :--- |
| `privateKey` | string |
| `passphrase` | string |

**Returns:** _Promise‹void›_

### lockAccount

▸ **lockAccount**\(`address`: string\): _Promise‹void›_

_Defined in_ [_keystore-wallet-wrapper.ts:34_](https://github.com/celo-org/celo-monorepo/blob/master/packages/sdk/keystores/src/keystore-wallet-wrapper.ts#L34)

**Parameters:**

| Name | Type |
| :--- | :--- |
| `address` | string |

**Returns:** _Promise‹void›_

### unlockAccount

▸ **unlockAccount**\(`address`: string, `passphrase`: string\): _Promise‹void›_

_Defined in_ [_keystore-wallet-wrapper.ts:29_](https://github.com/celo-org/celo-monorepo/blob/master/packages/sdk/keystores/src/keystore-wallet-wrapper.ts#L29)

**Parameters:**

| Name | Type |
| :--- | :--- |
| `address` | string |
| `passphrase` | string |

**Returns:** _Promise‹void›_
