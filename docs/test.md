==This is highlighted text==

~~This is the wrong way to do~~


```json
{
  "jsonrpc": "2.0",
  "id": 1,
  "result": true
}
```


!!! note
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! abstract
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! info
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! tip
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! success
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! question
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! warning
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! failure
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! bug
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! danger
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! quote
    This is a multi line note
    in the Hyperledger Besu documentation.

!!! example
    This example shows how to use the `net_listening` RPC method.
    
    ```bash tab="curl HTTP request"
    $ curl -X POST --data '{"jsonrpc":"2.0","method":"net_listening","params":[],"id":53}' <JSON-RPC-http-endpoint:port>
    ```
    
    ```bash tab="wscat WS request"
    {"jsonrpc":"2.0","method":"net_listening","params":[],"id":53}
    ```
    
    ```json tab="JSON result"
    {
      "jsonrpc" : "2.0",
      "id" : 53,
      "result" : true
    }
    ```