# Diggerslife Chunk Format (or Diggerslife Chunk File) フォーマットについて

DCF フォーマットは、DiggersLife のチャンクをシリアライズしたバイナリフォーマットです。

チャンクについての詳しい説明は、[チャンク](chunk.md)をご確認ください。

## フォーマット

|型                 |バイト数|説明            |
|-------------------|------|---------------|
|"DCF"              |3     |マジックナンバー  |
|(short, byte)[4096]|12288 |ブロック+ステート |
