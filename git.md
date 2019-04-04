# githubメモ
1. gitで管理したいファイルを作る  
`mkdir samplefile`  
2. gitを入れる  
`git init`  
3. githubと連携する(この場合ファーストコミットはいらない。.git毎くる)  
`git remote add origin githubのSSHリンク`  
4. 作業をしたら
`git add -A`(ST:作業コピー)  
`git commit -m "Initialized repository"`(ST:コミット)  
`git push origin master`(ST:プッシュ)  

リモート先から持ってきたい場合はcloneもしくはpull

`git status`でブランチ等の状態を確認できる
