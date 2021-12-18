# GetTagsForNode\(String\)

Returns the tags for the node 'nodeName'.

```csharp
public IEnumerable<string> GetTagsForNode(string nodeName)
```

## Remarks

The tags for a node are defined by setting the `tags` \[header\]\(\) in the node's source code. This header must be a space-separated list.

## Parameters

| Parameter | Description |
| :--- | :--- |
| [`string`](https://docs.microsoft.com/dotnet/api/System.String) nodeName | The name of the node. |

## Return Type

[`String}`](https://docs.microsoft.com/dotnet/api/System.Collections.Generic.IEnumerable{System.String}): The node's tags, or `null` if the node is not present in the Program.

## Namespace

[`Yarn`](../)

## Assembly

YarnSpinner.dll

## Source

Defined in [YarnSpinner/Dialogue.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner/Dialogue.cs#L797), line 797.
