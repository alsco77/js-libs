

# Functions

<a id="accounts_"></a>

##  accounts$

▸ **accounts$**(options?: *[RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md)*): `Observable`<`string`[]>

*Defined in [rpc/eth.ts:25](https://github.com/paritytech/js-libs/blob/4cbf0f0/packages/light.js/src/rpc/eth.ts#L25)*

Observable which contains the array of all addresses managed by the light client.

Calls eth\_accounts.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| `Optional` options | [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md) |  Options to pass to [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md). |

**Returns:** `Observable`<`string`[]>
- An Observable containing the list of public addresses.

___
<a id="balanceof_"></a>

##  balanceOf$

▸ **balanceOf$**(address: *[Address](_types_.md#address)*, options?: *[RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md)*): `Observable`< `BigNumber` &#124; `Symbol`>

*Defined in [rpc/eth.ts:39](https://github.com/paritytech/js-libs/blob/4cbf0f0/packages/light.js/src/rpc/eth.ts#L39)*

Get the balance of a given account. Calls `eth_getBalance`.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| address | [Address](_types_.md#address) |  The account address to query the balance. |
| `Optional` options | [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md) |  Options to pass to [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md). |

**Returns:** `Observable`< `BigNumber` &#124; `Symbol`>
- An Observable containing the balance.

___
<a id="blocknumber_"></a>

##  blockNumber$

▸ **blockNumber$**(options?: *[RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md)*): `Observable`<`BigNumber`>

*Defined in [rpc/eth.ts:84](https://github.com/paritytech/js-libs/blob/4cbf0f0/packages/light.js/src/rpc/eth.ts#L84)*

Get the current block number.

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` options | [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md) |

**Returns:** `Observable`<`BigNumber`>
- An Observable containing the block height.

___
<a id="defaultaccount_"></a>

##  defaultAccount$

▸ **defaultAccount$**(options?: *[RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md)*): `Observable`<`string`>

*Defined in [rpc/eth.ts:71](https://github.com/paritytech/js-libs/blob/4cbf0f0/packages/light.js/src/rpc/eth.ts#L71)*

Get the default account managed by the light client.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| `Optional` options | [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md) |  Options to pass to [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md). |

**Returns:** `Observable`<`string`>
- An Observable containing the public address
of the default account.

___
<a id="mybalance_"></a>

##  myBalance$

▸ **myBalance$**(options?: *[RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md)*): `Observable`< `BigNumber` &#124; `Symbol`>

*Defined in [rpc/eth.ts:95](https://github.com/paritytech/js-libs/blob/4cbf0f0/packages/light.js/src/rpc/eth.ts#L95)*

Shorthand for fetching the current account's balance.

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` options | [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md) |

**Returns:** `Observable`< `BigNumber` &#124; `Symbol`>

___
<a id="syncstatus_"></a>

##  syncStatus$

▸ **syncStatus$**(options?: *[RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md)*): `Observable`< `false` &#124; `true` &#124; `object`>

*Defined in [rpc/eth.ts:115](https://github.com/paritytech/js-libs/blob/4cbf0f0/packages/light.js/src/rpc/eth.ts#L115)*

Get the syncStatus state.

**Parameters:**

| Name | Type |
| ------ | ------ |
| `Optional` options | [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md) |

**Returns:** `Observable`< `false` &#124; `true` &#124; `object`>
- An Observable containing the syncing state object, or false.

___
<a id="transactioncountof_"></a>

##  transactionCountOf$

▸ **transactionCountOf$**(address: *[Address](_types_.md#address)*, options?: *[RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md)*): `Observable`< `BigNumber` &#124; `Symbol`>

*Defined in [rpc/eth.ts:55](https://github.com/paritytech/js-libs/blob/4cbf0f0/packages/light.js/src/rpc/eth.ts#L55)*

Get the transaction count of a given account. Calls `eth_getTransactionCount`

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| address | [Address](_types_.md#address) |  Address of the account whose transaction count we want to query. |
| `Optional` options | [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md) |  Options to pass to [RpcObservableOptions](../interfaces/_types_.rpcobservableoptions.md). |

**Returns:** `Observable`< `BigNumber` &#124; `Symbol`>
- An Observable containing the transaction count.

___

