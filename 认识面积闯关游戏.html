<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>面积大冒险 - 三年级数学</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Microsoft YaHei', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* 欢迎界面 */
        .welcome-screen {
            text-align: center;
            padding: 50px 20px;
        }

        .game-title {
            font-size: 3.5em;
            color: #fff;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.3);
            margin-bottom: 20px;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
        }

        .mascot {
            font-size: 120px;
            margin: 30px 0;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0) rotate(-5deg); }
            50% { transform: translateY(-20px) rotate(5deg); }
        }

        .subtitle {
            font-size: 1.5em;
            color: #ffeaa7;
            margin-bottom: 40px;
        }

        .start-btn {
            background: linear-gradient(45deg, #f39c12, #e74c3c);
            border: none;
            padding: 20px 60px;
            font-size: 1.8em;
            color: white;
            border-radius: 50px;
            cursor: pointer;
            box-shadow: 0 8px 20px rgba(0,0,0,0.3);
            transition: all 0.3s;
        }

        .start-btn:hover {
            transform: scale(1.1);
            box-shadow: 0 12px 30px rgba(0,0,0,0.4);
        }

        .stats-bar {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin: 30px 0;
        }

        .stat-item {
            background: rgba(255,255,255,0.2);
            padding: 15px 30px;
            border-radius: 20px;
            color: white;
            font-size: 1.2em;
        }

        .stat-item span {
            font-size: 1.5em;
            font-weight: bold;
            color: #ffeaa7;
        }

        /* 关卡选择 */
        .level-select {
            display: none;
            padding: 30px;
        }

        .level-select h2 {
            color: white;
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 30px;
        }

        .levels-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
            max-width: 900px;
            margin: 0 auto;
        }

        .level-card {
            background: white;
            border-radius: 20px;
            padding: 30px;
            text-align: center;
            cursor: pointer;
            transition: all 0.3s;
            position: relative;
            overflow: hidden;
        }

        .level-card:hover:not(.locked) {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.3);
        }

        .level-card.locked {
            opacity: 0.6;
            cursor: not-allowed;
        }

        .level-card.locked::after {
            content: '🔒';
            position: absolute;
            font-size: 50px;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .level-card.completed {
            border: 4px solid #2ecc71;
        }

        .level-card.completed::before {
            content: '✅';
            position: absolute;
            top: 10px;
            right: 10px;
            font-size: 30px;
        }

        .level-icon {
            font-size: 60px;
            margin-bottom: 15px;
        }

        .level-name {
            font-size: 1.4em;
            color: #333;
            margin-bottom: 10px;
        }

        .level-desc {
            font-size: 0.9em;
            color: #666;
        }

        .level-stars {
            margin-top: 10px;
            font-size: 24px;
        }

        /* 游戏区域 */
        .game-screen {
            display: none;
            background: white;
            border-radius: 30px;
            padding: 30px;
            margin-top: 20px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
            min-height: 500px;
        }

        .game-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 3px solid #eee;
        }

        .game-title-small {
            font-size: 1.5em;
            color: #667eea;
        }

        .game-score {
            background: linear-gradient(45deg, #f39c12, #e74c3c);
            color: white;
            padding: 10px 25px;
            border-radius: 25px;
            font-size: 1.2em;
        }

        .back-btn {
            background: #95a5a6;
            border: none;
            padding: 10px 20px;
            color: white;
            border-radius: 10px;
            cursor: pointer;
            font-size: 1em;
            transition: all 0.3s;
        }

        .back-btn:hover {
            background: #7f8c8d;
            transform: scale(1.05);
        }

        /* 概念动画区 */
        .concept-area {
            text-align: center;
            padding: 20px;
        }

        .concept-animation {
            position: relative;
            width: 400px;
            height: 300px;
            margin: 20px auto;
            background: #f0f0f0;
            border-radius: 20px;
            overflow: hidden;
        }

        .ground {
            position: absolute;
            bottom: 0;
            width: 100%;
            height: 150px;
            background: #27ae60;
        }

        .house {
            position: absolute;
            bottom: 150px;
            left: 50%;
            transform: translateX(-50%);
        }

        .house-body {
            width: 120px;
            height: 80px;
            background: #e74c3c;
            position: relative;
        }

        .house-roof {
            width: 0;
            height: 0;
            border-left: 80px solid transparent;
            border-right: 80px solid transparent;
            border-bottom: 60px solid #c0392b;
            position: absolute;
            top: -60px;
            left: -20px;
        }

        .house-door {
            width: 30px;
            height: 50px;
            background: #f39c12;
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
        }

        .house-window {
            width: 25px;
            height: 25px;
            background: #3498db;
            position: absolute;
            top: 15px;
            border-radius: 3px;
        }

        .house-window.left { left: 15px; }
        .house-window.right { right: 15px; }

        .grass-tile {
            display: inline-block;
            width: 30px;
            height: 30px;
            background: #2ecc71;
            border: 1px solid #27ae60;
            position: absolute;
            font-size: 12px;
            color: #27ae60;
            text-align: center;
            line-height: 30px;
            transition: all 0.5s;
        }

        .area-text {
            font-size: 2em;
            color: #667eea;
            margin: 20px 0;
            animation: pulse 1.5s infinite;
        }

        @keyframes pulse {
            0%, 100% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.1); opacity: 0.8; }
        }

        .concept-tip {
            font-size: 1.3em;
            color: #555;
            margin-top: 20px;
            padding: 15px;
            background: #f8f9fa;
            border-radius: 15px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        /* 方格练习 */
        .grid-exercise {
            text-align: center;
            padding: 20px;
        }

        .exercise-instruction {
            font-size: 1.4em;
            color: #333;
            margin-bottom: 20px;
        }

        .grid-container {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }

        .grid-area {
            display: grid;
            gap: 2px;
            background: #ddd;
            padding: 2px;
            border-radius: 10px;
        }

        .grid-cell {
            width: 50px;
            height: 50px;
            background: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2em;
            color: #aaa;
            transition: all 0.3s;
            cursor: pointer;
        }

        .grid-cell.highlight {
            background: #74b9ff;
            color: white;
        }

        .grid-cell.filled {
            background: #0984e3;
            color: white;
            animation: fillPop 0.3s;
        }

        @keyframes fillPop {
            0% { transform: scale(0.8); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }

        .grid-cell.wrong {
            background: #ff7675;
            animation: shake 0.5s;
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            75% { transform: translateX(5px); }
        }

        .tile-source {
            display: flex;
            flex-direction: column;
            gap: 10px;
            padding: 20px;
            background: #f8f9fa;
            border-radius: 15px;
        }

        .draggable-tile {
            width: 50px;
            height: 50px;
            background: #0984e3;
            border-radius: 8px;
            cursor: grab;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.5em;
            transition: all 0.3s;
            user-select: none;
        }

        .draggable-tile:hover {
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }

        .draggable-tile:active {
            cursor: grabbing;
        }

        .draggable-tile.used {
            opacity: 0.3;
            pointer-events: none;
        }

        .answer-section {
            margin-top: 30px;
        }

        .answer-input {
            font-size: 1.5em;
            padding: 10px 20px;
            border: 3px solid #667eea;
            border-radius: 10px;
            width: 150px;
            text-align: center;
        }

        .submit-btn {
            background: #667eea;
            border: none;
            padding: 12px 30px;
            color: white;
            font-size: 1.2em;
            border-radius: 10px;
            cursor: pointer;
            margin-left: 15px;
            transition: all 0.3s;
        }

        .submit-btn:hover {
            background: #5568d3;
            transform: scale(1.05);
        }

        .feedback {
            font-size: 1.5em;
            margin-top: 20px;
            padding: 15px;
            border-radius: 15px;
            display: none;
        }

        .feedback.correct {
            background: #d4edda;
            color: #155724;
            display: block;
            animation: popIn 0.5s;
        }

        .feedback.incorrect {
            background: #f8d7da;
            color: #721c24;
            display: block;
            animation: popIn 0.5s;
        }

        @keyframes popIn {
            0% { transform: scale(0.5); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        /* 公式关卡 */
        .formula-area {
            text-align: center;
            padding: 20px;
        }

        .formula-display {
            background: linear-gradient(135deg, #667eea, #764ba2);
            padding: 40px;
            border-radius: 20px;
            color: white;
            margin: 20px auto;
            max-width: 500px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
        }

        .formula-text {
            font-size: 2.5em;
            font-weight: bold;
            margin: 20px 0;
        }

        .formula-visual {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 20px;
            margin: 30px 0;
        }

        .rectangle-demo {
            position: relative;
        }

        .rect-demo-body {
            background: rgba(255,255,255,0.3);
            border: 3px solid white;
            display: grid;
            gap: 2px;
            padding: 5px;
        }

        .rect-demo-cell {
            width: 40px;
            height: 40px;
            background: rgba(255,255,255,0.5);
        }

        .dimension-label {
            position: absolute;
            font-size: 1.2em;
            font-weight: bold;
            color: #ffeaa7;
        }

        .dimension-label.length {
            bottom: -30px;
            left: 50%;
            transform: translateX(-50%);
        }

        .dimension-label.width {
            left: -40px;
            top: 50%;
            transform: translateY(-50%) rotate(-90deg);
        }

        .formula-examples {
            margin-top: 30px;
        }

        .example-item {
            background: rgba(255,255,255,0.1);
            padding: 15px 25px;
            margin: 10px 0;
            border-radius: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .example-calc {
            font-size: 1.3em;
        }

        .example-result {
            background: #f39c12;
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: bold;
        }

        /* 挑战关卡 */
        .challenge-area {
            text-align: center;
            padding: 20px;
        }

        .challenge-question {
            font-size: 1.6em;
            color: #333;
            margin-bottom: 30px;
        }

        .shape-display {
            margin: 20px auto;
            position: relative;
        }

        .shape-rect {
            background: #74b9ff;
            border: 3px solid #0984e3;
            margin: 0 auto;
        }

        .shape-square {
            background: #55efc4;
            border: 3px solid #00b894;
        }

        .shape-label {
            margin-top: 15px;
            font-size: 1.2em;
            color: #666;
        }

        .multiple-choice {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
            margin-top: 30px;
        }

        .choice-btn {
            background: white;
            border: 3px solid #667eea;
            padding: 15px 30px;
            font-size: 1.3em;
            border-radius: 15px;
            cursor: pointer;
            transition: all 0.3s;
            min-width: 100px;
        }

        .choice-btn:hover {
            background: #667eea;
            color: white;
            transform: scale(1.05);
        }

        .choice-btn.correct {
            background: #2ecc71;
            border-color: #27ae60;
            color: white;
            animation: correctPulse 0.5s;
        }

        .choice-btn.incorrect {
            background: #e74c3c;
            border-color: #c0392b;
            color: white;
            animation: shake 0.5s;
        }

        @keyframes correctPulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }

        /* 成就弹窗 */
        .achievement-popup {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) scale(0);
            background: linear-gradient(135deg, #f39c12, #e74c3c);
            padding: 40px;
            border-radius: 30px;
            text-align: center;
            color: white;
            z-index: 1000;
            box-shadow: 0 20px 60px rgba(0,0,0,0.5);
            transition: transform 0.5s;
        }

        .achievement-popup.show {
            transform: translate(-50%, -50%) scale(1);
        }

        .achievement-icon {
            font-size: 80px;
            margin-bottom: 20px;
            animation: bounce 1s infinite;
        }

        .achievement-title {
            font-size: 2em;
            margin-bottom: 10px;
        }

        .achievement-desc {
            font-size: 1.2em;
            opacity: 0.9;
        }

        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
            z-index: 999;
            display: none;
        }

        .overlay.show {
            display: block;
        }

        /* 星星动画 */
        .stars-animation {
            position: fixed;
            pointer-events: none;
            z-index: 1001;
        }

        .star {
            position: absolute;
            font-size: 30px;
            animation: starFall 1s forwards;
        }

        @keyframes starFall {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(100px) rotate(360deg); opacity: 0; }
        }

        /* 进度条 */
        .progress-bar {
            width: 100%;
            height: 10px;
            background: #eee;
            border-radius: 5px;
            margin: 20px 0;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #667eea, #764ba2);
            border-radius: 5px;
            transition: width 0.5s;
        }

        /* 响应式 */
        @media (max-width: 768px) {
            .game-title { font-size: 2.5em; }
            .mascot { font-size: 80px; }
            .stats-bar { flex-direction: column; gap: 15px; }
            .grid-cell { width: 40px; height: 40px; }
            .draggable-tile { width: 40px; height: 40px; }
            .concept-animation { width: 300px; height: 220px; }
            .formula-text { font-size: 1.8em; }
            .choice-btn { padding: 10px 20px; font-size: 1.1em; }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 欢迎界面 -->
        <div class="welcome-screen" id="welcomeScreen">
            <h1 class="game-title">面积大冒险</h1>
            <div class="mascot">🎮</div>
            <p class="subtitle">一起探索面积的奥秘吧！</p>
            <div class="stats-bar">
                <div class="stat-item">⭐ 积分: <span id="totalScore">0</span></div>
                <div class="stat-item">🏆 关卡: <span id="completedLevels">0</span>/5</div>
                <div class="stat-item">🎖️ 成就: <span id="achievements">0</span></div>
            </div>
            <button class="start-btn" onclick="showLevelSelect()">开始冒险！</button>
        </div>

        <!-- 关卡选择 -->
        <div class="level-select" id="levelSelect">
            <h2>选择关卡</h2>
            <div class="levels-grid" id="levelsGrid"></div>
            <button class="back-btn" onclick="showWelcome()" style="margin-top: 30px;">返回</button>
        </div>

        <!-- 游戏区域 -->
        <div class="game-screen" id="gameScreen">
            <div class="game-header">
                <button class="back-btn" onclick="showLevelSelect()">返回</button>
                <span class="game-title-small" id="gameTitle">关卡 1</span>
                <span class="game-score">⭐ <span id="currentScore">0</span></span>
            </div>
            <div id="gameContent"></div>
        </div>

        <!-- 成就弹窗 -->
        <div class="overlay" id="overlay"></div>
        <div class="achievement-popup" id="achievementPopup">
            <div class="achievement-icon" id="achievementIcon">🎉</div>
            <div class="achievement-title" id="achievementTitle">恭喜过关！</div>
            <div class="achievement-desc" id="achievementDesc">获得 100 积分！</div>
        </div>
    </div>

    <script>
        // 游戏数据
        const gameData = {
            totalScore: parseInt(localStorage.getItem('areaGameScore')) || 0,
            completedLevels: JSON.parse(localStorage.getItem('areaGameCompleted')) || [],
            achievements: JSON.parse(localStorage.getItem('areaGameAchievements')) || []
        };

        const levels = [
            {
                id: 1,
                name: '认识面积',
                desc: '什么是面积？',
                icon: '📐',
                unlocked: true,
                stars: 0
            },
            {
                id: 2,
                name: '方格计数',
                desc: '数方格算面积',
                icon: '🟦',
                unlocked: false,
                stars: 0
            },
            {
                id: 3,
                name: '公式学习',
                desc: '长方形面积公式',
                icon: '📝',
                unlocked: false,
                stars: 0
            },
            {
                id: 4,
                name: '矩形挑战',
                desc: '计算矩形面积',
                icon: '⬜',
                unlocked: false,
                stars: 0
            },
            {
                id: 5,
                name: '综合挑战',
                desc: '各种图形面积',
                icon: '🏆',
                unlocked: false,
                stars: 0
            }
        ];

        // 初始化
        function init() {
            updateStats();
            renderLevels();
        }

        function updateStats() {
            document.getElementById('totalScore').textContent = gameData.totalScore;
            document.getElementById('completedLevels').textContent = gameData.completedLevels.length;
            document.getElementById('achievements').textContent = gameData.achievements.length;
        }

        function saveProgress() {
            localStorage.setItem('areaGameScore', gameData.totalScore);
            localStorage.setItem('areaGameCompleted', JSON.stringify(gameData.completedLevels));
            localStorage.setItem('areaGameAchievements', JSON.stringify(gameData.achievements));
        }

        function renderLevels() {
            const grid = document.getElementById('levelsGrid');
            grid.innerHTML = '';

            levels.forEach((level, index) => {
                // 检查是否解锁
                if (index > 0 && !gameData.completedLevels.includes(levels[index - 1].id)) {
                    level.unlocked = false;
                } else if (gameData.completedLevels.includes(level.id)) {
                    level.unlocked = true;
                } else if (index === 0 || gameData.completedLevels.includes(levels[index - 1].id)) {
                    level.unlocked = true;
                }

                const card = document.createElement('div');
                card.className = `level-card ${!level.unlocked ? 'locked' : ''} ${gameData.completedLevels.includes(level.id) ? 'completed' : ''}`;
                card.innerHTML = `
                    <div class="level-icon">${level.icon}</div>
                    <div class="level-name">关卡 ${level.id}: ${level.name}</div>
                    <div class="level-desc">${level.desc}</div>
                    ${level.unlocked ? getStarsHTML(level.stars) : ''}
                `;

                if (level.unlocked) {
                    card.onclick = () => startLevel(level.id);
                }

                grid.appendChild(card);
            });
        }

        function getStarsHTML(count) {
            return `<div class="level-stars">${'⭐'.repeat(count)}${'☆'.repeat(3-count)}</div>`;
        }

        function showWelcome() {
            document.getElementById('welcomeScreen').style.display = 'block';
            document.getElementById('levelSelect').style.display = 'none';
            document.getElementById('gameScreen').style.display = 'none';
        }

        function showLevelSelect() {
            document.getElementById('welcomeScreen').style.display = 'none';
            document.getElementById('levelSelect').style.display = 'block';
            document.getElementById('gameScreen').style.display = 'none';
            renderLevels();
        }

        function startLevel(levelId) {
            document.getElementById('welcomeScreen').style.display = 'none';
            document.getElementById('levelSelect').style.display = 'none';
            document.getElementById('gameScreen').style.display = 'block';
            document.getElementById('gameTitle').textContent = `关卡 ${levelId}`;

            switch(levelId) {
                case 1: showConceptLevel(); break;
                case 2: showGridLevel(); break;
                case 3: showFormulaLevel(); break;
                case 4: showRectChallengeLevel(); break;
                case 5: showFinalChallengeLevel(); break;
            }
        }

        // 关卡1: 认识面积
        let conceptStep = 0;
        let grassTiles = [];

        function showConceptLevel() {
            conceptStep = 0;
            const content = document.getElementById('gameContent');
            content.innerHTML = `
                <div class="concept-area">
                    <div class="area-text" id="conceptTitle">什么是面积？</div>
                    <div class="concept-animation" id="conceptAnim">
                        <div class="ground" id="ground"></div>
                        <div class="house" id="house" style="display:none;">
                            <div class="house-roof"></div>
                            <div class="house-body">
                                <div class="house-window left"></div>
                                <div class="house-window right"></div>
                                <div class="house-door"></div>
                            </div>
                        </div>
                    </div>
                    <div class="concept-tip" id="conceptTip">
                        点击下方按钮，一起来探索面积的奥秘！
                    </div>
                    <button class="submit-btn" onclick="conceptNextStep()" style="margin-top: 20px;" id="conceptBtn">下一步</button>
                    <div class="progress-bar" style="max-width: 400px; margin: 30px auto;">
                        <div class="progress-fill" id="conceptProgress" style="width: 0%"></div>
                    </div>
                </div>
            `;
        }

        function conceptNextStep() {
            const ground = document.getElementById('ground');
            const house = document.getElementById('house');
            const title = document.getElementById('conceptTitle');
            const tip = document.getElementById('conceptTip');
            const btn = document.getElementById('conceptBtn');
            const progress = document.getElementById('conceptProgress');

            conceptStep++;

            switch(conceptStep) {
                case 1:
                    title.textContent = '这是一块草地';
                    tip.textContent = '草地的大小就是这块区域的"面积"哦！';
                    progress.style.width = '25%';
                    break;
                case 2:
                    house.style.display = 'block';
                    title.textContent = '占地面积';
                    tip.textContent = '房子占用了这块草地的大小，我们叫它"占地面积"！';
                    progress.style.width = '50%';
                    break;
                case 3:
                    // 添加方格
                    const anim = document.getElementById('conceptAnim');
                    for (let i = 0; i < 6; i++) {
                        for (let j = 0; j < 5; j++) {
                            const tile = document.createElement('div');
                            tile.className = 'grass-tile';
                            tile.style.left = (100 + j * 50) + 'px';
                            tile.style.top = (50 + i * 30) + 'px';
                            tile.textContent = '1';
                            tile.style.opacity = '0';
                            tile.style.transitionDelay = (i * 0.1 + j * 0.05) + 's';
                            anim.appendChild(tile);
                            grassTiles.push(tile);
                            setTimeout(() => tile.style.opacity = '1', 50);
                        }
                    }
                    title.textContent = '用方格来测量';
                    tip.textContent = '每个小方格代表1个面积单位，我们可以数一数有多少个方格！';
                    progress.style.width = '75%';
                    break;
                case 4:
                    title.textContent = '面积 = 6 × 5 = 30';
                    tip.textContent = '长有6个方格，宽有5个方格，所以面积是 6×5=30 个平方单位！';
                    btn.textContent = '完成学习！';
                    progress.style.width = '100%';
                    break;
                case 5:
                    completeLevel(1, 3);
                    showLevelSelect();
                    break;
            }
        }

        // 关卡2: 方格练习
        let gridExercises = [];
        let currentExercise = 0;
        let tilesRemaining = 0;

        function showGridLevel() {
            gridExercises = [
                { rows: 3, cols: 4, answer: 12 },
                { rows: 4, cols: 5, answer: 20 },
                { rows: 2, cols: 6, answer: 12 },
                { rows: 5, cols: 3, answer: 15 }
            ];
            currentExercise = 0;
            showGridExercise();
        }

        function showGridExercise() {
            const exercise = gridExercises[currentExercise];
            tilesRemaining = exercise.answer;

            const content = document.getElementById('gameContent');
            content.innerHTML = `
                <div class="grid-exercise">
                    <div class="exercise-instruction">用方格填满图形，然后数一数面积是多少？</div>
                    <div class="progress-bar" style="max-width: 600px; margin: 20px auto;">
                        <div class="progress-fill" style="width: ${(currentExercise / gridExercises.length) * 100}%"></div>
                    </div>
                    <div class="grid-container">
                        <div class="grid-area" id="exerciseGrid" style="grid-template-columns: repeat(${exercise.cols}, 50px);">
                            ${generateGridCells(exercise.rows, exercise.cols)}
                        </div>
                        <div class="tile-source" id="tileSource">
                            <div style="font-size: 1.2em; color: #666; margin-bottom: 10px;">点击方格填充：</div>
                            ${generateTiles(exercise.answer)}
                        </div>
                    </div>
                    <div class="answer-section">
                        <span style="font-size: 1.3em;">面积 = </span>
                        <input type="number" class="answer-input" id="gridAnswer" min="1" max="100">
                        <button class="submit-btn" onclick="checkGridAnswer()">确认</button>
                    </div>
                    <div class="feedback" id="gridFeedback"></div>
                </div>
            `;
        }

        function generateGridCells(rows, cols) {
            let html = '';
            for (let i = 0; i < rows * cols; i++) {
                html += `<div class="grid-cell" data-index="${i}" onclick="fillCell(this)"></div>`;
            }
            return html;
        }

        function generateTiles(count) {
            let html = '';
            for (let i = 0; i < count; i++) {
                html += `<div class="draggable-tile" onclick="useTile(this)">${i + 1}</div>`;
            }
            return html;
        }

        function useTile(tile) {
            if (tile.classList.contains('used')) return;
            tile.classList.add('used');

            const cells = document.querySelectorAll('.grid-cell:not(.filled)');
            if (cells.length > 0) {
                cells[0].classList.add('filled');
                cells[0].textContent = tile.textContent;
            }
        }

        function fillCell(cell) {
            if (cell.classList.contains('filled')) return;
            cell.classList.add('filled');
            cell.textContent = '✓';
        }

        function checkGridAnswer() {
            const userAnswer = parseInt(document.getElementById('gridAnswer').value);
            const correctAnswer = gridExercises[currentExercise].answer;
            const feedback = document.getElementById('gridFeedback');

            if (userAnswer === correctAnswer) {
                feedback.className = 'feedback correct';
                feedback.textContent = '太棒了！回答正确！🎉';
                createStarsAnimation();

                setTimeout(() => {
                    currentExercise++;
                    if (currentExercise >= gridExercises.length) {
                        completeLevel(2, 3);
                        showLevelSelect();
                    } else {
                        showGridExercise();
                    }
                }, 1500);
            } else {
                feedback.className = 'feedback incorrect';
                feedback.textContent = '再想一想，面积是数一数有多少个小方格哦～';
                document.getElementById('gridAnswer').value = '';
                document.querySelectorAll('.grid-cell.filled').forEach(c => {
                    c.classList.add('wrong');
                    setTimeout(() => c.classList.remove('wrong'), 500);
                });
            }
        }

        // 关卡3: 公式学习
        function showFormulaLevel() {
            const content = document.getElementById('gameContent');
            content.innerHTML = `
                <div class="formula-area">
                    <div class="area-text">长方形面积公式</div>
                    <div class="formula-display">
                        <div class="formula-text">面积 = 长 × 宽</div>
                        <div class="formula-visual">
                            <div class="rectangle-demo">
                                <div class="dimension-label width">宽 = 4</div>
                                <div class="rect-demo-body" style="grid-template-columns: repeat(4, 40px);">
                                    ${'<div class="rect-demo-cell"></div>'.repeat(12)}
                                </div>
                                <div class="dimension-label length">长 = 3</div>
                            </div>
                        </div>
                        <div style="font-size: 1.3em; margin-top: 20px;">
                            3 行 × 4 列 = 12 个方格
                        </div>
                    </div>
                    <div class="formula-examples">
                        <h3 style="margin-bottom: 15px; color: #667eea;">练习一下：</h3>
                        <div class="example-item">
                            <span class="example-calc">长 = 5, 宽 = 3, 面积 = ?</span>
                            <span class="example-result" onclick="this.style.background='#2ecc71'; this.textContent='15 ✓'" style="cursor:pointer;">点击查看</span>
                        </div>
                        <div class="example-item">
                            <span class="example-calc">长 = 6, 宽 = 4, 面积 = ?</span>
                            <span class="example-result" onclick="this.style.background='#2ecc71'; this.textContent='24 ✓'" style="cursor:pointer;">点击查看</span>
                        </div>
                        <div class="example-item">
                            <span class="example-calc">长 = 7, 宽 = 2, 面积 = ?</span>
                            <span class="example-result" onclick="this.style.background='#2ecc71'; this.textContent='14 ✓'" style="cursor:pointer;">点击查看</span>
                        </div>
                    </div>
                    <button class="submit-btn" onclick="completeLevel(3, 3); showLevelSelect();" style="margin-top: 30px;">我学会了！</button>
                </div>
            `;
        }

        // 关卡4: 矩形挑战
        let rectChallenges = [];
        let currentRectChallenge = 0;

        function showRectChallengeLevel() {
            rectChallenges = [
                { length: 5, width: 3, shape: 'rect' },
                { length: 6, width: 4, shape: 'rect' },
                { length: 7, width: 2, shape: 'rect' },
                { length: 8, width: 5, shape: 'rect' },
                { length: 4, width: 4, shape: 'square' }
            ];
            currentRectChallenge = 0;
            showRectChallenge();
        }

        function showRectChallenge() {
            const challenge = rectChallenges[currentRectChallenge];
            const area = challenge.length * challenge.width;
            const choices = generateChoices(area, 4);

            const content = document.getElementById('gameContent');
            content.innerHTML = `
                <div class="challenge-area">
                    <div class="progress-bar" style="max-width: 600px; margin: 20px auto;">
                        <div class="progress-fill" style="width: ${(currentRectChallenge / rectChallenges.length) * 100}%"></div>
                    </div>
                    <div class="challenge-question">
                        这个${challenge.shape === 'square' ? '正方形' : '长方形'}的面积是多少？
                    </div>
                    <div class="shape-display">
                        <div class="shape-${challenge.shape}" style="width: ${challenge.length * 40}px; height: ${challenge.width * 40}px;"></div>
                        <div class="shape-label">长 = ${challenge.length}, 宽 = ${challenge.width}</div>
                    </div>
                    <div class="multiple-choice">
                        ${choices.map(c => `<button class="choice-btn" onclick="checkChoice(this, ${c === area}, ${area})">${c}</button>`).join('')}
                    </div>
                    <div class="feedback" id="rectFeedback"></div>
                </div>
            `;
        }

        function generateChoices(correct, count) {
            const choices = [correct];
            while (choices.length < count) {
                const wrong = correct + Math.floor(Math.random() * 10) - 5;
                if (wrong > 0 && !choices.includes(wrong)) {
                    choices.push(wrong);
                }
            }
            return choices.sort(() => Math.random() - 0.5);
        }

        function checkChoice(btn, isCorrect, correctAnswer) {
            const feedback = document.getElementById('rectFeedback');
            const buttons = document.querySelectorAll('.choice-btn');

            buttons.forEach(b => b.style.pointerEvents = 'none');

            if (isCorrect) {
                btn.classList.add('correct');
                feedback.className = 'feedback correct';
                feedback.textContent = '太棒了！🎉';
                createStarsAnimation();

                setTimeout(() => {
                    currentRectChallenge++;
                    if (currentRectChallenge >= rectChallenges.length) {
                        completeLevel(4, 3);
                        showLevelSelect();
                    } else {
                        showRectChallenge();
                    }
                }, 1200);
            } else {
                btn.classList.add('incorrect');
                feedback.className = 'feedback incorrect';
                feedback.textContent = `答案不对哦，记住：面积 = 长 × 宽 = ${correctAnswer}`;
                setTimeout(() => {
                    buttons.forEach(b => b.style.pointerEvents = 'auto');
                    feedback.style.display = 'none';
                }, 1500);
            }
        }

        // 关卡5: 综合挑战
        let finalChallenges = [];
        let currentFinalChallenge = 0;

        function showFinalChallengeLevel() {
            finalChallenges = [
                { type: 'rect', length: 9, width: 4, desc: '长方形' },
                { type: 'square', length: 6, width: 6, desc: '正方形' },
                { type: 'rect', length: 8, width: 3, desc: '长方形' },
                { type: 'square', length: 5, width: 5, desc: '正方形' },
                { type: 'rect', length: 7, width: 6, desc: '长方形' }
            ];
            currentFinalChallenge = 0;
            showFinalChallenge();
        }

        function showFinalChallenge() {
            const challenge = finalChallenges[currentFinalChallenge];
            const area = challenge.length * challenge.width;
            const choices = generateChoices(area, 4);

            const content = document.getElementById('gameContent');
            content.innerHTML = `
                <div class="challenge-area">
                    <div style="background: linear-gradient(135deg, #f39c12, #e74c3c); color: white; padding: 10px 20px; border-radius: 20px; display: inline-block; margin-bottom: 20px;">
                        最终挑战 - 第 ${currentFinalChallenge + 1} / ${finalChallenges.length} 题
                    </div>
                    <div class="challenge-question">
                        计算这个${challenge.desc}的面积：
                    </div>
                    <div class="shape-display">
                        <div class="shape-${challenge.type === 'square' ? 'square' : 'shape-rect'}" style="width: ${Math.min(challenge.length * 35, 300)}px; height: ${Math.min(challenge.width * 35, 200)}px;"></div>
                        <div class="shape-label">长 = ${challenge.length}, 宽 = ${challenge.width}</div>
                    </div>
                    <div class="multiple-choice">
                        ${choices.map(c => `<button class="choice-btn" onclick="checkFinalChoice(this, ${c === area}, ${area})">${c}</button>`).join('')}
                    </div>
                    <div class="feedback" id="finalFeedback"></div>
                </div>
            `;
        }

        function checkFinalChoice(btn, isCorrect, correctAnswer) {
            const feedback = document.getElementById('finalFeedback');
            const buttons = document.querySelectorAll('.choice-btn');

            buttons.forEach(b => b.style.pointerEvents = 'none');

            if (isCorrect) {
                btn.classList.add('correct');
                feedback.className = 'feedback correct';
                feedback.textContent = '太棒了！🎉';
                createStarsAnimation();
                gameData.totalScore += 50;

                setTimeout(() => {
                    currentFinalChallenge++;
                    if (currentFinalChallenge >= finalChallenges.length) {
                        completeLevel(5, 3);
                        unlockAchievement('面积大师', '完成了所有关卡！');
                        showLevelSelect();
                    } else {
                        showFinalChallenge();
                    }
                }, 1200);
            } else {
                btn.classList.add('incorrect');
                feedback.className = 'feedback incorrect';
                feedback.textContent = `正确答案是 ${correctAnswer}！再接再厉！`;
                setTimeout(() => {
                    buttons.forEach(b => b.style.pointerEvents = 'auto');
                    feedback.style.display = 'none';
                }, 1500);
            }
        }

        // 通用函数
        function completeLevel(levelId, stars) {
            if (!gameData.completedLevels.includes(levelId)) {
                gameData.completedLevels.push(levelId);
                gameData.totalScore += stars * 50;
            }
            updateStats();
            saveProgress();
        }

        function createStarsAnimation() {
            const container = document.createElement('div');
            container.className = 'stars-animation';
            container.style.left = '50%';
            container.style.top = '50%';

            for (let i = 0; i < 8; i++) {
                const star = document.createElement('div');
                star.className = 'star';
                star.textContent = '⭐';
                star.style.left = (Math.random() * 200 - 100) + 'px';
                star.style.animationDelay = (i * 0.1) + 's';
                container.appendChild(star);
            }

            document.body.appendChild(container);
            setTimeout(() => container.remove(), 1500);
        }

        function unlockAchievement(title, desc) {
            if (!gameData.achievements.includes(title)) {
                gameData.achievements.push(title);
                saveProgress();
            }

            const overlay = document.getElementById('overlay');
            const popup = document.getElementById('achievementPopup');
            document.getElementById('achievementIcon').textContent = '🏆';
            document.getElementById('achievementTitle').textContent = title;
            document.getElementById('achievementDesc').textContent = desc;

            overlay.classList.add('show');
            popup.classList.add('show');

            setTimeout(() => {
                overlay.classList.remove('show');
                popup.classList.remove('show');
            }, 2500);
        }

        // 启动游戏
        init();
    </script>
</body>
</html>
