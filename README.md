<div align="center">

## Javascript Rollover Fade


</div>

### Description

This script lets you specify two images and on mouseover of the image it fades to a different image. perfect for dhtml fade navs.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[chris mcintosh](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/chris-mcintosh.md)
**Level**          |Intermediate
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |
**Category**       |[Graphics](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/graphics__2-75.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/chris-mcintosh-javascript-rollover-fade__2-3663/archive/master.zip)





### Source Code

```
<%@LANGUAGE="VBSCRIPT" CODEPAGE="1252"%>
<"script" type="text/javascript">
function blendCham(which) {
  imCham.filters.blendTrans.Apply();
  imCham.src = which;
  imCham.filters.blendTrans.Play();
}
</script>
<"IMG" ID="imCham" SRC="logoraw.png" STYLE="filter:blendTrans(duration=2)" onmouseout="blendCham('logoraw.png')" onmouseover="blendCham('logoraw2.png')">
```

