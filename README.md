# portfolio
My portfolio

## 👩‍💻 自己紹介
Javaを中心に学習中の者です。Servlet/JSPを用いた簡単なWebアプリを制作しました。実務経験はありませんが、学生時代に実践的な課題に取り組んできました。
最大四人のチームでアプリの作成を経験したことがあります。

## 📌 紹介するアプリ一覧
・おみくじあぷり<br>
・Todo管理アプリ<br>
--------ここから下は学生時代の成果物です--------<br>
・教育支援アプリ(先生・生徒・保護者の方々が利用することを想定)<br>
・健康支援アプリ<br>
・チャットアプリ

---


## 🍀 おみくじアプリ（Java + JSP）
- おみくじを引ける
- 大吉の時のみエフェクト実装


## 🔧 使用技術
- Java（Servlet）
- JSP
- HTML / CSS（画面構成）
- Tomcat 9（ローカル実行）
- Eclipse（開発環境）

🖼️ **スクリーンショット**<br>
| おみくじ画面 | おみくじ結果(大吉) |
|-------------|------------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Omikuji.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Omikuji.png?raw=true" width="250"/></a> | <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Omikuji-Daikichi.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Omikuji-Daikichi.png?raw=true" width="250"/></a> |

| おみくじ結果(小吉) |
|-------------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Omikuji-Result.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Omikuji-Result.png?raw=true" width="250"/></a> |



▶️ **動画リンク**
https://drive.google.com/file/d/1D_razDd2ea7fCsKjuQEp5SYyHHCsPjb2/view?usp=sharing

**💻 コード（.zip）ダウンロード**<br>
おみくじアプリコード：https://drive.google.com/file/d/1HN3qX4AjFjhW2NTvb-85z3oi8UnGUJu3/view?usp=sharing

```plaintext
📦OmikujiApp
 ┣ 📂src/main/java/Servlet/
 ┃ ┗ 📄OmikujiServlet.java
 ┣ 📂webapp/
 ┃ ┣ 📄index.jsp
 ┃ ┗ 📄result.jsp
```

---

## 📋 ToDo管理アプリ（Java + JSP）
- チェックボックス付きToDoリスト
- 追加・削除・完了の管理可能
- 完了時取り消し線が引かれる

## 🔧 使用技術
- Java（Servlet）
- JSP
- HTML / CSS（画面構成）
- Tomcat 9（ローカル実行）
- Eclipse（開発環境）


🖼️ **スクリーンショット**<br>
| ホーム画面 | タスク入力 |
|------------|-----------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoHome.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoHome.png?raw=true" width="250"/></a> | <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoTask.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoTask.png?raw=true" width="250"/></a> |

| タスク追加済み | チェック済み |
|---------------|-------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoTask2.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoTask2.png?raw=true" width="250"/></a> | <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoChecked.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoChecked.png?raw=true" width="250"/></a> |

| タスクの削除 |
|-------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoDeleted.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/TodoDeleted.png?raw=true" width="250"/></a> |



▶️ **動画リンク**
https://drive.google.com/file/d/1buIK7Euh1x5fv8Ket99FSv8sRQifef8Y/view?usp=sharing

**💻 コード（.zip）ダウンロード**<br>
Todo管理アプリコード：https://drive.google.com/file/d/1lSUBJEewkczoSwRXEAcgiM3N78c8lNGz/view?usp=sharing

```plaintext
📦TodoCheckApp 
 ┣ 📂src/main/java/servlet/ 
 ┃ ┗ 📄TodoItem.java
 ┃ ┗ 📄TodoServlet.java 
 ┣ 📂webapp/
 ┃ ┗ 📄todo.jsp
```


---

## 📁 チーム開発の経験（学校課題）
### 「教育支援アプリ（ローコード）」

## 🔧 使用技術
- JavaScript
- css
- Kintone（開発環境）
- Kintone plugin

