# Data Path Setting

- The data path can be a remote server path, such as http://example.com/data.
- Or you can start a service locally, e.g. on port 3333, then the data path will be http://localhost:3333/data.
- If you need it in the project folder, you can copy the data to the project `data` folder, and then use vscode to right-click the html file to open with live server, then the data path can be written as http://localhost:5500/data, usually vscode will start port 5500 by default, you can set the data path according to the starting port. You can set the data path according to the port.

# SDK import

- ES Module Import
```
import { LCCRender } from './sdk/lcc-0.3.1.js'
// Use SDK ...
```
- UMD Import

```
<script src="./sdk/lcc-0.3.1.umd.js"></script>

<script>
    const LCCRender = LCC.LCCRender;
    // Use SDK ...
</script>
```
