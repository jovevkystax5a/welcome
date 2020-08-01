---
id: validate
title: validate
sidebar_label: validate
---

# `/transaction/validate`

The `validate` validates whether the given transaction is valid on the Aleo network.

## Request Type

```
POST /transaction/validate
```

## Parameters

### raw transaction <span style="color:red">required</span>

A 1950 character long string that represents an valid signed raw transaction.

## Response

A boolean value (true or false), whether the transaction is valid or not.

```
true
```