::: danger Dangerous RPC calls controlled by `enable_control`
This RPC command/option requires `enable_control` to be enabled within the RPC config file. Enabling this means that anyone with access to the RPC port could potentially [access wallet funds](/node/rpc#send), [stop](/node/rpc#stop) the node from running and take other dangerous actions. **Use caution when enabling this option, especially with external RPC access available.** For more details see the [Node Security page](#).
:::
