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
7. Put a space between number / english words and chinese character. e.g. "价格是 30 RMB", "非常 serious 的态度". Use 1, 2, 3 instead of the chinese 一，二，三。

## Reference

### Article Name Classify Table

Name | Category
------------ | -------------
cc | clash of clans