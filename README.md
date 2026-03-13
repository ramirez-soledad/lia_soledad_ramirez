<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Linktree Profesional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #f0f9ff 0%, #f5f3ff 100%);
            min-height: 100vh;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.6);
            box-shadow: 0 4px 20px -2px rgba(30, 64, 175, 0.05);
        }
        .link-button {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            border: 1px solid transparent;
        }
        .link-button:hover {
            transform: scale(1.02);
            background: #ffffff;
            border-color: #93c5fd;
            box-shadow: 0 10px 25px -5px rgba(59, 130, 246, 0.15);
        }
        .gpt-badge {
            background: linear-gradient(90deg, #2563eb, #8b5cf6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-weight: 700;
        }
        .profile-ring {
            padding: 3px;
            background: linear-gradient(45deg, #3b82f6, #a78bfa);
            border-radius: 9999px;
        }
    </style>
</head>
<body class="flex flex-col items-center py-16 px-6">

    <!-- Main Container -->
    <div class="w-full max-w-md flex flex-col items-center">
        
        <!-- Profile Section -->
        <div class="profile-ring mb-6 shadow-xl">
            <div class="bg-white rounded-full p-1">
                <img src="https://api.dicebear.com/7.x/micah/svg?seed=creative&backgroundColor=f0f9ff" alt="Avatar" class="w-24 h-24 rounded-full">
            </div>
        </div>

        <h1 class="text-3xl font-bold text-gray-900 mb-2 tracking-tight">Tu Nombre</h1>
        <p class="text-gray-500 text-sm mb-10 text-center leading-relaxed max-w-[280px]">
            Especialista en Automatización & AI. Optimizando flujos de trabajo con tecnología.
        </p>

        <!-- Links Section -->
        <div class="w-full space-y-4">
            
            <!-- Redes Principales -->
            <h2 class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-2 ml-2">Contacto</h2>
            
            <a href="#" class="link-button glass-card w-full py-4 px-6 rounded-2xl flex items-center group">
                <div class="bg-blue-50 p-2 rounded-lg mr-4 group-hover:bg-blue-100 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#2563eb" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect><path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"></path><line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line></svg>
                </div>
                <span class="font-semibold text-gray-700">Instagram</span>
            </a>

            <a href="#" class="link-button glass-card w-full py-4 px-6 rounded-2xl flex items-center group">
                <div class="bg-blue-50 p-2 rounded-lg mr-4 group-hover:bg-blue-100 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#3b82f6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
                </div>
                <span class="font-semibold text-gray-700">LinkedIn</span>
            </a>

            <!-- Sección GPTs -->
            <div class="pt-6">
                <h2 class="text-xs font-bold text-gray-400 uppercase tracking-widest mb-4 ml-2">Mis GPTs Personalizados</h2>
                <div class="space-y-3">
                    
                    <a href="#" class="link-button glass-card w-full py-4 px-6 rounded-2xl flex items-center group border-l-4 border-l-purple-400">
                        <div class="bg-purple-50 p-2 rounded-lg mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#8b5cf6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14.5 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V7.5L14.5 2z"></path><polyline points="14 2 14 8 20 8"></polyline><line x1="16" y1="13" x2="8" y2="13"></line><line x1="16" y1="17" x2="8" y2="17"></line><line x1="10" y1="9" x2="8" y2="9"></line></svg>
                        </div>
                        <div class="flex flex-col text-left">
                            <span class="font-bold text-gray-800">Redactor de Documentos</span>
                            <span class="text-xs text-gray-500 italic">Escritura profesional y formal</span>
                        </div>
                    </a>

                    <a href="#" class="link-button glass-card w-full py-4 px-6 rounded-2xl flex items-center group border-l-4 border-l-indigo-400">
                        <div class="bg-indigo-50 p-2 rounded-lg mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#6366f1" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="16 18 22 12 16 6"></polyline><polyline points="8 6 2 12 8 18"></polyline></svg>
                        </div>
                        <div class="flex flex-col text-left">
                            <span class="font-bold text-gray-800">Code Mentor</span>
                            <span class="text-xs text-gray-500 italic">Aprende programación paso a paso</span>
                        </div>
                    </a>

                    <a href="#" class="link-button glass-card w-full py-4 px-6 rounded-2xl flex items-center group border-l-4 border-l-blue-400">
                        <div class="bg-blue-50 p-2 rounded-lg mr-4">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="#3b82f6" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"></path></svg>
                        </div>
                        <div class="flex flex-col text-left">
                            <span class="font-bold text-gray-800">n8n Master</span>
                            <span class="text-xs text-gray-500 italic">Arquitecto de automatizaciones</span>
                        </div>
                    </a>

                </div>
            </div>

        </div>

        <!-- Footer -->
        <footer class="mt-16 flex flex-col items-center">
            <div class="flex space-x-5 mb-6 text-gray-400">
                <a href="mailto:tuemail@ejemplo.com" class="hover:text-blue-600 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
                </a>
            </div>
            <span class="gpt-badge text-[10px] uppercase tracking-[0.2em]">Powered by Intelligence</span>
        </footer>

    </div>

</body>
</html>
