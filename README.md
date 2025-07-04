# be-swished

```html
<label for=lhs>LHS:</label>
<input id=lhs>
<label for=rhs>RHS:</label>
<input id=rhs>
<template
    be-swished='on if eq, based on #lhs and #rhs, and lhs-rhs ish loaded.'
>
    <div><span itemprop=lhs></span> === <span itemprop=rhs></span></div>
</template>
```

results in:

```html
<label for=lhs>LHS:</label>
<input id=lhs value=hello>
<label for=rhs>RHS:</label>
<input id=rhs value=hello>
<template
    be-swished='on if eq, based on #lhs and #rhs, and lhs-rhs ish loaded.'
>
    <div>
        <span itemprop=lhs></span> === <span itemprop=rhs></span>
    </div>
</template>
<div itemscope=lhs-rhs>
    <span itemprop=lhs></span> === <span itemprop=rhs></span>
</div>
```

