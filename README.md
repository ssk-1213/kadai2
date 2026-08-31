1. AがGitHub上にリモートリポジトリを用意し、`index.html`（"Hello"と記述）を`main`ブランチにPushする。
<img width="674" height="841" alt="image" src="https://github.com/user-attachments/assets/09bec774-46fd-4b80-8a10-6673b185310a" />
2．BがAのリポジトリからforkを作成する
<img width="1060" height="764" alt="スクリーンショット 2026-08-28 132938" src="https://github.com/user-attachments/assets/94c2c2a4-479a-4dc4-87d7-bbde57996317" />
※参考画像https://www.bing.com/images/search?view=detailV2&ccid=TeQ3vMPj&id=78E20A841D0A166E18AC44DCFFFC601C3BAE1CEC&thid=OIP.TeQ3vMPjUh2MNE2_arOuwgHaFP&mediaurl=https%3A%2F%2Fopendevbook.github.io%2Fgit_book%2Fassets%2Fimages%2Fgithub-fork-create.png&exph=730&expw=1030&q=github+create+fork&ck=064D70A9B0C1D60ED692C8674B5A36AB&selectedIndex=3&itb=0&cw=1721&ch=853&ajaxhist=0&ajaxserp=0&shtc=0&shth=OIP.TeQ3vMPjUh2MNE2_arOuwgHaFP&shsc=idp&form=EX0050&shid=d6ed63e4-0c46-42c0-a830-34652813a64c&shtp=GetUrl&shtk=R2l0IHdvcmtzaG9wMg%3D%3D&shdk=QmluZyDkuIrjga4gb3BlbmRldmJvb2suZ2l0aHViLmlvIOOBq%2Bimi%2BOBpOOBi%2BOCiuOBvuOBl%2BOBnw%3D%3D&shhk=O2%2Fc5ugH%2FXh%2F16gI%2F6Ul%2BT4liGkZLkDATX3qxkgLv1I%3D
3. Bがリポジトリをcloneし、作業ブランチを作成。`index.html`を編集してPushし、Aへプルリクエストを出す。
<img width="830" height="1029" alt="スクリーンショット 2026-08-31 113223" src="https://github.com/user-attachments/assets/3e6cf10b-94d1-4a6f-b6a7-d752ae498ae8" />
4. AがBのプルリクエストをレビューし、`main`ブランチにマージする。
5. Aがローカルの`main`ブランチを最新化（pull）し、作業ブランチを作成。`index.html`を編集してPRを作成・マージする。
6. Bがローカルの`main`ブランチを最新化（pull）し、作業ブランチを作成。`stylesheet.css`を追加してAへプルリクエストを出す。
7. AがBのプルリクエストをレビューし、`main`ブランチにマージする。
