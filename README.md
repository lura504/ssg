# pt-BR
## Shuusou Gyoku

### O que é?
* Este é o código fonte para Shuusou Gyoku, o primeiro lançamento do **Nishikata Project**;
* Ele pode compilar, mas nem todo código fonte está incluso, portanto ele não pode ser linkado;
* Imagens, músicas, efeitos sonoros, scripts e outros recursos não inclusos.


### De Referência
* Basicamente, isso é o mesmo que quando foi desenvolvido (por volta dos anos 2000), mas a codificação de caracteres foi alterada para UTF-8 e alguns comentários (poemas sombrios históricos?) foram deletados. Indentação e outras coisas são as mesmos que antigamente, então algumas partes podem ser difíceis de ler.
* A mistura de cores 8/16 bit, reprodução MIDI e evitar cálculos de ponto flutuante provavelmente são alguns pontos nostálgicos.
* Existem vários nomes de arquivos no formato 8.3 pois parte do código foi escrito na época que PC-98 era usado.
* O código relacionado com expansão de recursos de arquivos não está incluso neste repositório devido a vários motivos.


### Estrutura de Pastas
* /**MAIN**		: Shuusou Gyoku WinMain
* /**GIAN07**		: função main() de Shuusou Gyoku 
* /**DirectXUTYs**	: DirectX, Reprodutor MIDI, funções matemáticas de processamento comuns, etc…
* /**MapEdit2**		: Editor de Mapa
* /**ECLC**		: Compilador do script ECL(para controle de inimigos)
* /**SCLC**		: Compilador do script SCL(para posicionamento de inimigos)


### Código fonte que pode ter sido perdido
O código à seguir será adicionado assim que for encontrado.
* Arquivador de Recursos


### Licensa
* [MIT](LICENSE)
---
# jp
## 秋霜玉

### これは何？
* 西方プロジェクト第一弾 **秋霜玉** のソースコードです。
* コンパイルできるかもしれませんが, すべてのソースコードが含まれているわけではないのでリンクはできません。
* 画像、音楽、効果音、スクリプト等のリソースは含まれません。


### 参考までに
* 基本、開発当時（2000年前後）のままですが、文字コードを utf-8 に変更し、一部コメント（黒歴史ポエム）は削除してあります。インデント等も当時のままなので、読みにくい箇所があるかもしれません。
* 8bit/16bitカラーの混在、MIDI再生関連、浮動小数点数演算を避ける、あたりが懐かしポイントになるかと思います。
* 8.3形式のファイル名が多いのは、PC-98 時代に書いたコードの一部を流用していたためです。
* リソースのアーカイブ展開に関するコードはもろもろの影響を考え、このリポジトリには含めていません。


### ディレクトリ構成
* /**MAIN** : 秋霜玉WinMainあたり
* /**GIAN07** : 秋霜玉本体
* /**DirectXUTYs** : DirectX, MIDI再生、数学関数等の共通処理
* /**MapEdit2** : マップエディタ
* /**ECLC** : ECL(敵制御用) スクリプトコンパイラ
* /**SCLC** : SCL(敵配置用) スクリプトコンパイラ


### たぶん紛失してしまったソースコード
以下のコードについては、見つかり次第追加するかもしれません。
* リソースのアーカイバ


### ライセンス
* [MIT](LICENSE)
