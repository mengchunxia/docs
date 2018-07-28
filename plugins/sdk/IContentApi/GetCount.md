# IContentApi.GetCount method

获取满足条件的内容总数。

```csharp
public int GetCount(int siteId, int channelId, string whereString)
```

| parameter | description |
| --- | --- |
| siteId | 站点Id。 |
| channelId | 栏目Id。 |
| whereString | WHERE SQL语句 |

## Return Value

如果满足条件的内容存在，则返回内容总数；否则返回 0。

## See Also

* interface [IContentApi](sdk/IContentApi.md)
* namespace [SiteServer.Plugin](sdk/README.md)

<!-- DO NOT EDIT: generated by xmldocmd for SiteServer.Plugin.dll -->