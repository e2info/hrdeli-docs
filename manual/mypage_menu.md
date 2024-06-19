---
title: マイページ専用メニューの追加・削除する
---
## 概要
HR Deliでは、マイページ専用メニュー（1ページ）につき複数のコンテンツが設定できます。

![マイページ専用メニューでできること](https://e2info.github.io/hrdeli-docs/manual/img/mypage_menu_summary.png)

<dl class="tips">
    <dt>コンテンツについて</dt>
    <dd>
        ［おすすめ求人］［登録情報の編集・表示］は、メニューを追加する前に別画面でコンテンツを作成する必要があります。<br>作成方法は下記をご確認ください。<br>
        <ul>
            <li><a href="https://e2info.github.io/hrdeli-docs/manual/news">お知らせを追加する</a></li>
            <li><a href="https://e2info.github.io/hrdeli-docs/manual/mypage_field-setting">登録情報の表示、編集を許可する（編集・表示項目設定）</a></li>
        </ul>
    </dd>
</dl>

本ページでは、マイページ管理 ＞ メニュー設定で行える［マイページ専用メニューの追加・削除］について記載いたします。
<!-- ※マイページ専用メニューの内、パスワードの変更 / メールアドレスの変更 / 退会の手続き は対象外となります。-->

<div class="index">
    <p>目次</p>
    <ul>
        <li>
            <a href="https://e2info.github.io/hrdeli-docs/manual/mypage_menu#create">
                マイページ専用メニューを追加する
            </a>
        </li>
        <li>
            <a href="https://e2info.github.io/hrdeli-docs/manual/mtpage_menu#delete">
                マイページ専用メニューを削除する
            </a>
        </li>
    </ul>
</div>


<h2 id="mypage_create">マイページ専用メニューを追加する</h2>

1．管理画面 > マイページ管理 > メニュー設定 に遷移します。

2．「新規登録」を押下します。<br>
<!-- ![メニュー設定-一覧画面](https://e2info.github.io/hrdeli-docs/manual/img/mtpage_menu-c_02.png) -->

3．フォームに各項目を入力します。<br>
<!-- ![メニュー設定-登録画面](https://e2info.github.io/hrdeli-docs/manual/img/XXX) -->

<p class="table_title">メニューの設定</p>

![メニュー設定-登録画面_メニューの設定](https://e2info.github.io/hrdeli-docs/manual/img/mypage_menu_create-menu.png)

No. | 項目名 | 説明 | 
------------- | ------------- | ------------- |  
1 | メニュー名  | メニューの名称を入力します。
2 | URL | メニューのURLを入力します。

<p class="table_title">コンテンツの設定</p>

![メニュー設定-登録画面_コンテンツの設定](https://e2info.github.io/hrdeli-docs/manual/img/mypage_menu_create-contents.png)

<table>
    <tr>
        <th>No.</th>
        <th>項目名</th>
        <th>説明</th>
    </tr>
    <tr>
        <td>3</td>
        <td>コンテンツ種別</td>
        <td>
            表示するコンテンツを指定します。詳細は以下のコンテンツ種別をご参照ください。
        </td>
    </tr>
    <tr>
        <td>4</td>
        <td>コンテンツ詳細</td>
        <td>
            <dl>
                <dt>コンテンツ種別［おすすめ求人］［編集・表示項目］の場合</dt>
                <dd>各設定画面で作成したタイトルが一覧で表示されます。その中から表示したいコンテンツを指定します。</dd>
            </dl>
            <dl>
                <dt>コンテンツ種別［HTML］の場合</dt>
                <dd>
                    ［テンプレート］と［本文のHTML］を展開します。
                </dd>
            </dl>
        </td>
    </tr>
    <tr>
        <td>5</td>
        <td>テンプレート</td>
        <td>見出しやテーブルなど追加したいパーツを指定し［追加］を押下することで、指定したパーツが［本文のHTML］に追加されます。テンプレートの詳細は<a href="https://e2info.github.io/hrdeli-docs/manual/cms" target="blank">CMS機能について</a>をご参照ください。</td>
    </tr>
    <tr>
        <td>6</td>
        <td>本文のHTML</td>
        <td> HTML形式で入力します。<br>見出しやテーブルといったパーツは「テンプレート」から追加可能です。</td>
    </tr>
    <tr>
        <td>7</td>
        <td>コンテンツ削除</td>
        <td> 押下した行が削除されます。</td>
    </tr>
    <tr>
        <td>8</td>
        <td>コンテンツ追加</td>
        <td>押下すると下に1行追加されます。</td>
    </tr>
    <tr>
        <td>9</td>
        <td>公開設定</td>
        <td> 求職者画面への公開/非公開を指定します。<br>コンテンツの表示イメージ</td>
    </tr>
</table>

<p id="contents">コンテンツ種別</p>

コンテンツの種類 | 説明 | 
------------- | ------------- | 
応募履歴 | 求職者の応募履歴の表示範囲や応募状況を表示します。<br>初期設定から内容を変更する場合、<a href="https://e2info.github.io/hrdeli-docs/manual/mypage_phases">応募履歴設定</a>をご参照ください。 | 
お知らせ | マイページ用のお知らせを表示します。<br>お知らせを追加する場合、<a href="https://e2info.github.io/hrdeli-docs/manual/news">お知らせを追加する</a>をご参照ください。 | メニューとして表示する選考プロセスフェーズを指定します。
おすすめ求人 | 貴社から求職者におすすめしたい求人を表示します。<br>※コンテンツを設定する場合、事前におすすめ求人を追加する必要があります。<br>詳細は<a href="https://e2info.github.io/hrdeli-docs/manual/mtpage_menu">おすすめ求人を追加・削除する</a>をご参照ください。
編集・表示項目 | 求職者にPORTERSに連携した求職者情報(個人連絡先/レジュメ)を表示します。また、登録情報を求職者に更新を許可することも可能です。<br>※コンテンツを設定する場合、事前に編集・表示項目を追加する必要があります。<br>詳細は<a href="https://e2info.github.io/hrdeli-docs/manual/mypage_field-setting">登録情報の表示、編集を許可する（編集・表示項目設定）</a>をご参照ください。
HTML | 任意のHTMLを設定することができます。<br>

<dl id="tips_item" class="tips">
    <dt>［本文のHTML］表示イメージについて</dt>
    <dd>
        設定した内容に対する画面イメージは、登録時点では確認することができません。<br>
        大変お手数ですが、一度公開設定を「非公開」で登録していただいた後、一覧画面のプレビューボタンから画面イメージをご確認ください。
    </dd>
</dl>

4． 「確認する」を押下し、確認画面に遷移します。<br>
![「確認する」ボタンを押す](https://e2info.github.io/hrdeli-docs/manual/img/common_push-check-button_with_back-button.png)

5．入力内容に問題がないようでしたら、「登録する」を押下します。<br>
![「登録する」ボタンを押す](https://e2info.github.io/hrdeli-docs/manual/img/common_push-registration-button_with_back-button.png.png)
<br>

6．メニュー設定 - 一覧画面に遷移し「マイページメニュー[メニュー名]を登録しました」とメッセージが表示されます。<br>
![メニュー設定-登録完了](https://e2info.github.io/hrdeli-docs/manual/img/mypage_menu_complete.png)


<h2 id="delete">メニューを削除する</h2>

1．管理画面 > マイページ管理 > メニュー設定 に遷移します。

2．「削除」を押下します。

3．削除確認のダイアログが展開されるので「OK」を押下します。<br>


[← 戻る](https://e2info.github.io/hrdeli-docs/)

{% include footer.md %}