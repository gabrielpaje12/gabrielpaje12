<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Gabriel Oliveira - Desenvolvedor Java</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
        rel="stylesheet"
    />
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap');

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background: #000000;
            color: #ffffff;
            min-height: 100vh;
        }

        .code-bg {
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .tech-icon {
            transition: all 0.3s ease;
        }

        .tech-icon:hover {
            transform: scale(1.1);
        }

        .gradient-text {
            background: linear-gradient(45deg, #60a5fa, #818cf8, #ec4899);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .typewriter {
            overflow: hidden;
            border-right: 2px solid #60a5fa;
            white-space: nowrap;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
        }

        @keyframes typing {
            from {
                width: 0;
            }
            to {
                width: 100%;
            }
        }

        @keyframes blink-caret {
            from,
            to {
                border-color: transparent;
            }
            50% {
                border-color: #60a5fa;
            }
        }

        .social-icon {
            transition: all 0.3s ease;
        }

        .social-icon:hover {
            transform: translateY(-3px);
            color: #60a5fa;
        }

        .glow-border {
            border: 1px solid rgba(59, 130, 246, 0.3);
            box-shadow: 0 0 20px rgba(59, 130, 246, 0.2);
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- Header -->
    <header class="fixed w-full top-0 z-50 code-bg">
        <nav class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="flex items-center space-x-2">
                    <div
                        class="w-8 h-8 bg-blue-500 rounded-lg flex items-center justify-center"
                    >
                        <span class="text-white font-bold">GO</span>
                    </div>
                    <span class="text-xl font-semibold">Gabriel Oliveira</span>
                </div>

                <div class="hidden md:flex space-x-8">
                    <a href="#inicio" class="text-gray-300 hover:text-white transition"
                        >Início</a
                    >
                    <a href="#sobre" class="text-gray-300 hover:text-white transition"
                        >Sobre</a
                    >
                    <a
                        href="#habilidades"
                        class="text-gray-300 hover:text-white transition"
                        >Habilidades</a
                    >
                    <a href="#contato" class="text-gray-300 hover:text-white transition"
                        >Contato</a
                    >
                </div>

                <button class="md:hidden text-gray-300">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section
        id="inicio"
        class="min-h-screen flex items-center justify-center pt-20 px-6"
    >
        <div class="text-center max-w-4xl">
            <div
                class="w-32 h-32 mx-auto mb-8 rounded-full border-4 border-blue-500 p-2 glow-border"
            >
                <img
                    src="https://placehold.co/300x300"
                    alt="Foto profissional de Gabriel Oliveira - Desenvolvedor Java e Spring Boot especializado em desenvolvimento backend"
                    class="w-full h-full object-cover rounded-full"
                />
            </div>

            <h1 class="text-4xl md:text-6xl font-bold mb-6">
                Gabriel <span class="gradient-text">Oliveira</span>
            </h1>

            <div
                class="typewriter text-xl md:text-2xl text-gray-300 mb-8 inline-block"
            >
                Desenvolvedor Backend Java & Spring Boot
            </div>

            <p class="text-lg text-gray-400 mb-12 max-w-2xl mx-auto">
                Transformando ideias em soluções robustas através do poder do Java e
                Spring Boot. Apaixonado por código limpo, arquitetura escalável e boas
                práticas de desenvolvimento.
            </p>

            <div class="flex justify-center space-x-6 mb-12">
                <img
                    src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"
                    alt="Java Programming Language - Linguagem de programação Java para desenvolvimento backend"
                    class="tech-icon w-16 h-16"
                />
                <img
                    src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg"
                    alt="Spring Boot Framework - Framework Spring Boot para desenvolvimento de aplicações Java enterprise"
                    class="tech-icon w-16 h-16"
                />
            </div>

            <div class="space-x-4">
                <a
                    href="#habilidades"
                    class="bg-blue-600 px-8 py-3 rounded-lg text-white font-semibold hover:bg-blue-700 transition inline-block"
                    >Ver Habilidades</a
                >
                <a
                    href="#contato"
                    class="border-2 border-gray-600 px-8 py-3 rounded-lg text-gray-300 font-semibold hover:border-blue-600 hover:text-white transition inline-block"
                    >Entrar em Contato</a
                >
            </div>
        </div>
    </section>

    <!-- Sobre -->
    <section id="sobre" class="py-20 px-6">
        <div class="container mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">Sobre Mim</h2>
                <div class="w-20 h-1 bg-blue-500 mx-auto"></div>
            </div>

            <div
                class="grid md:grid-cols-2 gap-12 items-center max-w-6xl mx-auto"
            >
                <div>
                    <div class="code-bg p-8 rounded-xl glow-border">
                        <h3 class="text-2xl font-semibold mb-6">Minha Jornada</h3>
                        <p class="text-gray-300 mb-6 leading-relaxed">
                            Sou um desenvolvedor backend especializado em Java e Spring Boot,
                            com foco em criar aplicações escaláveis e de alta performance. Minha
                            paixão por tecnologia começou cedo e evoluiu para uma carreira
                            dedicada ao desenvolvimento de software.
                        </p>
                        <p class="text-gray-300 mb-8 leading-relaxed">
                            Acredito no poder do código bem escrito e na importância de seguir
                            as melhores práticas de desenvolvimento. Minha experiência abrange
                            desde APIs RESTful até sistemas distribuídos complexos, sempre
                            buscando a excelência técnica e soluções elegantes para problemas
                            desafiadores.
                        </p>

                        <div class="grid grid-cols-2 gap-4">
                            <div class="flex items-center">
                                <i class="fas fa-code text-blue-500 mr-3"></i>
                                <span>Código Limpo</span>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-layer-group text-blue-500 mr-3"></i>
                                <span>Arquitetura</span>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-rocket text-blue-500 mr-3"></i>
                                <span>Performance</span>
                            </div>
                            <div class="flex items-center">
                                <i class="fas fa-shield-alt text-blue-500 mr-3"></i>
                                <span>Segurança</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="grid grid-cols-2 gap-4">
                    <div
                        class="code-bg p-6 rounded-xl text-center glow-border"
                    >
                        <div class="text-3xl font-bold text-blue-500 mb-2">2+</div>
                        <div class="text-gray-300">Anos de Experiência</div>
                    </div>
                    <div
                        class="code-bg p-6 rounded-xl text-center glow-border"
                    >
                        <div class="text-3xl font-bold text-blue-500 mb-2">15+</div>
                        <div class="text-gray-300">Projetos Concluídos</div>
                    </div>
                    <div
                        class="code-bg p-6 rounded-xl text-center glow-border"
                    >
                        <div class="text-3xl font-bold text-blue-500 mb-2">Java</div>
                        <div class="text-gray-300">Especialização</div>
                    </div>
                    <div
                        class="code-bg p-6 rounded-xl text-center glow-border"
                    >
                        <div class="text-3xl font-bold text-blue-500 mb-2">Spring</div>
                        <div class="text-gray-300">Framework Principal</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Habilidades -->
    <section id="habilidades" class="py-20 px-6 bg-gray-900">
        <div class="container mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">
                    Habilidades Técnicas
                </h2>
                <p class="text-gray-400 max-w-2xl mx-auto">
                    Tecnologias e ferramentas que domino e utilizo no desenvolvimento
                </p>
                <div class="w-20 h-1 bg-blue-500 mx-auto mt-4"></div>
            </div>

            <div
                class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-6xl mx-auto"
            >
                <!-- Backend -->
                <div class="code-bg p-6 rounded-xl glow-border">
                    <h3 class="text-xl font-semibold mb-6 text-center">Backend</h3>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg"
                                alt="Java"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">Java</span>
                        </div>
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg"
                                alt="Spring Boot"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">Spring Boot</span>
                        </div>
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg"
                                alt="PostgreSQL"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">PostgreSQL</span>
                        </div>
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg"
                                alt="MySQL"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">MySQL</span>
                        </div>
                    </div>
                </div>

                <!-- Ferramentas -->
                <div class="code-bg p-6 rounded-xl glow-border">
                    <h3 class="text-xl font-semibold mb-6 text-center">
                        Ferramentas
                    </h3>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg"
                                alt="Git"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">Git</span>
                        </div>
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg"
                                alt="Docker"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">Docker</span>
                        </div>
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg"
                                alt="IntelliJ IDEA"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">IntelliJ</span>
                        </div>
                        <div class="text-center">
                            <img
                                src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg"
                                alt="AWS"
                                class="tech-icon w-12 h-12 mx-auto mb-2"
                            />
                            <span class="text-sm">AWS</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contato -->
    <section id="contato" class="py-20 px-6 bg-gray-900">
        <div class="container mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4">
                    Vamos Trabalhar Juntos?
                </h2>
                <p class="text-gray-400 max-w-2xl mx-auto">
                    Estou sempre aberto a novas oportunidades e projetos desafiadores
                </p>
                <div class="w-20 h-1 bg-blue-500 mx-auto mt-4"></div>
            </div>

            <div class="grid md:grid-cols-2 gap-12 max-w-4xl mx-auto">
                <div>
                    <h3 class="text-2xl font-semibold mb-6">Entre em Contato</h3>

                    <div class="space-y-6 mb-8">
                        <div class="flex items-center">
                            <div
                                class="bg-blue-600 p-3 rounded-full mr-4 flex items-center justify-center"
                            >
                                <i class="fas fa-envelope text-white"></i>
                            </div>
                            <div>
                                <p class="font-semibold">Email</p>
                                <p class="text-gray-400">gabriel.oliveira@email.com</p>
                            </div>
                        </div>

                        <div class="flex items-center">
                            <div
                                class="bg-blue-600 p-3 rounded-full mr-4 flex items-center justify-center"
                            >
                                <i class="fab fa-github text-white"></i>
                            </div>
                            <div>
                                <p class="font-semibold">GitHub</p>
                                <a
                                    href="https://github.com/gabrielpaje12"
                                    target="_blank"
                                    class="text-blue-400 hover:text-blue-300"
                                    >github.com/gabrielpaje12</a
                                >
                            </div>
                        </div>

                        <div class="flex items-center">
                            <div
                                class="bg-blue-600 p-3 rounded-full mr-4 flex items-center justify-center"
                            >
                                <i class="fab fa-linkedin text-white"></i>
                            </div>
                            <div>
                                <p class="font-semibold">LinkedIn</p>
                                <a
                                    href="https://www.linkedin.com/in/gabriel-oliveira-833a58373?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"
                                    target="_blank"
                                    class="text-blue-400 hover:text-blue-300"
                                    >Gabriel Oliveira</a
                                >
                            </div>
                        </div>
                    </div>

                    <h3 class="text-2xl font-semibold mb-4">Redes Sociais</h3>
                    <div class="flex space-x-4">
                        <a
                            href="https://github.com/gabrielpaje12"
                            target="_blank"
                            class="social-icon bg-gray-800 p-3 rounded-full hover:bg-gray-700"
                            ><i class="fab fa-github text-xl"></i
                        ></a>
                        <a
                            href="https://www.linkedin.com/in/gabriel-oliveira-833a58373?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"
                            target="_blank"
                            class="social-icon bg-gray-800 p-3 rounded-full hover:bg-gray-700"
                            ><i class="fab fa-linkedin text-xl"></i
                        ></a>
                    </div>
                </div>

                <div>
                    <form class="code-bg p-8 rounded-xl glow-border">
                        <h3 class="text-2xl font-semibold mb-6">Envie uma Mensagem</h3>

                        <div class="space-y-4">
                            <div>
                                <label class="block text-gray-300 mb-2">Nome completo</label>
                                <input
                                    type="text"
                                   