## 📃 アプリ説明
本アプリは、教育機関・学校向けに開発しました。作成時、ターゲットを小学校にし、ユーザーは先生・保護者・生徒を想定しました。
<本アプリ制作目的>
・学校で配布されるプリント類の電子化
・保護者、先生の円滑な連絡ツール(欠席連絡や行事の参加可否、個人情報入力画面も作成)
・いじめアンケートの簡易化(いつ何時も入力可能、匿名性確保、いじめ報告の心理的壁を排除)
・年間行事・イベント事の通知(カレンダー機能)

- 3人のチームでKintoneを使って開発
- 自分は画面(基盤)作成、デザイン考案、進捗管理、ポスター・プレゼン資料及び動画編集、その他掲示物資料(サンプル)を製作しました。
- エラー対策や必須項目機能も実施
- それぞれの利用者ごとの画面表示を設定
- プリント提出や通知などが対象者のみに送られるような設定

## ✨ 頑張ったこと
ローコードなこともあり、アプリ自体の基盤を作るのは、かなり早く順調に作ることができました。<br>
cssやJavaScript、pluginなどを使用し、色の統一や見やすさにこだわりました。<br>
先生・保護者・生徒という三種で分け、通知設定や画面表示設定を行いました。<br>
(例：欠席連絡が先生だけに届く、学校で配布されるプリントを保護者・生とともに通知される等)


※コードや詳細な内容が残っていませんが、資料や設計書あり<br>
※一部資料の個人の特定を避けるため編集を施していますが、内容に影響はありません。

▶️ **動画リンク(ゼミ用に作成したものです)**<br>
https://drive.google.com/file/d/1WJGoxuqSSdPqeb1INWCeLQsNaU9lMKXo/view?usp=sharing<br>
※音声がありますので音量にご注意ください。<br>
・動画編集を主に担当しました<br>
・音楽選びや各動画撮影を素敵なチームメンバーに協力していただきました。

📑 **資料諸々**<br>
https://drive.google.com/file/d/1k70q0IX4sbLQpst1U-zeVDC_hDFeyLbj/view?usp=sharing<br>
サンプルプリント、ポスター、卒業研究概要説明書2、発表資料を作成させていただきましたのでぜひご覧ください。<br>
その他の資料は素敵なチームメンバーに作成していただきました。

---

## 📁 チーム開発の経験（学校課題）
## 「健康支援アプリ」
※本アプリのコード、資料は一切ありません。
※画像と動画及び説明のみになりますので、学校での記録と思っていただけたらと思います。

## 🔧 使用技術
- Java（Servlet）
- JSP
- HTML / CSS（画面構成）
- Tomcat 9（ローカル実行）
- Eclipse（開発環境）

## 📃 アプリ説明
本アプリは、利用者の健康を支援する目的で作成しました。ターゲットユーザーとしては若い女性にしました。<br>
<本アプリ制作目的><br>
・ダイエット記録の管理（目標体重と現在体重の入力）
・日々のTodo管理(当日にこなすタスクを入力)
・習慣付けを目的としたチェックリスト作成

- 2人で開発しました。
- 自分は主にバックエンドを担当しました。ロゴの作成や使用する画像・デザインの決定をフロントエンドの方と相談し決定しました。
- エラー入力、空白入力のエラーの表示もしました。
- 健康目的のダイエットや習慣作りを想定して作成しています。
- 現在体重と目標体重の差を計算する機能を作りました。


## ✨ 頑張ったこと

初の二人での協力作業だったので、バックエンド、フロントエンドの情報、作業進捗度の共有の難しさを体験できました。<br>
習慣の英語habitを取り、女性向けなアプリなこともあり、habiton(はびっとん)というかわいらしい雰囲気のアプリ名を付けました。<br>
ロゴやデザインを含め、大人の女性向けの落ち着きつつも、柔らかい雰囲気の配色を選びました。文字色も黒ではなく茶色にすることで背景色との統一感を出しました。<br>
Servletが機能しているかどうかを何度も確かめながら頑張りました。<br>
Todoリスト機能や、チェックボックス、計算機能の搭載をし、本格的に使用できるアプリらしく作成することを頑張りました。<br>

