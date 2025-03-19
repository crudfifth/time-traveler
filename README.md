# RedSpecter

**RedSpecter** は、セキュリティ研究およびペネトレーションテストのための攻撃ツール群。  
ネットワーク、Webアプリケーション、認証機構の脆弱性を検証し、防御戦略の向上を目的とする。  
**個人の学習・研究用途に限定** し、許可なく第三者のシステムに使用することは禁止されている。

## 機能一覧

### 1. **ネットワーク攻撃**
- **ポートスキャン**（カスタムNmap）
- **パケットスニッフィング**（ネットワークトラフィック解析）
- **ARPスプーフィング**（MITM攻撃のシミュレーション）
- **DNSスプーフィング**（悪意のあるリダイレクトのテスト）
- **ICMPトンネリング**（ファイアウォールの回避テスト）

### 2. **Webアプリケーション攻撃**
- **SQLインジェクション**（自動エクスプロイト）
- **XSS（クロスサイトスクリプティング）**（DOM/ストアド/リフレクテッド）
- **CSRF（クロスサイトリクエストフォージェリ）**（セッション乗っ取り）
- **ディレクトリトラバーサル**（非公開ファイルの探索）
- **サーバーサイドリクエストフォージェリ（SSRF）**（内部ネットワークの探索）

### 3. **認証・クラック**
- **ブルートフォース攻撃**（パスワードリスト攻撃）
- **辞書攻撃**（カスタムワードリスト対応）
- **ハッシュクラッキング**（MD5 / SHA1 / SHA256）
- **SSHブルートフォース**（認証突破のシミュレーション）
- **Wi-Fiクラッキング**（WPA/WPA2ハンドシェイク解析）

### 4. **エクスプロイトとポストエクスプロイト**
- **ローカル権限昇格**（脆弱な権限設定の検証）
- **リモートコード実行（RCE）**（特定の脆弱性を利用）
- **バックドアの埋め込み**（ポストエクスプロイト戦略）
- **C2フレームワーク**（リモートコントロールの概念検証）

### 5. **DDoS（分散型サービス拒否攻撃）**
- **SYNフラッディング**（TCP接続の飽和攻撃）
- **UDPフラッディング**（帯域幅の消費）
- **HTTPフラッド**（アプリケーションレイヤー攻撃）
- **DNSリフレクション**（アンプ攻撃の検証）

## 技術スタック
- **Python**: Scapy, Requests, Paramiko, BeautifulSoup
- **Rust**: 高速なパケット処理
- **Go**: 並列処理を活用した攻撃モジュール
- **Bash**: OSコマンドベースのエクスプロイト
- **Docker**: テスト環境のコンテナ化

## 開発環境
- **OS**: Kali Linux / Ubuntu / Windows（WSL2推奨）
- **仮想環境**: VirtualBox / Docker
- **ネットワーク分析**: Wireshark / tcpdump
- **デバッグツール**: GDB / strace / lsof

## 注意事項
本ツールは教育目的および個人の研究用途に限定されています。  
不正アクセス禁止法等の法令を遵守し、**許可のないシステムへの使用は禁止** です。

