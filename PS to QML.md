---


---

<ul>
<li></li>
</ul>
<h2 id="Перевод-psd-в-qml-для-qt-creator">Перевод PSD файл (Photoshop) в QML (для Qt Creator)</h2>
<ul>
<li></li>
</ul>
<p>Для правильного создания <strong>ui</strong> в Photoshop для QML, нам понадобиться правильное распределение слоев. Где каждый слой/папка это отдельный фрагмент в <em>'.qml</em>’.</p>
<p><img src="https://i.imgur.com/CGkBebD.png" alt="Layers"></p>
<p>С помощью скрипта <em>“<a href="https://github.com/qt-labs/photoshop-qmlexporter">photoshop-qmlexporter</a>”</em>, экспортируем psd в qml.</p>
<p>Скрипт (<strong>.jsx</strong> файл) устаналиваем в папку <strong><em>\Adobe\Adobe Photoshop CC 2018\Presets\Scripts</em></strong>.<br>
Открываем наш готовый psd файл, заходим в <strong><em>Файл-&gt;Сценарии-&gt;Export QML</em></strong> (Files-&gt;Scripts-&gt;Export QML).<br>
Готово. На выходе получаем обычный .qml файл который можно открыть в Qt Creator</p>
<p><img src="https://i.imgur.com/ED1P6l3.png" alt="Qt Creator"></p>
<p>И вот все наши “слои” с которыми мы можем взаимодействовать.</p>
<p><img src="https://i.imgur.com/4L7hw11.png" alt="Слои"></p>

