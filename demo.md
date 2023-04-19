sequenceDiagram
	participant 机构
    participant 服务市场
    participant HIVE
    participant 新氧通WB
    participant 搜推
    机构->>服务市场: 购买服务市场全能包
    服务市场->>搜推: 新增购买服务机构
    loop Healthcheck
    	HIVE->>HIVE: 运营同学配置包杆城市
    end
    HIVE->>服务市场: 
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!