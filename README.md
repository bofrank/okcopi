# okcopi

This code when run outputs the following blockchain as a proof of concept:

```json
{
    "chain": [
        {
            "index": 0,
            "timestamp": "01/01/2017",
            "data": "Genesis block",
            "previousHash": "0",
            "hash": "4373c7fb1437035365d9228c77eca2cfd240523e274163e78c1eba11effd8b38"
        },
        {
            "index": 1,
            "timestamp": "10/07/2017",
            "data": {
                "amount": 4
            },
            "previousHash": "4373c7fb1437035365d9228c77eca2cfd240523e274163e78c1eba11effd8b38",
            "hash": "c37ff893464874ffb4cfb0e0da1961786a0fd14ed68157af3a468944d098ecad"
        },
        {
            "index": 1,
            "timestamp": "12/07/2017",
            "data": {
                "amount": 10
            },
            "previousHash": "c37ff893464874ffb4cfb0e0da1961786a0fd14ed68157af3a468944d098ecad",
            "hash": "de1f0402361f32c515a5ef5fd4d6729844dcea193c7aac1c53544a250e9df62f"
        }
    ]
}
```
