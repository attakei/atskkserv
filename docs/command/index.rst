サブコマンド
============

atskkservではSKK辞書サーバーとして動作するために必要な機能を、
「サブコマンド」という形式で分割して提供しています。

共通のオプション
----------------

--log-level
  ログ出力時の最低レベルを指定します。
  次の8段階で指定が可能で、デフォルトでは ``NOTICE`` となっています。

  * TRACE
  * DEBUG
  * INFO
  * NOTICE
  * WARN
  * ERROR
  * FATAL
  * NONE

一覧
----

.. toctree::
   :maxdepth: 1
   :glob:

   *
