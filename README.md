# Portfolio-
Abubakri Abdul malik 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdulmalik Abubakri | Conversion Copywriter</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #111322;
            --secondary: #1f2240;
            --accent: #f05454;
            --accent-light: #ff8a71;
            --gold: #c9a227;
            --text-light: #f8f9fa;
            --text-muted: #8c8f9f;
            --bg-light: #f7f7fb;
            --bg-card: #ffffff;
            --border: #e1e3ef;
            --shadow: rgba(17, 19, 34, 0.08);
            --shadow-hover: rgba(17, 19, 34, 0.15);
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-light);
            color: var(--primary);
            line-height: 1.7;
            overflow-x: hidden;
        }
        h1, h2, h3, h4, h5, h6 {
            font-family: 'Playfair Display', serif;
            font-weight: 600;
            line-height: 1.3;
        }
        a { text-decoration: none; color: inherit; transition: all 0.3s ease; }
        .navbar {
            position: fixed; top: 0; left: 0; right: 0; z-index: 1000;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            padding: 1rem 5%;
            display: flex; justify-content: space-between; align-items: center;
            box-shadow: 0 2px 20px var(--shadow);
            transition: all 0.3s ease;
        }
        .navbar.scrolled { padding: 0.7rem 5%; }
        .logo { font-family: 'Playfair Display', serif; font-size: 1.5rem; font-weight: 700; color: var(--primary); }
        .logo span { color: var(--accent); }
        .nav-links { display: flex; list-style: none; gap: 2rem; }
        .nav-links a { font-size: 0.95rem; font-weight: 500; color: var(--secondary); position: relative; padding: 0.5rem 0; }
        .nav-links a::after {
            content: ''; position: absolute; bottom: 0; left: 0; width: 0; height: 2px; background: var(--accent); transition: width 0.3s ease;
        }
        .nav-links a:hover::after { width: 100%; }
        .nav-cta { background: var(--primary); color: var(--text-light) !important; padding: 0.75rem 1.5rem !important; border-radius: 999px; }
        .nav-cta:hover { background: var(--accent); }
        .nav-cta::after { display: none !important; }
        .mobile-menu { display: none; flex-direction: column; gap: 5px; cursor: pointer; padding: 10px; }
        .mobile-menu span { width: 25px; height: 2px; background: var(--primary); transition: all 0.3s ease; }
        .hero {
            min-height: 100vh; display: flex; align-items: center;
            padding: 8rem 5% 4rem;
            background: linear-gradient(135deg, var(--bg-light) 0%, #f0f0f5 100%);
            position: relative; overflow: hidden;
        }
        .hero::before {
            content: ''; position: absolute; top: -50%; right: -20%;
            width: 70%; height: 150%;
            background: radial-gradient(circle, rgba(240, 84, 84, 0.08) 0%, transparent 70%);
        }
        .hero-content {
            max-width: 1400px; margin: 0 auto;
            display: grid; grid-template-columns: 1fr 1fr;
            gap: 4rem; align-items: center; width: 100%;
        }
        .hero-text { z-index: 1; }
        .hero-badge {
            display: inline-block; background: rgba(240, 84, 84, 0.12);
            color: var(--accent); padding: 0.5rem 1rem;
            border-radius: 50px; font-size: 0.85rem; font-weight: 500;
            margin-bottom: 1.5rem;
        }
        .hero h1 {
            font-size: 3.5rem; color: var(--primary);
            margin-bottom: 1.5rem; line-height: 1.1;
        }
        .hero h1 span { color: var(--accent); }
        .hero p {
            font-size: 1.15rem; color: var(--text-muted);
            margin-bottom: 2rem; max-width: 520px;
        }
        .hero-buttons { display: flex; gap: 1rem; margin-bottom: 3rem; flex-wrap: wrap; }
        .btn {
            padding: 1rem 2rem; border-radius: 50px;
            font-weight: 600; font-size: 0.95rem; cursor: pointer;
            transition: all 0.3s ease; border: none;
            display: inline-flex; align-items: center; gap: 0.5rem;
        }
        .btn svg { width: 20px; height: 20px; }
        .btn-primary { background: var(--primary); color: var(--text-light); }
        .btn-primary:hover {
            background: var(--accent); transform: translateY(-2px);
            box-shadow: 0 10px 30px rgba(240, 84, 84, 0.3);
        }
        .btn-secondary {
            background: transparent; color: var(--primary);
            border: 2px solid var(--border);
        }

   
