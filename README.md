# 👁️ ctOS Chat Control Interceptor & Profiler

An interactive, cyberpunk-styled desktop monitor emulator inspired by the **Watch Dogs (ctOS)** interface and the soundtrack of **Buckshot Roulette**. This mini-app was created in Python 3.10 as a creative response to the ongoing news about "Chat Control" mass surveillance legislation in the EU. 

> *"Big Brother is watching you — don't let him restrict your freedom."*

---

## ⚡ Features

* **5 Interactive Screens:** Switch seamlessly between tabs using keys `1`, `2`, `3`, `4`, `5`.
  1. **INTERCEPT:** View intercepted anti-government data locks (User 🔄 Anon).
  2. **LIVE SCAN:** Type any text in real-time. If you input flagged words (like *VPN, TG, privacy, freedom, EU*), the built-in AI scanner triggers a high-risk alarm state.
  3. **MANIFESTO:** A static cyberpunk protest screen dedicated to privacy.
  4. **PROFILER:** Press `R` to instantly scan the ctOS citizen database and generate random civilian profiles with risk assessments.
  5. **DATABASE:** A multi-page hacker database containing real articles and arguments against Chat Control (navigate via `Left/Right` arrow keys).
* **Retro CRT Shader:** Hardware-accelerated screen curvature distortion (barrel effect), neon glow, and raster scanlines built purely on NumPy and OpenCV without external game engines.
* **Audio Engine:** Programmatically synthesized custom low-volume keyboard clicks, AI sirens, and a dedicated `page_select.mp3` module for transition glitches.
* **Adaptive 2K Fullscreen:** Instantly queries your monitor info and scales smoothly into full-screen immersive mode.

---

## 🛠️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com
cd anti_eu_python
```

### 2. Unpack the project
Unzip the `ANTI EU.zip` archive into the repository root folder to get the source code (`ctos2.py`).

### 3. Install dependencies
Make sure you have Python 3.10+ installed. Then run:
```bash
pip install pygame opencv-python numpy
```

### 4. Audio files configuration
For the application to sound exactly as intended, place your audio files directly into the root folder next to `ctos2.py`:
* `bg_music.mp3` (Recommended: *Buckshot Roulette OST* by Mike Klubnika)
* `page_select.mp3` (Any glitch/static transition sound effect)

### 5. Run the app
```bash
python ctos2.py
```

---

## 🎮 Controls

* `1` - `5` : Switch between monitoring tabs.
* `R` : Scan next citizen (Only available on Screen 4: PROFILER).
* `Left` / `Right` Arrow Keys : Navigate through article pages (Only available on Screen 5: DATABASE).
* `Backspace` / `Return` : Edit text inside the live chat analyzer (Screen 2).
* `Esc` / `Alt + F4` : Safely exit the fullscreen app.

---

## ⚖️ Disclaimer & Context
This project is an artistic simulation and a political satire. It does not actually intercept or analyze real network data, nor does it communicate with any government entities. It serves as a visual commentary on the erosion of digital privacy rights.

---
---

# 👁️ ctOS Chat Control Interceptor & Profiler (На русском)

Интерактивный эмулятор монитора в стиле киберпанк, вдохновленный интерфейсом **Watch Dogs (ctOS)** и саундтреком **Buckshot Roulette**. Это мини-приложение написано на Python 3.10 как творческий ответ на непрекращающиеся новости о законе "Chat Control" (тотальной слежке за чатами) в Евросоюзе.

> *"Старший Брат следит за тобой — не позволяй ему ограничивать твою свободу."*

---

## ⚡ Функции

* **5 интерактивных экранов:** Плавное переключение между вкладками с помощью клавиш `1`, `2`, `3`, `4`, `5`.
  1. **INTERCEPT:** Просмотр перехваченных антиправительственных сообщений (User 🔄 Anon).
  2. **LIVE SCAN:** Ввод любого текста в реальном времени. Если вы вводите запрещенные слова (например, *VPN, TG, privacy, freedom, EU*), встроенный ИИ-сканер активирует режим критической тревоги.
  3. **MANIFESTO:** Статичный киберпанк-экран манифеста, посвященный цифровой приватности.
  4. **PROFILER:** Нажмите `R`, чтобы мгновенно просканировать базу данных граждан ctOS и сгенерировать случайные профили людей с оценкой их уровня угрозы.
  5. **DATABASE:** Многостраничная хакерская база данных, содержащая реальные статьи и аргументы правозащитников против Chat Control (навигация стрелками `Влево/Вправо`).
* **Ретро ЭЛТ-шейдер:** Аппаратно-ускоренное искажение геометрии экрана (эффект выпуклой бочки), неоновое свечение и растровые сканирующие линии (Scanlines), созданные чисто на NumPy и OpenCV без сторонних игровых движков.
* **Звуковой движок:** Программно синтезированные тихие щелчки клавиатуры, сирены ИИ и поддержка внешнего файла `page_select.mp3` для звукового сопровождения глитчей при переходах.
* **Адаптивный 2K Fullscreen:** Автоматически определяет разрешение вашего монитора и плавно разворачивает интерфейс на весь экран.

---

## 🛠️ Установка и настройка

### 1. Клонирование репозитория
```bash
git clone https://github.com
cd anti_eu_python
```

### 2. Распаковка проекта
Распакуйте ZIP-архив `ANTI EU.zip` в корневую папку репозитория, чтобы извлечь исходный код (`ctos2.py`).

### 3. Установка зависимостей
Убедитесь, что у вас установлен Python 3.10+. Затем выполните команду:
```bash
pip install pygame opencv-python numpy
```

### 4. Настройка аудиофайлов
Чтобы программа звучала именно так, как задумывалось, положите ваши аудиофайлы в корень папки рядом со скриптом `ctos2.py`:
* `bg_music.mp3` (Рекомендуется: трек из *Buckshot Roulette OST* от Mike Klubnika)
* `page_select.mp3` (Любой короткий звук помех/статики для перехода между страницами)

### 5. Запуск приложения
```bash
python ctos2.py
```

---

## 🎮 Управление

* `1` - `5` : Переключение между вкладками мониторинга.
* `R` : Сканировать следующего гражданина (доступно только на экране 4: PROFILER).
* Стрелки `Влево` / `Вправо` : Листать страницы статей (доступно только на экране 5: DATABASE).
* `Backspace` / `Return` : Редактировать текст внутри живого анализатора чата (экран 2).
* `Esc` / `Alt + F4` : Безопасный выход из полноэкранного режима.

---

## ⚖️ Дисклеймер и контекст
Данный проект является художественной симуляцией и политической сатирой. Он не перехватывает и не анализирует реальный сетевой трафик, а также не связывается с какими-либо государственными структурами. Скрипт служит исключительно визуальным комментарием к проблеме нарушения прав на цифровую конфиденциальность.
