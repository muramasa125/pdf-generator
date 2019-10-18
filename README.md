# pdf-generator
base64でエンコードされたPDFデータをファイル化するツールです。

テキストエリアに以下形式のJSONデータを入力して生成してください。

``
{
"pdfdata": base64encode_pdfdata_string,
"filename": output_filename
}
``
