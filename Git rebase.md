



```mermaid
flowchart LR
	direction LR
	subgraph master
	初始化 --> master节点1 --> master节点2
	end
	direction TB
	subgraph feature
	master节点1 --> feature节点1 --> feature节点2
	end
```

