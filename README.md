1. AがGitHub上にリモートリポジトリを用意し、`index.html`（"Hello"と記述）を`main`ブランチにPushする。
<img width="674" height="841" alt="image" src="https://github.com/user-attachments/assets/09bec774-46fd-4b80-8a10-6673b185310a" />
2．BがAのリポジトリからforkを作成する
<img width="830" height="1029" alt="スクリーンショット 2026-08-31 113223" src="https://github.com/user-attachments/assets/1d7b2888-71e7-42c4-a9fd-b71476aedcbf" />
3. Bがリポジトリをcloneし、作業ブランチを作成。`index.html`を編集してPushし、Aへプルリクエストを出す。
<img width="830" height="1029" alt="スクリーンショット 2026-08-31 113223" src="https://github.com/user-attachments/assets/3e6cf10b-94d1-4a6f-b6a7-d752ae498ae8" />
4. AがBのプルリクエストをレビューし、`main`ブランチにマージする。
<img width="554" height="937" alt="image" src="https://github.com/user-attachments/assets/6ebceffc-757e-477a-a90f-c634dfb3ebc9" />
5. Aがローカルの`main`ブランチを最新化（upatream）し、作業ブランチを作成。`index.html`を編集してPRを作成・マージする。
<img width="988" height="928" alt="スクリーンショット 2026-08-31 113718" src="https://github.com/user-attachments/assets/5015de69-facc-4af7-b654-d01ccfb79de0" />
6. Bがローカルの`main`ブランチを最新化（pull）し、作業ブランチを作成。`stylesheet.css`を追加してAへプルリクエストを出す。
<img width="702" height="982" alt="スクリーンショット 2026-08-31 113731" src="https://github.com/user-attachments/assets/bc985261-eea7-41ef-a7b3-468241831455" />
<img width="727" height="743" alt="スクリーンショット 2026-08-31 113743" src="https://github.com/user-attachments/assets/0f48a129-6bae-4486-8582-9591efb709da" />
7. AがBのプルリクエストをレビューし、`main`ブランチにマージする。
