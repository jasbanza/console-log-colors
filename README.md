# console-log-colors
Color markup wrapper module for console.log 

### usage 
```js
import out from "js-console-log-colors";

out.ln(); // A line break, same as console.log();
out.info("cyan text"); //🔵
out.warn("yellow text"); //🟡
out.success("green text"); //🟢
out.command("magenta text"); //🟣
out.debug("black text, yellow background"); //🟨⚫🟨
out.error("white text, red background"); // 🟥⚪🟥
```

