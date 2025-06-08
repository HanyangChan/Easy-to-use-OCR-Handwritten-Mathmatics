# Easy-to-use-OCR-Handwritten-Mathmatics

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Easy OCR Tool</title>
    <style>
        body { font-family: Arial, sans-serif; padding: 20px; }
        button { padding: 10px; cursor: pointer; margin-bottom: 20px; }
        .hidden { display: none; }
    </style>
</head>
<body>

<button onclick="toggleLanguage()">한국어</button>

<div id="english">
    <h1>Easy OCR Tool</h1>
    <p>This tool is designed to make Optical Character Recognition (OCR) easily accessible for everyone. With just a few clicks, you can convert images and scanned documents into editable text.</p>

    <h2>Features</h2>
    <ul>
        <li>Simple drag-and-drop interface</li>
        <li>Supports multiple image formats</li>
        <li>Quick and accurate text extraction</li>
    </ul>

    <h2>Getting Started</h2>
    <ol>
        <li>Upload or drag your image file.</li>
        <li>Click the OCR button.</li>
        <li>Download or copy the extracted text.</li>
    </ol>
</div>

<div id="korean" class="hidden">
    <h1>쉬운 OCR 도구</h1>
    <p>이 도구는 광학 문자 인식(OCR)을 누구나 쉽게 사용할 수 있도록 만들어졌습니다. 몇 번의 클릭만으로 이미지나 스캔된 문서를 편집 가능한 텍스트로 변환할 수 있습니다.</p>

    <h2>기능</h2>
    <ul>
        <li>간단한 드래그 앤 드롭 인터페이스</li>
        <li>다양한 이미지 형식 지원</li>
        <li>빠르고 정확한 텍스트 추출</li>
    </ul>

    <h2>시작하기</h2>
    <ol>
        <li>이미지 파일을 업로드하거나 드래그하세요.</li>
        <li>OCR 버튼을 클릭하세요.</li>
        <li>추출된 텍스트를 다운로드하거나 복사하세요.</li>
    </ol>
</div>

<script>
function toggleLanguage() {
    const english = document.getElementById('english');
    const korean = document.getElementById('korean');
    const button = document.querySelector('button');

    if (english.classList.contains('hidden')) {
        english.classList.remove('hidden');
        korean.classList.add('hidden');
        button.textContent = '한국어';
    } else {
        english.classList.add('hidden');
        korean.classList.remove('hidden');
        button.textContent = 'English';
    }
}
</script>

</body>
</html>
