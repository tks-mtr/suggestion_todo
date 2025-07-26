```mermaid
flowchart TD

subgraph BackEnd
エンドポイント

end

subgraph FrontEnd
aaa-->|test|a1[test]
end

a1<-->|GraphQL, gRPC|エンドポイント
```