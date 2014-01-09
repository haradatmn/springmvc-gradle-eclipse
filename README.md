Hello World SpringMVC with Gradle
=============

SpringMVC FrameWorkのHelloWorldです。  
Gradleプロジェクトを使用した、SpringMVCの導入に使用できます。

動作環境
------
確認済みの動作環境は以下になります。
* Eclipse 4.3.0
* EGit 2.2
* JAVA 1.6
* Spring 3.0.2.RELEASE

使い方
------

Eclipseへのプロジェクト作成方法は以下の通りです。

1. **Eclipseにインポートする**  
Eclipseのインポート機能から、「GITからプロジェクト」→「URI」を選択する。  
「ロケーション」にて、「https://github.com/tabris1298/boasting-test.git」を入力する。  
「ブランチ選択」にて、"master"を選択して、任意のローカルフォルダにGITリポジトリを作成する。  
最後に「既存プロジェクト」にてインポートする。（ここで、WorkSpaceにはコピーしないこと。）

2. **プロジェクト名を変更する**  
GITリポジトリには、.projectが同封されているため、プロジェクト名が「SpringMvcWithGradle01」となる。  
「リファクタ」→「リネーム」から好きなプロジェクト名に変更する。

3. **動的Webモジュールとコンテキストルートの指定**  
プロジェクトを右クリック→「プロジェクト・ファセット」を選択する。  
Java、動的Webモジュールにチェックを入れて、「より詳しい構成が使用可能」リンクを押下する。  
「ファセット・プロジェクトの変更」にて、デフォルト出力フォルダに「build/classes」を指定して、次へを押下。  
「コンテキストルート」→「src/main/webapp」を指定する。

4. **デプロイ**  
EclipseプラグインのWTP（Eclipse Web Tools Project）から、動作させる。（WTPはインストール済みとする。）  
ビューのサーバにプロジェクトを追加して、起動させる。

5. **動作確認**  
http://localhost:8080/SpringMvcWithGradle01/home  
にアクセスして  
ページに「Hello SpringMvcWithGradle!」が表示されれば成功です。







