# OCR Local 配置完成

## 状态
✅ ocr-local 已安装并启用
✅ tesseract.js 本地OCR引擎已安装
✅ 清理了之前的MiniMax-VL-01配置

## 识图方式
使用OCR进行图片文字识别，不再使用MiniMax-VL-01

## 命令
node skills/ocr-local/scripts/ocr.js <图片路径> --lang chi_sim+eng