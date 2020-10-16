# Introduction_1016

## Netlify
### 成果物をNetlifyで表示させる
- GitHubの場合、プルリクをマージしてもらうまでGitHub Pagesが見れないため  
  Netlifyを使ってウェブサイトを公開
- サイトを公開することプルリクの段階でもブラウザ上でコードの動作を見ていただくことができる
## 詳解JavaScript オブジェクト編
### 第14回 `Object.keys()`の部分での疑問点
- プロパティの取得にはドット記法とブラケット記法の2つがあるが
  ブラケット記法でしか書けない場合がある
---
    const point = {
        x: 100, 
        y: 180,
    };

    const keys = Object.keys(point);
    keys.forEach(key => {
        console.log(`Key: ${key} Value: ${point[key]}`)
    })
---
