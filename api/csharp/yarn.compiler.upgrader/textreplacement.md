# TextReplacement Struct

Contains information describing a replacement to make in a string.


```csharp
public struct TextReplacement
```



## Fields
|Name|Description|
|:---|:---|
|[Comment](/api/csharp/yarn.compiler.upgrader/textreplacement.comment.md)| A descriptive comment explaining why the substitution is necessary. |
|[OriginalText](/api/csharp/yarn.compiler.upgrader/textreplacement.originaltext.md)| The string to expect at [`Start`](/api/csharp/yarn.compiler.upgrader/textreplacement.start.md) in the original string. |
|[ReplacementText](/api/csharp/yarn.compiler.upgrader/textreplacement.replacementtext.md)| The string to replace [`OriginalText`](/api/csharp/yarn.compiler.upgrader/textreplacement.originaltext.md) with at [`Start`](/api/csharp/yarn.compiler.upgrader/textreplacement.start.md). |
|[Start](/api/csharp/yarn.compiler.upgrader/textreplacement.start.md)| The position in the original string where the substitution should be made. |
|[StartLine](/api/csharp/yarn.compiler.upgrader/textreplacement.startline.md)| The line in the original string where the substitution should be made. |
## Properties
|Name|Description|
|:---|:---|
|[OriginalLength](/api/csharp/yarn.compiler.upgrader/textreplacement.originallength.md)| Gets the length of [`OriginalText`](/api/csharp/yarn.compiler.upgrader/textreplacement.originaltext.md). |
|[ReplacementLength](/api/csharp/yarn.compiler.upgrader/textreplacement.replacementlength.md)| Gets the length of [`ReplacementLength`](/api/csharp/yarn.compiler.upgrader/textreplacement.replacementlength.md). |
<div class="class-metadata">

Namespace: [`Yarn.Compiler.Upgrader`](/api/csharp/yarn.compiler.upgrader/README.md), Assembly: YarnSpinner.Compiler.dll
</div>

## Source
Defined in [YarnSpinner.Compiler/Upgrader/LanguageUpgrader.cs](https://github.com/YarnSpinnerTool/YarnSpinner//blob/develop/YarnSpinner.Compiler/Upgrader/LanguageUpgrader.cs#L153), line 153.