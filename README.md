# My Articles

A collection of current writting / past articles.

## Before begin, refer

- [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
- [Markdownlint rules](https://github.com/DavidAnson/markdownlint/blob/master/doc/Rules.md)
- The folder `/sample-hangzhou-house-nowledge` for a sample structure (you will see broken images because for save storage, I deleted most of them)

## How to use it

1. Use kebab-case for file names and directory names. e.g. my-folder, my-awesome-new-article.
2. `<>` stand for a variable, use camelcase for variable name. e.g. `<nameOfImage>`
3. Create a new folder for each new article,
4. Article name should begin with `[]` to classify it, refer [the table below](#article-name-classify-table)
5. Images should under it's subfolder `/images`.
    - Name convention for image: `image-<index>__<nameOfImage>-.<extentionType>`. e.g. `image-1__大本营地图.png`
    - Keep `<index>` as increase by 1 begin from 0 (yep, programmer always count from 0). If need to add new image, instead of renaming all the existing ones after it, put sub version. e.g. `image-1`, `image-2`, `image-3`, `image-4`. When wants to insert new image between `image-3` and `image-4`, name it `image-3.1`.
    - `<nameOfImage>` will be used in markdown for accessibility, so people use screenreader can know what it is, e.g. `[大本营地图](url)`
    - `<extentionType>` should be all lower case, e.g. `png` not ~~PNG~~
    - Insert image below the text that mention this image, instead of put image above it. Why? it's more clear when user see the image, they already has some context of it.
6. Create a summary for each article, may including # in next line.
7. Put a space between number / english words and chinese character. e.g. "价格是 30 RMB", "非常 serious 的态度". If it means numberic value, use 1, 2, 3 instead of the chinese "一，二，三". However if it has context, use chinese. e.g. "一些碎片时间", "一次竞赛的时间长度一般为 6 天". If there is a special char near number and chinese, put a space between them, if the special char only between chinese, no space. e.g. "在联机/对抗赛中获胜 3 场", "摧毁 12 个圣水瓶 / 12 个箭塔 / 4 个实验室".
8. Create a README.md in the same folder
    - Create social media description (text post on social media).
    - keep links of each source that published and other relevant 'meta' information.
9. Convert to text (for post on 微信游戏圈)
    - Use VS plugin convert to `.html`
    - USe the following command to extra text _[TODO: write npm script for it]_ `cat example/test.html | node_modules/.bin/html-to-text > test.txt`
10. Convert to traditional chinese by copy the article into `scripts/chinese-conv.js` _[TODO: fort the lib and create a cli tool for it]_ https://github.com/Pleasurazy/chinese-conv

## Reference

### Article Name Classify Table

Name | Category
------------ | -------------
cc | clash of clans