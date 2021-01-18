# Webtoon-Dataset

This repo only give google drive URL for Webtoon Dataset. You can access it with [this link](https://drive.google.com/drive/folders/1xslbuuozniVlayjQWC6mjabxEsxHI8ai?usp=sharing). This repo's only available until end of 2021 so **GRAB IT FAST**. Feel free to copy them.

## Description
This will have six languages in Webtoon
1. English ([en](https://www.webtoons.com/en/genre)) 
2. Indonesia ([id](https://www.webtoons.com/id/genre))
3. Chinese (?) ([zh-hant](https://www.webtoons.com/zh-hant/genre))
4. Thailand ([th](https://www.webtoons.com/th/genre))
5. Spanish ([es](https://www.webtoons.com/es/genre))
6. France ([fr](https://www.webtoons.com/fr/genre))

## Description Drive
Every languages will have 4 types folder
1. {lang}
   - Raw from crawling using this [repo](https://github.com/JeremyRuhland/webtoon-dl.py)
   - The contents are webtoon title folders + cbz file for the image
2. {lang}_ext (**ABANDONED**)
   - Extract from cbz file
   - **ABANDONED** Because My Drive is crying :')
3. {lang}_face
   - Crop Face from {lang}_mrg using [anime-face-detector](https://github.com/qhgz2013/anime-face-detector)
4. {lang}_mrg
   - Concat between every two image. The reason is getting more face images (sometimes one face can be separated in two images).