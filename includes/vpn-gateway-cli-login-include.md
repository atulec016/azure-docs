---
 title: include file
 description: include file
 services: vpn-gateway
 author: cherylmc
 ms.service: vpn-gateway
 ms.topic: include
 ms.date: 03/21/2018
 ms.author: cherylmc
 ms.custom: include file
---
Sign in to your Azure subscription with the [az login](/cli/azure/#login) command and follow the on-screen directions. For more information about signing in, see [Get Started with Azure CLI 2.0](/cli/azure/get-started-with-azure-cli).

```azurecli
az login
```

If you have more than one Azure subscription, list the subscriptions for the account.

```azurecli
az account list --all
```

Specify the subscription that you want to use.

```azurecli
az account set --subscription <replace_with_your_subscription_id>
```