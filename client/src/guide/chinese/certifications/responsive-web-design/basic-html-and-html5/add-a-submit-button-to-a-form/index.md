title: Add a Submit Button to a Form	
localeTitle: undefined
---	## 向表单添加提交按钮

在此挑战中，您希望将提交按钮作为表单的最后一个元素（在`</form>`结束标记之前）插入，并为其提供属性`type="submit"` （全部小写）和文本内容“提交” “（第一个字母大写），在挑战指令中指定。

1）属性`type` `submit`值也在`input`标记内有效，它将呈现具有几乎相同行为的按钮，但这不是您要在此挑战中使用的标记。
```
<input type="submit"> 
```

如果您未指定值，则该按钮将具有您的用户代理选择的默认值（通常这类似于“提交”或“提交查询”）。

如果您希望指定类似“发送请求”的值，您可以这样做：
```
<input type="submit" value="Send Request"> 

```