🖼️ **スクリーンショット**<br>

| メイン画面 | ToDo画面 |
|------------|----------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-MainPage.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-MainPage.png?raw=true" width="250"/></a> | <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Todo.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Todo.png?raw=true" width="250"/></a> |

| 習慣画面 | 目標体重画面 |
|----------|-------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Habit.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Habit.png?raw=true" width="250"/></a> | <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Goal.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Goal.png?raw=true" width="250"/></a> |

| 体重管理画面 |
|-------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Weight.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Health-Weight.png?raw=true" width="250"/></a> |


▶️ **動画リンク**<br>
https://drive.google.com/file/d/1eS-lsGR3UFnaWw2T1q3JS_mXuf7-1PZF/view?usp=sharing<br>
※本動画には細かな操作が含まれます。必要に応じて一時停止をしてご視聴ください。

## 📝 画面解説
メイン画面：Todo画面・習慣画面・体重管理画面へのリンク、登録した情報の簡易的な表示(目標体重や重要度の高いTodoを表示など)<br>
Todo画面：その日にこなすタスクの登録・編集・削除。期日、時間、重要度も設定可能。<br>
習慣画面：習慣にしたいことの登録、削除。チェックボックスで管理。(習慣づけたい繰り返し行うタスクを登録する 例：読書、ウォーキングなど)<br>
目標体重画面：目標体重を登録する。変更可能。<br>
体重管理画面：その日の体重を登録する。目標体重との差が出力される。

---

## 📁 チーム開発の経験（学校課題）
## 「チャットアプリ」
※本アプリの資料はありません。(一部コードのみ)
※画像と動画及び説明のみになりますので、学校での記録と思っていただけたらと思います

## 🔧 使用技術
- Java（Servlet, bean, DAO, model）
- JSP
- HTML / CSS（画面構成）
- Tomcat 9（ローカル実行）
- Eclipse（開発環境）

## 📃 アプリ説明
本アプリは、slackというアプリを参考にしたアプリです。4人で開発しました。自分たちの力でなるべく学校側から提示された課題、作業をこなしていきました。
- 4人で開発しました。フロントエンド2人、バックエンド2人
- 自分は主にバックエンドを担当しました。SQLをほとんど担当しました。
- エラー入力、空白入力のエラーの表示もしました。
- DBを使用したため、様々な情報の追加、削除、編集などができます。
- 絵文字での反応や、ルームへの参加など、slackにある機能を模倣しました。

## ✨ 頑張ったこと
4人での作業だったので、バックエンドに関する相談相手がいることが心強かったです。<br>
slackを参考にしていること、学校からの提示された課題があることでやるべきことが決まっていて、作成する機能に迷いはありませんでしたが、実際機能するものを作るのは難しかったです。<br>
初めてDBを繋いでアプリを作成したので、動きに慣れるまで時間がかかりました。テーブルの中身の入力などを間違えると機能しないため、何度もリセットする作業もしました。<br>
バックエンドの全体が機能しているかどうかを何度も確かめながら頑張りました。<br>
チームメンバーそれぞれが各機能の作成に着手していましたが、操作の都合上同じファイルを使用したいときがあったので、同じファイルを触ってしまわないように確認しながら作業していました。<br>


🖼️ **スクリーンショット**<br>

動画には載せていなかった部分の画像です。<br>

| 管理者画面１ | 管理者画面２ |
|--------------|-------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-AdminPage.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-AdminPage.png?raw=true" width="250"/></a> | <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-AdminPage2.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-AdminPage2.png?raw=true" width="250"/></a> |

| リアクション画面 | 新規登録画面 |
|-----------------|-------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-Reaction.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-Reaction.png?raw=true" width="250"/></a> | <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-SignUp.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-SignUp.png?raw=true" width="250"/></a> |

