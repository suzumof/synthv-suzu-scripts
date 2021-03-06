
----------------------------------------------------------------

Synthesizer V Studio 用のスクリプト集。

製作者名  ：スズモフ
バージョン：1.0.8
更新日    ：2020/10/11

https://twitter.com/suzu_dov

----------------------------------------------------------------



【はじめに】

Synthesizer V Studio で利用可能な自作のスクリプト集です。



【インストール方法】

Synthesizer V Studio のスクリプトフォルダに利用するスクリプトファイルを
コピーまたは移動してください。

その後、本体のスクリプトメニューから再スキャンを選ぶとそのスクリプトが
利用可能になります。



【収録スクリプトの紹介】

・playback/RepeatPlayOfCurrentPhrase.js
  フレーズのリピート再生
  現在の再生位置に一番近いフレーズをリピート再生します。
  ノート間に隙間があったら別のフレーズとして扱います。

・playback/RepeatPlayOfNextPhrase.js
  次のフレーズのリピート再生
  現在の再生位置からその一つ次のフレーズをリピート再生します。
  
・playback/RepeatPlayOfPrevPhrase.js
  前のフレーズのリピート再生
  現在の再生位置からその一つ前のフレーズをリピート再生します。
  
・playback/RepeatPlayOfSelectedNotes.js
  選択範囲のリピート再生
  現在選択中のノートやグループの置かれている範囲をリピート再生します。

・editNote/FilterNoteWithMultiplePhonemes.js
  選択ノートを複数音素で絞り込み
  現在選択中のノートで複数の音素を含むものだけを絞り込んで再選択します。
  日本語の歌声データベース以外では正常に動作しない可能性があります。

・editNote/FilterNoteWithSinglePhoneme.js
  選択ノートを単一音素で絞り込み
  現在選択中のノートで単一の音素を含むものだけを絞り込んで再選択します。
  日本語の歌声データベース以外では正常に動作しない可能性があります。

・editNote/SelectNextNote.js
  次のノートを選択
  現在選択中のノートの直後のノートを選択します。
  編集中以外のグループに含まれるノートは選択対象になりません。

・editNote/SelectPrevNote.js
  前のノートを選択
  現在選択中のノートの直前のノートを選択します。
  編集中以外のグループに含まれるノートは選択対象になりません。

・editNote/SetConsonantPhonemeDuration.js
  子音の長さ設定
  現在選択されているノートやグループの子音の長さを-160から+160の範囲で設定します。
  -80から+80の範囲を超える場合は直前のノートに置かれている母音の長さも変えます。
  もし複数のノートが選択されている場合は一括で変更します。

・editNote/SetFirstPhonemeDuration.js
  先頭音素の長さ設定
  現在選択されているノートやグループの先頭音素の長さを設定します。
  もし複数のノートが選択されている場合は一括で変更します。

・editNote/PackParameterToGroup.js
  パラメータをグループ内に移す
  現在選択されているグループの外側に設定されているパラメータを、
  グループ内に移します。
  ノートとパラメータをまとめて移動・コピーしたい時に役立ちます。

・editNote/CopyTrack.js
  現在選択中のトラックを複製します。



【動作環境】

Windows版のSynthesizer V Studio Ver.1.0.8で動作確認しています。
バージョンの違いによってスクリプトの互換性が無くなる可能性があります。

また、スクリプトの利用によってエラーなどのトラブルが起こる可能性もある為、
事前にプロジェクトファイルの保存を行っておく事をお勧めします。



【注意事項】

・このスクリプトの利用は自己責任でお願いします。

・このスクリプトの利用によって起きた問題については、
  SynthesizerVの開発元や販売元にはお問い合わせを行わないようにお願いします。


もし不具合などがあれば下記のいずれかの場所からご連絡下さい。



【連絡先】

Twitter
https://twitter.com/suzu_dov

メールアドレス (反応遅め)
su_zu_mof@hotmail.com



【更新履歴】


2020/10/11　ver.1.0.8

・FitNoteEdgeToPlayhead.jsを追加。
・UpSelectingNotePitch.jsを追加。
・DownSelectingNotePitch.jsを追加。


2020/9/25　ver.1.0.7

・SetConsonantPhonemeDuration.jsを追加。


2020/9/20　ver.1.0.6

・「パラメータをグループ内に移す」のスクリプトにおいて、
　ビブラートエンベロープと無声/有声音のパラメータを正しく扱えていなかったのを修正しました。


2020/9/9　ver.1.0.5

・PackParameterToGroup.jsを追加。
・CopyTrack.jsを追加。
・本体のアップデートに合わせて説明文を一部修正。


2020/8/23　ver.1.0.1

・一部スクリプトで再生停止時に音がプツッと途切れて聞こえる問題を修正。
・空のグループが存在する場合にエラーを起こす問題を修正。


2020/8/22　ver.1.0.0

・初版公開



----------------------------------------------------------------

Copyright (c) 2020 スズモフ
Released under the MIT license
https://opensource.org/licenses/mit-license.php


