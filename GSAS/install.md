---
content: "# content"
---
# Install

## Install

現在のinstall siteは <https://subversion.xray.aps.anl.gov/trac/EXPGUI/wiki/InstallWindows> になっています。多くのダミーサイトに注意。

・普通はOption 1から

<https://subversion.xray.aps.anl.gov/EXPGUI/install/SetupGSAS_EXPGUI.exe>

を選択

重要！！！

・ダウンロードしたファイルは、右クリック　⇒　管理者として実行

2017/10/16

以下、少し古い情報

・DOS窓が出てきて、何かキーを押せというので、何か押す

以下のようなメッセージが出てきたら、証明書の確認なので、’’p"を押す

`C:\gsas>.\svn\bin\svn co https://subversion.xor.aps.anl.gov/EXPGUI/gsas/all .`

`Error validating server certificate for 'https://subversion.xor.aps.anl.gov:443'`

`:`

`- The certificate is not issued by a trusted authority. Use the`

`fingerprint to validate the certificate manually!`

`Certificate information:`

`- Hostname: subversion`

`- Valid: from Tue, 28 Aug 2012 15:00:00 GMT until Sat, 30 Aug 2014 14:59:59 GMT`

``\
`- Issuer: Terms of use at https://www.verisign.com/rpa (c)10, VeriSign Trust Ne`

`twork, VeriSign, Inc., US`

`- Fingerprint: 50:87:14:3e:23:4e:9f:5d:8f:37:3c:22:0a:0a:34:62:95:4f:07:f2`

`(R)eject, accept (t)emporarily or accept (p)ermanently? p`

・３分ほど待つ（DOS上に’続行するには何かキーを押してください、と出るまで）

・最後にexpguiが起動したらOK

Macの場合

https://subversion.xor.aps.anl.gov/trac/EXPGUI/wiki/InstallOSX

からHow to install non-updating GSAS & EXPGUIにしたがってインストール