| アイコン登録画面 |
|----------------|
| <a href="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-Upload.png?raw=true"><img src="https://github.com/kuramoto-sae/portfolio/blob/main/images/Chat-Upload.png?raw=true" width="250"/></a> |

▶️ **動画リンク**<br>
https://drive.google.com/file/d/1kOmKVCzeXGl8jAaDrlp-kRiqgI2mQmX7/view?usp=sharing<br>
※本動画には細かな操作が含まれます。必要に応じて一時停止をしてご視聴ください。

## 📝 画面解説
管理者とは？→アプリ全体の管理者。ユーザーのアカウントをロック(凍結状態)、強制退会させることができる。<br>
管理者画面１：アカウントのロックリスト。ロックされたアカウントはログインできない。管理者はロック、ロック解除できる。(アカウントはDB上に存在する)<br>
管理者画面２：アカウントの強制退会リスト。登録されているアカウントを強制退会させることができる。強制退会させられたアカウントは削除される。(DB上からも削除)<br>
リアクション画面：それぞれのコメントの下にあるアイコンをクリックすると、リアクションができる。本アプリのリアクションは3種類。<br>
新規登録画面：ユーザー名、メールアドレス、パスワードを設定することでアカウントが登録できる。(DBに登録)<br>
アイコン登録画面：画像のファイルを選択し、送信ボタンを押すことでプロフィールにアイコンを登録することができる。

## 💻 コード(一部) 

私は主にバックエンドを担当していました。<br>
Servlet, bean, DAO, modelなどを書いていました。<br>
下記にチャットを削除するときのServletを載せています。<br>
それ以降、プルダウン式でチャット機能のコードを一部お見せしますので、興味がある方は見てみてください。

````markdown
```java
@WebServlet("/DeleteChatServlet")
public class DeleteChatServlet extends LoginCheckServlet {
	private static final long serialVersionUID = 1L;

	protected void doPost(HttpServletRequest request, HttpServletResponse response)
			throws ServletException, IOException {
		// TODO 必要な処理
		// 画面から取得
		String roomId = request.getParameter("roomId");
		String deleteChatLogId = request.getParameter("deleteChatLogId");
		System.out.println("ルームID:" + roomId + ",削除するチャットID:" + deleteChatLogId);

		// TODO DBからメッセージを削除する

		// GET処理にリダイレクト
		response.sendRedirect("MainServlet?roomId=" + roomId);
	}
}
````

<details>
  <summary>チャット機能(model)</summary>

```java
package model;

import java.util.ArrayList;
import java.util.List;

import bean.ChatLog;
import bean.Room;
import dao.ChatDAO;
import exception.SwackException;

/**
 * チャット機能を実行するクラス
 */
public class ChatModel {

	public Room getRoom(String roomId, String userId) throws SwackException {
		return new ChatDAO().getRoom(roomId, userId);
	}

	public ArrayList<Room> getRoomList(String userId) throws SwackException {
		return new ChatDAO().getRoomList(userId);
	}

	public ArrayList<Room> getDirectList(String userId) throws SwackException {
		return new ChatDAO().getDirectList(userId);
	}

	public List<ChatLog> getChatlogList(String roomId) throws SwackException {
		return new ChatDAO().getChatlogList(roomId);
	}

	public void saveChatLog(String roomId, String userId, String message) throws SwackException {
		new ChatDAO().saveChatlog(roomId, userId, message);
	}
}
```

</details>

<details>
  <summary>チャット機能(bean)</summary>

```java
package bean;

import java.io.Serializable;
import java.sql.Timestamp;

/**
 * チャットログ情報を管理するBean
 */
public class ChatLog implements Serializable {
	private static final long serialVersionUID = 1L;

