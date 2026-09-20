# 66文明社、便利ツール

[ Language: [日本語](#日本語) | [English](#english) | [Русский](#русский) ]

---

## 日本語

### PrimitierTransistorCircuitSimulator
- プリミティアのトランジスタ回路の図面を作成して、ブラウザ上で動作確認できるツールです。
- **※本ツールは非公式（ファンメイド）の便利ツールであり、ゲーム開発元・公式とは関係ありません。**
- HTMLファイル単体で動作します。ネットワーク環境不要です。
- 実際にプリミティアで使うときは、作成した図面を見ながら手動で組み立てる必要があります。
- 動作確認環境: Windows 11 / Google Chrome

### 多言語対応 (i18n)
- 画面右上の言語切替セレクトボックス **`[ JA | EN | RU ]`** から、表示言語を「日本語」「英語」「ロシア語」に即座に切り替えることができます。
- ブラウザのデフォルト言語設定に応じて初期表示言語が自動選択されます。

### 基本操作
- **部品配置・移動:** 画面上部ボタンから追加、ドラッグで移動（10pxグリッド吸着）、範囲選択も可能
- **部品の左右反転:** 部品を選択して `R` キーを押すか、右クリックメニューから左右反転（in/outピンの位置入れ替え）
- **サイズ変更:** テキスト、黄鉄鉱、LEDは選択時に右下をドラッグしてサイズ変更が可能
- **配線接続:** ピン同士をドラッグして接続
- **中継ポイント:** 配線上をダブルクリックで折れ曲がり点追加 / ドラッグ移動 / 右クリックで削除
- **テキスト・水晶厚設定:** コンポーネントをダブルクリックで編集
- **シミュレーション制御:** 画面上部のバーから、再生/一時停止、シミュレーション速度の変更（0.1x 〜 2.0x）が可能
- **コマ送り（1チック）:** 「⏭ 1チック」ボタンで、時間を正確に0.1秒だけ進めて動作を確認
- **ファイルの保存・読込:** 「保存 (JSON)」で現在の回路をPCに保存し、「読み込み」でいつでも続きから再開可能
- **操作の取り消し・やり直し:** 回路の編集操作をいつでも `Ctrl + Z` で元に戻し、`Ctrl + Y` でやり直し可能
- **削除:** 部品・配線・中継ポイント上で右クリック（または選択してDelete / Backspace）
- **画面操作:** マウスホイールでズーム、中クリックドラッグ（または Space + 左ドラッグ）で画面移動

### ショートカットキー
- `1`〜`9`: 各種パーツをマウスカーソルの位置へ即座に配置
- `N`: シミュレーションを1チック（0.1秒）進める
- `Ctrl + Z` (Cmd + Z): 操作を元に戻す (Undo)
- `Ctrl + Y` (Cmd + Y) / `Ctrl + Shift + Z`: やり直す (Redo)
- `R`: 選択した部品の左右反転
- `Ctrl + C` (Cmd + C): 選択した回路のコピー
- `Ctrl + V` (Cmd + V): カーソル位置へのペースト、タブ間でのコピーも可能
- `Delete` / `Backspace`: 選択した部品の削除

---

## English

### PrimitierTransistorCircuitSimulator
- A browser-based simulator for designing and verifying transistor circuits in Primitier.
- ***Note: This is an unofficial fan-made tool and is not affiliated with the official game developers.**
- Runs as a standalone HTML file without an internet connection.
- When building in Primitier, you need to manually assemble the circuit while referencing the diagram.
- Tested Environment: Windows 11 / Google Chrome

### Multilingual Support (i18n)
- Switch UI languages between **Japanese, English, and Russian** instantly via the **`[ JA | EN | RU ]`** language dropdown in the top-right toolbar.
- Automatically selects the initial language based on your browser settings.

### Basic Controls
- **Place & Move Components:** Click toolbar buttons to add, drag to move (snaps to 10px grid). Area selection is supported.
- **Flip Component:** Select a component and press `R` key, or use the right-click menu to flip horizontally (swaps in/out pins).
- **Resize Components:** Text, Pyrite, and LED components can be resized by dragging the bottom-right corner when selected.
- **Wire Connection:** Drag between pins to connect.
- **Waypoints:** Double-click a wire to add a waypoint / drag to move / right-click to delete.
- **Text & Crystal Thickness:** Double-click a component to edit settings.
- **Simulation Control:** Play/Pause the simulation and change the execution speed (0.1x to 2.0x) via the toolbar.
- **1-Tick Step:** Use the "⏭ 1-Tick" button to advance the simulation by exactly 0.1 seconds.
- **Save & Load:** Save your current circuit to your PC as a JSON file, and load it anytime to resume.
- **Undo / Redo:** Easily undo changes with `Ctrl + Z` and redo with `Ctrl + Y`.
- **Delete:** Right-click a component, wire, or waypoint (or press Delete / Backspace when selected).
- **Canvas Control:** Mouse wheel to zoom, middle-click drag (or Space + Left-drag) to pan.

### Shortcuts
- `1` - `9`: Instantly place components at the mouse cursor position
- `N`: Step simulation forward by 1-Tick (0.1s)
- `Ctrl + Z` (Cmd + Z): Undo last action
- `Ctrl + Y` (Cmd + Y) / `Ctrl + Shift + Z`: Redo last action
- `R`: Flip selected component horizontally
- `Ctrl + C` (Cmd + C): Copy selected circuit
- `Ctrl + V` (Cmd + V): Paste at cursor position (supports copy-pasting across browser tabs)
- `Delete` / `Backspace`: Delete selected items

---

## Русский

### PrimitierTransistorCircuitSimulator
- Инструмент для проектирования и проверки транзисторных схем Primitier прямо в браузере.
- ***Примечание: Это неофициальный фанатский инструмент, который не связан с официальными разработчиками игры.**
- Работает как автономный HTML-файл без подключения к Интернету.
- При сборке в Primitier вам потребуется вручную собрать схему, ориентируясь на созданный чертеж.
- Протестировано в: Windows 11 / Google Chrome

### Многоязычная поддержка (i18n)
- Вы можете мгновенно переключать язык интерфейса между **японским, английским и русским** с помощью выпадающего списка **`[ JA | EN | RU ]`** в верхней панели инструментов.
- Язык по умолчанию выбирается автоматически в зависимости от настроек вашего браузера.

### Основное управление
- **Размещение и перемещение:** Добавление через верхние кнопки, перетаскивание с привязкой к сетке 10px. Поддерживается выделение области.
- **Отражение компонента:** Выделите компонент и нажмите клавишу `R` или используйте контекстное меню для отражения по горизонтали (меняет местами входы и выходы).
- **Изменение размера:** Для текста, пирита и светодиода можно менять размер, потянув за правый нижний угол выделенного элемента.
- **Соединение проводов:** Перетащите линию от одного пина к другому.
- **Точки изгиба (Waypoints):** Двойной клик по проводу для добавления / перетаскивание / правый клик для удаления.
- **Текст и толщина кристалла:** Двойной клик по компоненту для редактирования.
- **Управление симуляцией:** Запуск/Пауза и изменение скорости симуляции (от 0.1x до 2.0x) на панели инструментов.
- **Шаг 1 такт:** Кнопка "⏭ 1 такт" продвигает симуляцию ровно на 0.1 секунды.
- **Сохранение и загрузка:** Сохраняйте схему на ПК в формате JSON и загружайте для продолжения работы.
- **Отмена и повтор действий:** Отмена изменений комбинацией `Ctrl + Z`, повтор — `Ctrl + Y`.
- **Удаление:** Правый клик по компоненту, проводу или точке (либо клавиши Delete / Backspace для выделенного).
- **Навигация:** Колесо мыши для масштабирования, зажатие колесика (или Space + ЛКМ) для перемещения по холсту.

### Горячие клавиши
- `1` - `9`: Мгновенное добавление компонентов в позицию курсора мыши
- `N`: Продвинуть симуляцию на 1 такт (0.1с)
- `Ctrl + Z` (Cmd + Z): Отменить действие (Undo)
- `Ctrl + Y` (Cmd + Y) / `Ctrl + Shift + Z`: Повторить действие (Redo)
- `R`: Отразить выделенный компонент по горизонтали
- `Ctrl + C` (Cmd + C): Копировать выделенные элементы
- `Ctrl + V` (Cmd + V): Вставить в позиции курсора (работает между вкладками)
- `Delete` / `Backspace`: Удалить выделенные элементы

### 更新履歴 (Change Log)
- **v1.2.0** :(2026-09-19) 範囲選択、コピペ、電線の折り曲げ、ショートカットキー追加。オブジェクト構造強化。トリガー・黄鉄鉱・水晶・LEDのデザイン変更。シミュレーション速度調整機能、コマ送り（1チック）機能の追加。描画処理の高速化、テキストコンポーネントの画像読み込みロジックの最適化。古代の金属を追加。
- **v1.1.0**:(2026-09-16) 多言語対応(JA/EN/RU)
- **v1.0.0**:(2026-09-14) 初版
