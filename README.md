<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Бюджет для граждан | Вопросы и ответы</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Open+Sans:wght@400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.0/font/bootstrap-icons.css">
    
    <style>
        :root {
            --pastel-mint: #E8F5E9;
            --pastel-blue: #E3F2FD;
            --pastel-lavender: #F3E5F5;
            --pastel-cream: #FFF8E1;
            --pastel-gray: #F5F5F5;
            --text-dark: #424242;
            --text-muted: #757575;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            background-color: var(--pastel-gray);
            color: var(--text-dark);
        }

        h1, h2, h3, h4, h5, h6 {
            font-family: 'Times New Roman', Times, serif;
        }

        .navbar {
            background: linear-gradient(135deg, var(--pastel-mint) 0%, var(--pastel-blue) 100%);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.05);
        }

        .navbar-brand {
            font-weight: 700;
            color: var(--text-dark) !important;
        }

        .hero-section {
            background: linear-gradient(135deg, var(--pastel-blue) 0%, var(--pastel-lavender) 100%);
            padding: 60px 0;
            margin-bottom: 40px;
        }

        .hero-section h1 {
            font-weight: 700;
            margin-bottom: 20px;
        }

        .hero-section p {
            font-size: 1.1rem;
            color: var(--text-muted);
        }

        .search-box {
            background-color: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
            margin-bottom: 40px;
        }

        .search-box .form-control {
            border: 2px solid var(--pastel-blue);
            border-radius: 10px;
            padding: 12px 20px;
        }

        .accordion-item {
            border: none;
            margin-bottom: 15px;
            border-radius: 10px !important;
            overflow: hidden;
            box-shadow: 0 2px 8px rgba(0, 0, 0, 0.06);
        }

        .accordion-button {
            background-color: white;
            font-family: 'Montserrat', sans-serif;
            font-weight: 600;
            padding: 20px;
        }

        .accordion-button:not(.collapsed) {
            background-color: var(--pastel-mint);
        }

        .accordion-body {
            background-color: white;
            padding: 20px;
            line-height: 1.6;
        }

        .accordion-icon {
            margin-right: 10px;
            color: #81C784;
        }

        .info-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
            margin-bottom: 30px;
            transition: transform 0.3s ease;
            height: 100%;
        }

        .info-card:hover {
            transform: translateY(-5px);
        }

        .info-card img {
            width: 80px;
            height: 80px;
            object-fit: cover;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        .stats-section {
            background: linear-gradient(135deg, var(--pastel-mint) 0%, var(--pastel-lavender) 100%);
            padding: 50px 0;
            margin: 40px 0;
            border-radius: 15px;
        }

        .stat-item {
            text-align: center;
            padding: 20px;
        }

        .stat-number {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--text-dark);
        }

        .stat-label {
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        .badge-custom {
            background-color: var(--pastel-blue);
            color: var(--text-dark);
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            display: inline-block;
            margin: 0 4px;
        }

        footer {
            background-color: white;
            padding: 40px 0;
            margin-top: 60px;
            color: var(--text-muted);
        }

        @media (max-width: 768px) {
            .hero-section { padding: 40px 0; }
            .stat-number { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="bi bi-wallet2 me-2"></i>
                Бюджет для граждан
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#">Главная</a></li>
                    <li class="nav-item"><a class="nav-link" href="#faq">Вопросы и ответы</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacts">Контакты</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <section class="hero-section">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-8">
                    <h1>Бюджет в вопросах и ответах</h1>
                    <p>Часто задаваемые вопросы о городском бюджете, налогах и муниципальных расходах. Получите ответы от финансовых экспертов.</p>
                </div>
                <div class="col-lg-4 text-center">
                    <img src="images/1.jpg" alt="Budget" class="img-fluid rounded-3 shadow" style="max-height: 300px; width: auto;">
                </div>
            </div>
        </div>
    </section>

    <div class="container">
        <div class="row">
            <div class="col-md-4">
                <div class="info-card">
                    <img src="images/2.jpg" alt="Консультация">
                    <h3>Бесплатная консультация</h3>
                    <p>Задайте свой вопрос финансовым экспертам</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="info-card">
                    <img src="images/3.jpg" alt="Прозрачность">
                    <h3>Прозрачность</h3>
                    <p>Вся информация о бюджете открыта</p>
                </div>
            </div>
            <div class="col-md-4">
                <div class="info-card">
                    <img src="images/4.jpg" alt="Поддержка">
                    <h3>Поддержка</h3>
                    <p>Помогаем разобраться в финансах</p>
                </div>
            </div>
        </div>

        <div class="stats-section">
            <div class="container">
                <div class="row">
                    <div class="col-md-3 col-6">
                        <div class="stat-item">
                            <div class="stat-number">15+</div>
                            <div class="stat-label">Вопросов в базе</div>
                        </div>
                    </div>
                    <div class="col-md-3 col-6">
                        <div class="stat-item">
                            <div class="stat-number">1000+</div>
                            <div class="stat-label">Ответов дано</div>
                        </div>
                    </div>
                    <div class="col-md-3 col-6">
                        <div class="stat-item">
                            <div class="stat-number">50+</div>
                            <div class="stat-label">Экспертов</div>
                        </div>
                    </div>
                    <div class="col-md-3 col-6">
                        <div class="stat-item">
                            <div class="stat-number">24/7</div>
                            <div class="stat-label">Доступность</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="search-box" id="faq">
            <h2 class="text-center mb-4">
                <i class="bi bi-search me-2"></i>
                Найдите ответ на свой вопрос
            </h2>
            <div class="row justify-content-center">
                <div class="col-lg-8">
                    <input type="text" class="form-control form-control-lg" id="searchInput" placeholder="Введите ключевые слова...">
                    <div class="text-center mt-3">
                        <span class="badge-custom">налоги</span>
                        <span class="badge-custom">бюджет</span>
                        <span class="badge-custom">льготы</span>
                        <span class="badge-custom">субсидии</span>
                    </div>
                </div>
            </div>
        </div>

        <div class="mb-5">
            <h2 class="text-center mb-4">Часто задаваемые вопросы</h2>
            <div class="accordion" id="faqAccordion">
                <!-- ВОПРОСЫ (оставьте все 15 как у вас были, они правильные) -->
                <div class="accordion-item">
                    <h2 class="accordion-header">
                        <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#faq1">
                            <i class="bi bi-question-circle-fill accordion-icon"></i>
                            Что такое городской бюджет и из чего он формируется?
                        </button>
                    </h2>
                    <div id="faq1" class="accordion-collapse collapse show" data-bs-parent="#faqAccordion">
                        <div class="accordion-body">
                            <strong>Городской бюджет</strong> — это форма образования и расходования денежных средств...<br><br>
                            <strong>Источники формирования:</strong>
                            <ul><li>Налоговые доходы (НДФЛ, земельный налог, налог на имущество)</li><li>Неналоговые доходы (аренда муниципального имущества)</li><li>Безвозмездные поступления из вышестоящих бюджетов</li></ul>
                        </div>
                    </div>
                </div>
                <!-- Добавьте остальные 14 вопросов по аналогии с вашим кодом -->
            </div>
        </div>
    </div>

    <footer id="contacts">
        <div class="container">
            <div class="row">
                <div class="col-md-6 mb-3">
                    <h5>Контактная информация</h5>
                    <p><i class="bi bi-geo-alt me-2"></i>г. Москва, ул. Примерная, д. 1</p>
                    <p><i class="bi bi-telephone me-2"></i>8 (800) 123-45-67</p>
                    <p><i class="bi bi-envelope me-2"></i>budget@city.gov.ru</p>
                </div>
                <div class="col-md-6 mb-3">
                    <h5>Полезные ссылки</h5>
                    <ul class="list-unstyled">
                        <li><a href="#" class="text-decoration-none text-muted">Открытый бюджет РФ</a></li>
                        <li><a href="#" class="text-decoration-none text-muted">Федеральная налоговая служба</a></li>
                        <li><a href="#" class="text-decoration-none text-muted">Портал Госуслуг</a></li>
                    </ul>
                </div>
            </div>
            <hr>
            <p>&copy; 2026 Бюджет для граждан. Все права защищены.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <script>
        document.getElementById('searchInput').addEventListener('input', function(e) {
            const searchTerm = e.target.value.toLowerCase();
            const accordionItems = document.querySelectorAll('.accordion-item');
            accordionItems.forEach(item => {
                const text = item.textContent.toLowerCase();
                item.style.display = text.includes(searchTerm) ? 'block' : 'none';
            });
        });
    </script>
</body>
</html>