	/** チャットログID */
	private int chatLogId;
	/** ルームID */
	private String roomId;
	/** ユーザID */
	private String userId;
	/** ユーザ名 */
	private String userName;
	/** メッセージ */
	private String message;
	/** 投稿日時 */
	private Timestamp createdAt;
	

	public ChatLog() {
		// for JSP
	}

	public ChatLog(int chatLogId, String roomId, String userId, String userName, String message, Timestamp createdAt) {
		this.chatLogId = chatLogId;
		this.roomId = roomId;
		this.userId = userId;
		this.userName = userName;
		this.message = message;
		this.createdAt = createdAt;
	}

	public int getChatLogId() {
		return chatLogId;
	}

	public String getRoomId() {
		return roomId;
	}

	public String getUserId() {
		return userId;
	}

	public String getUserName() {
		return userName;
	}

	public String getMessage() {
		return message;
	}

	public Timestamp getCreatedAt() {
		return createdAt;
	}
}
```

</details>




<details>
  <summary>チャット機能(DAO)</summary>

```java
package dao;

import static parameter.Messages.*;

import java.sql.Connection;
import java.sql.PreparedStatement;
import java.sql.ResultSet;
import java.sql.SQLException;
import java.sql.Timestamp;
import java.util.ArrayList;
import java.util.List;

import bean.ChatLog;
import bean.Room;
import exception.SwackException;

/**
 * チャット機能に関するDBアクセスを行う.
 */
public class ChatDAO extends BaseDAO {
	public ChatDAO() throws SwackException {
		super();
	}

	public List<ChatLog> getChatlogList(String roomId) throws SwackException {
		String sql = "SELECT CHATLOGID, U.USERID AS USERID, U.USERNAME AS USERNAME, MESSAGE, CREATED_AT "
				+ "FROM CHATLOG C JOIN USERS U ON C.USERID = U.USERID WHERE ROOMID = ? " + "ORDER BY CREATED_AT ASC";

		List<ChatLog> chatLogList = new ArrayList<ChatLog>();
		try (Connection conn = dataSource.getConnection()) {
			PreparedStatement pStmt = conn.prepareStatement(sql);
			pStmt.setString(1, roomId);

			ResultSet rs = pStmt.executeQuery();
			while (rs.next()) {
				int chatLogId = rs.getInt("CHATLOGID");
				String userId = rs.getString("USERID");
				String userName = rs.getString("USERNAME");
				String message = rs.getString("MESSAGE");
				Timestamp createdAt = rs.getTimestamp("CREATED_AT");

				ChatLog chatLog = new ChatLog(chatLogId, roomId, userId, userName, message, createdAt);
				chatLogList.add(chatLog);
			}
		} catch (SQLException e) {
			throw new SwackException(ERR_DB_PROCESS, e);
		}
		return chatLogList;
	}

	public Room getRoom(String roomId, String userId) throws SwackException {
		String sqlGetRoom = "SELECT R.ROOMID, R.ROOMNAME, COUNT(*) AS MEMBER_COUNT, R.DIRECTED"
				+ " FROM ROOMS R JOIN JOINROOM J ON R.ROOMID = J.ROOMID" + " WHERE R.ROOMID = ?"
				+ " GROUP BY R.ROOMID, R.ROOMNAME, R.DIRECTED";
		String sqlGetDirectRoom = "SELECT U.USERNAME AS ROOMNAME FROM JOINROOM R"
				+ " JOIN USERS U ON R.USERID = U.USERID" + " WHERE R.USERID <> ? AND ROOMID = ?";

		boolean directed = false;
		String roomName = "";
		int memberCount = 0;

		try (Connection conn = dataSource.getConnection()) {
			PreparedStatement pStmt = conn.prepareStatement(sqlGetRoom);
			pStmt.setString(1, roomId);
			ResultSet rs = pStmt.executeQuery();
			if (rs.next()) {
				directed = rs.getBoolean("DIRECTED");
				roomName = rs.getString("ROOMNAME");
				memberCount = rs.getInt("MEMBER_COUNT");
			}

			// for Direct
			if (directed) {
				PreparedStatement pStmt2 = conn.prepareStatement(sqlGetDirectRoom);
				pStmt2.setString(1, userId);
				pStmt2.setString(2, roomId);

				ResultSet rs2 = pStmt2.executeQuery();
				if (rs2.next()) {
					roomName = rs2.getString("ROOMNAME");
					memberCount = 2;
				}
			}
		} catch (SQLException e) {
			throw new SwackException(ERR_DB_PROCESS, e);
		}
		Room room = new Room(roomId, roomName, memberCount, directed);
		return room;
	}

