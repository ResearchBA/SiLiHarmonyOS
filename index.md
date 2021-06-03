## Welcome to SiLiHarmonyOS

You can use the [editor on GitHub](https://github.com/SiLiHarmonyOS/SiLiHarmonyOS/edit/gh-pages/index.md) to maintain and preview the content for my website in Markdown files.

SiLiHarmonyOS is the study platform of HarmonyOS of Huawei.

### DevEco Studio

DevEco Studio is the IDE of HarmonyOS Applications. You can download [here](https://developer.harmonyos.com/en/develop/deveco-studio)

### My First Try 

![DevEco Studio](https://gitee.com/theforage/catslinc/raw/master/picbed/DevEcoStudio.png)

```markdown
MainAbility.java

package com.catslinc.siliharmonyos;

import ohos.ace.ability.AceAbility;
import ohos.aafwk.content.Intent;

public class MainAbility extends AceAbility {
    @Override
    public void onStart(Intent intent) {
        super.onStart(intent);
    }

    @Override
    public void onStop() {
        super.onStop();
    }
}
```

```markdown
app.js

export default {
    onCreate() {
        console.info('AceApplication onCreate');
    },
    onDestroy() {
        console.info('AceApplication onDestroy');
    }
};
```

### Support or Contact

Having trouble with Applications and Development on HarmonyOS? Check out our [technical website](https://theforage.herokuapp.com/) or [business applications](https://www.theforage.cn) and we’ll help you sort it out.
