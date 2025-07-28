<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Meus Afazeres</title>
    
    <!-- PWA Meta Tags -->
    <meta name="theme-color" content="#3B82F6">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="default">
    <meta name="apple-mobile-web-app-title" content="Meus Afazeres">
    
    <!-- PWA Icons -->
    <link rel="apple-touch-icon" href="data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTgwIiBoZWlnaHQ9IjE4MCIgdmlld0JveD0iMCAwIDE4MCAxODAiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxyZWN0IHdpZHRoPSIxODAiIGhlaWdodD0iMTgwIiByeD0iNDAiIGZpbGw9IiMzQjgyRjYiLz4KPHN2ZyB4PSI0MCIgeT0iNDAiIHdpZHRoPSIxMDAiIGhlaWdodD0iMTAwIiB2aWV3Qm94PSIwIDAgMjQgMjQiIGZpbGw9Im5vbmUiPgo8cGF0aCBkPSJNMTIgNXYxNG0tNy03aDRtNiAwaDRtLTctN2g0bTYgMGg0IiBzdHJva2U9IndoaXRlIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIvPgo8L3N2Zz4KPC9zdmc+">
    
    <!-- Manifest -->
    <link rel="manifest" href="data:application/json;base64,eyJuYW1lIjoiTWV1cyBBZmF6ZXJlcyIsInNob3J0X25hbWUiOiJBZmF6ZXJlcyIsInN0YXJ0X3VybCI6Ii8iLCJkaXNwbGF5Ijoic3RhbmRhbG9uZSIsImJhY2tncm91bmRfY29sb3IiOiIjZmZmZmZmIiwidGhlbWVfY29sb3IiOiIjM0I4MkY2IiwiaWNvbnMiOlt7InNyYyI6ImRhdGE6aW1hZ2Uvc3ZnK3htbDtiYXNlNjQsUEhOMlp5QjNhV1IwYUQwaU1UZ3dJaUJvWldsbmFIUTlJakU0TUNJZ2RtbGxkMEp2ZUQwaU1DQXdJREU0TUNBME1EQWlJR1pwYkd3OUltNXZibVVpSUhodGJHNXpQU0pvZEhSd09pOHZkM2QzTG5jekxtOXlaeTh5TURBd0wzTjJaeUkrQ2p4eVpXTjBJSGRwWkhSb1BTSXhPREFpSUdobGFXZG9kRDBpTVRnd0lpQnllRDBpTkRBaUlHWnBiR3c5SWpOQ09ESkdOaUl2UGdvOGMzWm5JR2c5SWpRd0lpQjVQU0kwTUNJZ2QybGtkR2c5SWpFd01DSWdhR1ZwWjJoMFBTSXhNREFpSUhacFpYZENiM2c5SWpBZ01DQXlOQ0F5TkNJZ1ptbHNiRDBpYm05dVpTSStDbkJ3WVhSb0lHUTlJazB4TWlBMWRqRTBiUzAzTFRkb05HMDJJREJvTkcweExUZG9OR3hUTVRKaUxURWlJSE4wY205clpUMWlkMmgwWm1VaUlITjBjbTlyWlMxM2FXUjBhRDBpTWlJZ2MzUnliMnRsTFdsdVpXTmhjRDBpY205MWJtUWlMejRLUEM5emRtYytDbHh1UEM5emRtYytDZz09SWl3aWMybDZaWE5pT2lJeE9EQjROemt4T0RBaUxDSmNibWwwZVhCbFhHNGlPaUJlYW05dVoyeDVZV0YwWm1sdlhtNWtiMmR1Y1hSb0xtaDViV3hsZG1sdWMwSWpObTRuT1daalFtUXFGZ3NVTTB0bWRpaUtOQ2RpaW1vcG1IY25Pa0lIZ2o9PSIsInNpemVzIjoiMTgweDNOZHg0MDMjMCIsInR5cGUiOiJpbWFnZS9zdmcreG1sIn1dfQ==">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: linear-gradient(135deg, #eff6ff 0%, #e0e7ff 100%);
            min-height: 100vh;
            padding: 1rem;
            -webkit-user-select: none;
            user-select: none;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 400px;
            margin: 0 auto;
        }
        
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 2rem;
            padding-top: 3rem;
        }
        
        .header h1 {
            font-size: 1.875rem;
            font-weight: bold;
            color: #1f2937;
        }
        
        .header p {
            color: #6b7280;
            margin-top: 0.25rem;
        }
        
        .add-btn {
            width: 3.5rem;
            height: 3.5rem;
            background: #3b82f6;
            border: none;
            border-radius: 50%;
            color: white;
            font-size: 1.5rem;
            cursor: pointer;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        
        .add-btn:hover {
            background: #2563eb;
            transform: translateY(-2px);
        }
        
        .category-card {
            border-radius: 1.5rem;
            padding: 1.5rem;
            margin-bottom: 1rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1);
            color: white;
        }
        
        .category-card.now {
            background: linear-gradient(135deg, #ef4444 0%, #ec4899 100%);
        }
        
        .category-card.later {
            background: linear-gradient(135deg, #f97316 0%, #eab308 100%);
        }
        
        .category-card.future {
            background: linear-gradient(135deg, #10b981 0%, #14b8a6 100%);
        }
        
        .category-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1rem;
        }
        
        .category-title {
            display: flex;
            align-items: center;
            gap: 0.75rem;
        }
        
        .category-title h2 {
            font-size: 1.25rem;
            font-weight: bold;
        }
        
        .task-count {
            background: rgba(255, 255, 255, 0.3);
            padding: 0.25rem 0.75rem;
            border-radius: 9999px;
            font-size: 0.875rem;
            font-weight: 500;
        }
        
        .tasks-container {
            max-height: 10rem;
            overflow-y: auto;
        }
        
        .task-item {
            display: flex;
            align-items: center;
            gap: 0.75rem;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 1rem;
            padding: 0.75rem;
            margin-bottom: 0.75rem;
        }
        
        .task-checkbox {
            width: 1.5rem;
            height: 1.5rem;
            border: 2px solid white;
            border-radius: 50%;
            background: transparent;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s ease;
        }
        
        .task-checkbox.completed {
            background: white;
        }
        
        .task-checkbox.completed::after {
            content: '';
            width: 0.75rem;
            height: 0.75rem;
            background: #10b981;
            border-radius: 50%;
        }
        
        .task-text {
            flex: 1;
            color: white;
        }
        
        .task-text.completed {
            text-decoration: line-through;
            opacity: 0.7;
        }
        
        .delete-btn {
            width: 2rem;
            height: 2rem;
            background: rgba(255, 255, 255, 0.3);
            border: none;
            border-radius: 50%;
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .delete-btn:hover {
            background: rgba(255, 255, 255, 0.5);
        }
        
        .empty-state {
            color: rgba(255, 255, 255, 0.8);
            font-style: italic;
        }
        
        .modal {
            position: fixed;
            inset: 0;
            background: rgba(0, 0, 0, 0.5);
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 1rem;
            z-index: 50;
        }
        
        .modal.hidden {
            display: none;
        }
        
        .modal-content {
            background: white;
            border-radius: 1.5rem;
            padding: 1.5rem;
            width: 100%;
            max-width: 28rem;
        }
        
        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.5rem;
        }
        
        .modal-header h3 {
            font-size: 1.25rem;
            font-weight: bold;
            color: #1f2937;
        }
        
        .close-btn {
            width: 2rem;
            height: 2rem;
            background: #f3f4f6;
            border: none;
            border-radius: 50%;
            cursor: pointer;
        }
        
        .task-input {
            width: 100%;
            padding: 1rem;
            border: 1px solid #e5e7eb;
            border-radius: 1rem;
            font-size: 1.125rem;
            margin-bottom: 1rem;
            outline: none;
        }
        
        .task-input:focus {
            border-color: #3b82f6;
            box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.1);
        }
        
        .category-selector {
            margin-bottom: 1.5rem;
        }
        
        .category-selector p {
            color: #374151;
            margin-bottom: 0.75rem;
            font-weight: 500;
        }
        
        .category-options {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }
        
        .category-option {
            width: 100%;
            padding: 0.75rem;
            border: none;
            border-radius: 0.75rem;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: 500;
        }
        
        .category-option.now {
            background: linear-gradient(135deg, #ef4444 0%, #ec4899 100%);
            color: white;
        }
        
        .category-option.later {
            background: linear-gradient(135deg, #f97316 0%, #eab308 100%);
            color: white;
        }
        
        .category-option.future {
            background: linear-gradient(135deg, #10b981 0%, #14b8a6 100%);
            color: white;
        }
        
        .category-option:not(.selected) {
            background: #f3f4f6;
            color: #374151;
        }
        
        .category-option:not(.selected):hover {
            background: #e5e7eb;
        }
        
        .submit-btn {
            width: 100%;
            background: #3b82f6;
            color: white;
            padding: 1rem;
            border: none;
            border-radius: 1rem;
            font-size: 1.125rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        
        .submit-btn:hover:not(:disabled) {
            background: #2563eb;
        }
        
        .submit-btn:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }
        
        .icon {
            width: 1.5rem;
            height: 1.5rem;
            fill: currentColor;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <div>
                <h1>Meus Afazeres</h1>
                <p>Organize suas tarefas por prioridade</p>
            </div>
            <button class="add-btn" onclick="openModal()">+</button>
        </div>

        <!-- Categories -->
        <div id="categories">
            <!-- Categories will be rendered here -->
        </div>
    </div>

    <!-- Add Task Modal -->
    <div id="modal" class="modal hidden">
        <div class="modal-content">
            <div class="modal-header">
                <h3>Nova Tarefa</h3>
                <button class="close-btn" onclick="closeModal()">×</button>
            </div>

            <input 
                type="text" 
                id="taskInput" 
                class="task-input" 
                placeholder="Digite sua tarefa..."
                onkeypress="handleKeyPress(event)"
            >

            <div class="category-selector">
                <p>Quando fazer?</p>
                <div class="category-options">
                    <button class="category-option now selected" data-category="now" onclick="selectCategory('now')">
                        Agora
                    </button>
                    <button class="category-option later" data-category="later" onclick="selectCategory('later')">
                        Depois
                    </button>
                    <button class="category-option future" data-category="future" onclick="selectCategory('future')">
                        Mais Tarde
                    </button>
                </div>
            </div>

            <button class="submit-btn" onclick="addTask()" id="submitBtn">
                Adicionar Tarefa
            </button>
        </div>
    </div>

    <script>
        // App State
        let tasks = {
            now: [],
            later: [],
            future: []
        };
        
        let selectedCategory = 'now';

        // Load tasks from localStorage
        function loadTasks() {
            const saved = localStorage.getItem('tasks');
            if (saved) {
                tasks = JSON.parse(saved);
            }
        }

        // Save tasks to localStorage
        function saveTasks() {
            localStorage.setItem('tasks', JSON.stringify(tasks));
        }

        // Render categories
        function renderCategories() {
            const container = document.getElementById('categories');
            const categories = [
                { key: 'now', title: 'Agora', icon: '🕐', class: 'now' },
                { key: 'later', title: 'Depois', icon: '📅', class: 'later' },
                { key: 'future', title: 'Mais Tarde', icon: '🗓️', class: 'future' }
            ];

            container.innerHTML = categories.map(cat => `
                <div class="category-card ${cat.class}">
                    <div class="category-header">
                        <div class="category-title">
                            <span>${cat.icon}</span>
                            <h2>${cat.title}</h2>
                        </div>
                        <span class="task-count">${tasks[cat.key].length}</span>
                    </div>
                    
                    <div class="tasks-container">
                        ${tasks[cat.key].length === 0 ? 
                            '<p class="empty-state">Nenhuma tarefa</p>' :
                            tasks[cat.key].map(task => `
                                <div class="task-item">
                                    <div class="task-checkbox ${task.completed ? 'completed' : ''}" 
                                         onclick="toggleTask('${cat.key}', ${task.id})"></div>
                                    <span class="task-text ${task.completed ? 'completed' : ''}">${task.text}</span>
                                    <button class="delete-btn" onclick="deleteTask('${cat.key}', ${task.id})">×</button>
                                </div>
                            `).join('')
                        }
                    </div>
                </div>
            `).join('');
        }

        // Modal functions
        function openModal() {
            document.getElementById('modal').classList.remove('hidden');
            document.getElementById('taskInput').focus();
        }

        function closeModal() {
            document.getElementById('modal').classList.add('hidden');
            document.getElementById('taskInput').value = '';
            selectedCategory = 'now';
            updateCategorySelection();
        }

        function selectCategory(category) {
            selectedCategory = category;
            updateCategorySelection();
        }

        function updateCategorySelection() {
            document.querySelectorAll('.category-option').forEach(btn => {
                btn.classList.remove('selected');
                if (btn.dataset.category === selectedCategory) {
                    btn.classList.add('selected');
                }
            });
        }

        function handleKeyPress(event) {
            if (event.key === 'Enter') {
                addTask();
            }
        }

        // Task functions
        function addTask() {
            const input = document.getElementById('taskInput');
            const text = input.value.trim();
            
            if (text) {
                const newTask = {
                    id: Date.now(),
                    text: text,
                    completed: false
                };
                
                tasks[selectedCategory].push(newTask);
                saveTasks();
                renderCategories();
                closeModal();
            }
        }

        function toggleTask(category, taskId) {
            tasks[category] = tasks[category].map(task =>
                task.id === taskId ? { ...task, completed: !task.completed } : task
            );
            saveTasks();
            renderCategories();
        }

        function deleteTask(category, taskId) {
            tasks[category] = tasks[category].filter(task => task.id !== taskId);
            saveTasks();
            renderCategories();
        }

        // Initialize app
        loadTasks();
        renderCategories();
        updateCategorySelection();

        // Register service worker for PWA
        if ('serviceWorker' in navigator) {
            navigator.serviceWorker.register('data:text/javascript;base64,Y29uc3QgQ0FDSEVfTkFNRSA9ICd0b2RvLWFwcC12MSc7CmNvbnN0IHVybHNUb0NhY2hlID0gWwogICcvJwpdOwoKc2VsZi5hZGRFdmVudExpc3RlbmVyKCdpbnN0YWxsJywgZXZlbnQgPT4gewogIGV2ZW50LndhaXRVbnRpbCgKICAgIGNhY2hlcy5vcGVuKENBQ0hFX05BTUUpCiAgICAgIC50aGVuKGNhY2hlID0+IGNhY2hlLmFkZEFsbCh1cmxzVG9DYWNoZSkpCiAgKTsKfSk7CgpzZWxmLmFkZEV2ZW50TGlzdGVuZXIoJ2ZldGNoJywgZXZlbnQgPT4gewogIGV2ZW50LnJlc3BvbmRXaXRoKAogICAgY2FjaGVzLm1hdGNoKGV2ZW50LnJlcXVlc3QpCiAgICAgIC50aGVuKHJlc3BvbnNlID0+IHsKICAgICAgICByZXR1cm4gcmVzcG9uc2UgfHwgZmV0Y2goZXZlbnQucmVxdWVzdCk7CiAgICAgIH0pCiAgKTsKfSk7');
        }
    </script>
</body>
</html>