	public ArrayList<Room> getRoomList(String userId) throws SwackException {
		String sql = "SELECT R.ROOMID, R.ROOMNAME FROM JOINROOM J JOIN ROOMS R ON J.ROOMID = R.ROOMID "
				+ "WHERE J.USERID = ? AND R.DIRECTED = FALSE ORDER BY R.ROOMNAME ASC";

		ArrayList<Room> roomlist = new ArrayList<Room>();

		try (Connection conn = dataSource.getConnection()) {
			PreparedStatement pst = conn.prepareStatement(sql);
			pst.setString(1, userId);

			ResultSet rs = pst.executeQuery();
			while (rs.next()) {
				String roomId = rs.getString("ROOMID");
				String roomName = rs.getString("ROOMNAME");
				roomlist.add(new Room(roomId, roomName));
			}

		} catch (Exception e) {
			throw new SwackException(ERR_DB_PROCESS, e);
		}

		return roomlist;

	}

	public ArrayList<Room> getDirectList(String userId) throws SwackException {
		String sql = "SELECT R.ROOMID, U.USERNAME AS ROOMNAME FROM JOINROOM R " + "JOIN USERS U ON R.USERID = U.USERID "
				+ "WHERE R.USERID <> ? AND ROOMID IN "
				+ "(SELECT R.ROOMID FROM JOINROOM J JOIN ROOMS R ON J.ROOMID = R.ROOMID "
				+ "WHERE J.USERID = ? AND R.DIRECTED = TRUE) " + "ORDER BY R.USERID";

		ArrayList<Room> roomlist = new ArrayList<Room>();

		try (Connection conn = dataSource.getConnection()) {
			PreparedStatement pst = conn.prepareStatement(sql);
			pst.setString(1, userId);
			pst.setString(2, userId);

			ResultSet rs = pst.executeQuery();
			while (rs.next()) {
				String roomId = rs.getString("ROOMID");
				String roomName = rs.getString("ROOMNAME");
				roomlist.add(new Room(roomId, roomName));
			}

		} catch (Exception e) {
			throw new SwackException(ERR_DB_PROCESS, e);
		}

		return roomlist;

	}

	public void saveChatlog(String roomId, String userId, String message) throws SwackException {
		String sql = "INSERT INTO CHATLOG (CHATLOGID, ROOMID, USERID, MESSAGE, CREATED_AT)"
				+ " VALUES (nextval('CHATLOGID_SEQ'), ?, ?, ?, CURRENT_TIMESTAMP)";

		try (Connection conn = dataSource.getConnection()) {
			PreparedStatement pStmt = conn.prepareStatement(sql);
			pStmt.setString(1, roomId);
			pStmt.setString(2, userId);
			pStmt.setString(3, message);

			pStmt.executeUpdate();
		} catch (SQLException e) {
			throw new SwackException(ERR_DB_PROCESS, e);
		}
	}

}
```

</details>


## 📌 最後に
ここまで見ていただきありがとうございます。<br>
自作アプリから学生時代の成果物を載せました。<br>
今回は完成版ではないコードもありますが、一部コードを掲載することで、設計や実装の理解度を見てもらえるようにしています。<br>
今後もさらに改善・挑戦を続け、より良いアプリを作っていきたいと考えています。





